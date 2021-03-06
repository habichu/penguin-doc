---
layout: component
title:  "Alert"
---

Alert is a feedback message for the user. This alert can be a success, error, warning or info message.

##simple alert
<div class="penguin-example">
	<p class="modifier">.alert--sucess</p>
	<div class="alert alert--success" role="alert" data-alert>
	    <div class="alert__content">
	        <strong>Well done!</strong> You successfully read this important alert message.
	    </div>
	</div>
	<p class="modifier">.alert--error</p>
	<div class="alert alert--error" role="alert" data-alert>
	    <div class="alert__content">
	        <strong>Oh snap!</strong> Change a few things up and try submitting again.
	    </div>
	</div>
	<p class="modifier">.alert--info</p>
	<div class="alert alert--info" role="alert" data-alert>
	    <div class="alert__content">
	        <strong>Heads up!</strong> This alert needs your attention, but it's not super important.
	    </div>
	</div>
	<p class="modifier">.alert--warning</p>
	<div class="alert alert--warning" role="alert" data-alert>
		<div class="alert__content">
	        <strong>Warning!</strong> Better check yourself, you're not looking too good.
	    </div>
	</div>
</div>
{% highlight html %}
<div class="alert alert--modifier" role="alert" data-alert>
    <div class="alert__content">
        Alert content
    </div>
</div>
{% endhighlight %}





##alert inline with align
<div class="penguin-example">
	<p class="modifier">.alert--inline</p>
	<div class="alert alert--success alert--inline" role="alert" data-alert="">
	    <div class="alert__content">
	        <strong>Well done!</strong> You successfully read this important alert message.
	    </div>
	</div>

	<p class="modifier">.alert--inline.alert--center</p>
	<div class="alert alert--error alert--inline alert--center" role="alert" data-alert="">
	    <div class="alert__content">
	        <strong>Oh snap!</strong> Change a few things up and try submitting again.
	    </div>
	</div>

	<p class="modifier">.alert--inline.alert--right</p>
	<div class="alert alert--info alert--inline alert--right" role="alert" data-alert="">
	    <div class="alert__content">
	        <strong>Heads up!</strong> This alert needs your attention, but it's not super important.
	    </div>
	</div>
</div>
{% highlight html %}
<div class="alert alert--inline alert--modifier" role="alert" data-alert>
    <div class="alert__content">
        Alert content
    </div>
</div>
{% endhighlight %}





##closeable alert

<div class="penguin-example">
	<div class="alert alert--info" role="alert" data-alert="">
	    <div class="alert__content">
	        <strong>Heads up!</strong> This alert needs your attention, but it's not super important.
	        <button type="button" title="close" data-close="alert" class="alert__close">
	        	<i class="icon icon--invert" aria-hidden="true">
	        		<svg style="fill: black;" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 512 512" enable-background="new 0 0 512 512" xml:space="preserve">
						<polygon points="438.393,374.595 319.757,255.977 438.378,137.348 374.595,73.607 255.995,192.225 137.375,73.622 
				73.607,137.352 192.246,255.983 73.622,374.625 137.352,438.393 256.002,319.734 374.652,438.378 "/>
					</svg>
				</i>
				<span class="invisible">Close</span>
			</button>
	    </div>
	</div>
</div>
{% highlight html %}
<div class="alert alert--modifier" role="alert" data-alert>
    <div class="alert__content">
        Alert content
        <button type="button" title="close" data-close="alert" class="alert__close">
            <i class="icon icon--invert" aria-hidden="true">*Your icon here*</i>
            <span class="invisible">Close text</span>
        </button>
    </div>
</div>
{% endhighlight %}


##how to use

| Class modifier                                             | Description                           |
|------------------------------------------------------------|---------------------------------------|
| .alert--success .alert--info .alert--warning .alert--error | Styles for each type of alerts.       |
| .alert--inline                                             | Places alert inline with fluid width. |
| .alert--inline alert--center                               | Centers the alert.                    |
| .alert--inline alert--right                                | Align to right the alert.             |


> Add [data-alert] attribute to element and [data-close="alert"] to your close button to automatically give an alert close functionality.

{% highlight js %}
// Initialize
var $alert = $('target').alert();

// Closes an alert by removing it from the DOM
$alert.hide();
{% endhighlight %}