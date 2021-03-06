---
layout: component
title:  "Button"
---

Usually a button indicates a user action.

##simple button
<div class="penguin-example">
	<div class="penguin-example__row">
		<button class="btn btn--primary">Primary</button>
	</div>
	<div class="penguin-example__row">
		<button class="btn btn--secondary">Secondary</button>
	</div>
	<div class="penguin-example__row">
		<button class="btn btn--disabled">Disabled</button>
	</div>
	<div class="penguin-example__row">
		<button class="btn btn--btn--custom-name">Custom button</button>
	</div>
</div>

{% highlight html %}
<button class="btn btn--modifier">Button</button>
{% endhighlight %}


##buttons group
<div class="penguin-example">
	<ul class="btn-group">
	    <li class="btn-group__item"><button class="btn btn--primary">Primary</button></li>
	    <li class="btn-group__item"><button class="btn btn--secondary">Secondary</button></li>
	    <li class="btn-group__item"><button class="btn btn--disabled">Disabled</button></li>
	</ul>
</div>
{% highlight html %}
<ul class="btn-group">
    <li class="btn-group__item">
         <button class="btn">Button</button>
    </li>
    <li class="btn-group__item">
         <button class="btn">Button</button>
    </li>
    <li class="btn-group__item">
         <button class="btn btn--disabled">Disabled</button>
    </li>
</ul>
{% endhighlight %}

##text &amp; icon buttons
<div class="penguin-example">
	<ul class="btn-group">
	    <li>
	        <button class="btn btn--primary">
	            <span class="icon-text"><i class="icon" aria-hidden="true">
	            	<svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
						 viewBox="0 0 512 512" xml:space="preserve">
						<path d="M160.879,312.387V205.609h117.064v-39.627l93.178,93.016l-93.178,93.018v-39.629H160.879z M90,256
							c0,91.756,74.258,166,166,166c91.755,0,166-74.258,166-166c0-91.755-74.258-166-166-166C164.245,90,90,164.259,90,256z M462,256
							c0,113.771-92.229,206-206,206S50,369.771,50,256c0-113.771,92.229-206,206-206S462,142.229,462,256z"/>
					</svg>
	            </i>Button 1</span>
	        </button>
	    </li>
	    <li>
	        <button class="btn btn--primary">
	            <span class="icon-text"><i class="icon" aria-hidden="true">
	            	<svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
						  viewBox="0 0 512 512" xml:space="preserve">
						<path d="M160.879,312.387V205.609h117.064v-39.627l93.178,93.016l-93.178,93.018v-39.629H160.879z M90,256
							c0,91.756,74.258,166,166,166c91.755,0,166-74.258,166-166c0-91.755-74.258-166-166-166C164.245,90,90,164.259,90,256z M462,256
							c0,113.771-92.229,206-206,206S50,369.771,50,256c0-113.771,92.229-206,206-206S462,142.229,462,256z"/>
					</svg>
	            </i>Button 2</span>
	        </button>
	    </li>
	</ul>
</div>
{% highlight html %}
<ul class="btn-group">
    <li>
        <button class="btn btn--modifier">
            <span class="icon-text">
                <i class="icon" aria-hidden="true">*Your icon here*</i>Button 1
            </span>
        </button>
    </li>
    <li>
        <button class="btn btn--modifier">
            <span class="icon-text">
                <i class="icon" aria-hidden="true">*Your icon here*</i>Button 2
            </span>
        </button>
    </li>
</ul>
{% endhighlight %}

##just icon buttons
<div class="penguin-example">
	<ul class="btn-group">
	    <li>
	        <button class="btn btn--primary btn--icon">
	            <i class="icon" aria-hidden="true">
	            	<svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
						 viewBox="0 0 512 512" xml:space="preserve">
						<path d="M160.879,312.387V205.609h117.064v-39.627l93.178,93.016l-93.178,93.018v-39.629H160.879z M90,256
							c0,91.756,74.258,166,166,166c91.755,0,166-74.258,166-166c0-91.755-74.258-166-166-166C164.245,90,90,164.259,90,256z M462,256
							c0,113.771-92.229,206-206,206S50,369.771,50,256c0-113.771,92.229-206,206-206S462,142.229,462,256z"/>
					</svg>
	            </i>
	            <span class="invisible">text</span>
	        </button>
	    </li>
	    <li>
	        <button class="btn btn--primary btn--icon ">
	            <i class="icon" aria-hidden="true">
	            	<svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
							 viewBox="0 0 512 512" xml:space="preserve">
						<path d="M391.332,362.891l-41.295-49.262c-7.564,11.041-20.262,17.287-34.656,17.287
							c-31.631,0-40.482-26.475-59.344-26.475c-21.703,0-29.037,26.475-58.42,26.475c-14.393,0-28.092-6.246-35.656-17.287l-41.295,49.262
							c-29.484,29.484-80.271,7.361-69.084-37.391l40.24-165.834c3.52-14.084,16.174-23.963,30.688-23.963h266.979
							c14.516,0,27.168,9.879,30.688,23.963L460.418,325.5C471.604,370.252,420.818,392.375,391.332,362.891z M174.537,218.193h26.086
							v-20.645h-26.086v-26.084h-20.643v26.084h-26.086v20.645h26.086v26.086h20.643V218.193z M221.215,285.131
							c0-12.459-10.137-22.595-22.598-22.595c-12.459,0-22.594,10.136-22.594,22.595c0,12.46,10.135,22.596,22.594,22.596
							C211.078,307.727,221.215,297.591,221.215,285.131z M241.156,244.279h29.486v-12.744h-29.486V244.279z M335.975,285.131
							c0-12.459-10.135-22.595-22.594-22.595s-22.598,10.136-22.598,22.595c0,12.46,10.139,22.596,22.598,22.596
							S335.975,297.591,335.975,285.131z M331.639,199.111c-4.836-4.836-12.678-4.836-17.518,0c-4.838,4.84-4.838,12.682,0,17.52
							c4.838,4.836,12.682,4.836,17.518,0C336.477,211.793,336.477,203.951,331.639,199.111z M359.041,224.346
							c-4.838-4.836-12.682-4.836-17.52,0c-4.836,4.836-4.836,12.68,0,17.518c4.838,4.838,12.682,4.838,17.52,0
							C363.877,237.025,363.877,229.182,359.041,224.346z M359.041,174.346c-4.838-4.838-12.682-4.838-17.52,0
							c-4.836,4.836-4.836,12.68,0,17.518c4.838,4.836,12.682,4.836,17.52,0C363.877,187.025,363.877,179.182,359.041,174.346z
							 M386.359,199.111c-4.838-4.836-12.682-4.836-17.518,0c-4.838,4.84-4.838,12.682,0,17.52c4.836,4.836,12.68,4.836,17.518,0
							C391.195,211.793,391.195,203.951,386.359,199.111z"/>
					</svg>
	            </i>
	            <span class="invisible">text</span>
	        </button>
	    </li>
	</ul>
</div>
{% highlight html %}
<ul class="btn-group">
    <li>
        <button class="btn btn--modifier btn--icon">
            <i class="icon" aria-hidden="true">*Your icon here*</i>
            <span class="invisible">text</span>
        </button>
    </li>
    <li>
        <button class="btn btn--modifier btn--icon">
            <i class="icon" aria-hidden="true">*Your icon here*</i>
            <span class="invisible">text</span>
        </button>
    </li>
</ul>
{% endhighlight %}

##How to use

| Modifier class    | Description                      |
|-------------------|----------------------------------|
| .btn--primary     | Adds primary styles.             |
| .btn--secondary   | Adds secondary styles.           |
| .btn--disabled    | Adds styles to disabled buttons. |
| .btn--custom-name | Any name for your custom button. |


##Sass mixins

You can create your own buttons using our Sass mixins:

{% highlight scss %}
@mixin button($color, $background, $border, $border-color) {
    color: $color;
    background-color: $background;
    @if $border != none {
        border: $border $border-color;
    }
}

@mixin button-events($color-hover, $background-hover, $border-color-hover, $background-active) {
    &:hover,
    &:focus {
        color: $color-hover;
        background-color: $background-hover;
        text-decoration: $button-text-decoration;
        @if $border-color-hover != none {
            border-color: $border-color-hover;
        }
    }
    &:active {
        background-color: $background-active;
    }
}
{% endhighlight %}

###example

{% highlight scss %}
.btn--penguin {
    @include button(#fff, #000, 1px solid, #FA8500);
    @include button-events(#fff, #333, #FFA947, #000);
}
{% endhighlight %}

