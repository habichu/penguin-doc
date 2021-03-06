---
layout: component
title:  "Icon"
---

Icons can be handled in different ways: sprite, iconic fonts, inline svg, css background

###how to use

| Class name                     | Description                                                   |
| ----------                     | -----------                                                   |
| icon              | Adds base styles                                              |
| icon--{icon-name} | Class for desired icon. Icon name will be the image file name |


<div class="penguin-example">
        <i class="icon icon--invert" aria-hidden="true">
            <svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 512 512" enable-background="new 0 0 512 512" xml:space="preserve">
                <path d="M305.041,131.559c-10.059-5.773-16.285-16.529-16.266-28.125c0-0.02,0-0.039,0-0.059
                c0-18.1-14.676-32.773-32.775-32.773c-18.102,0-32.775,14.674-32.775,32.773c0,0.02,0,0.039,0,0.059
                c0.02,11.609-6.195,22.346-16.266,28.125C133.987,173.444,175.918,312.55,99.67,337.134v32.492h312.66v-32.492
                C336.082,312.548,378.014,173.442,305.041,131.559z M256,90.08c7.332,0,13.297,5.963,13.297,13.297
                c0,7.332-5.965,13.297-13.297,13.297s-13.299-5.965-13.299-13.297C242.701,96.043,248.668,90.08,256,90.08z M301.15,396.7
                c0,24.688-20.014,44.698-44.701,44.698c-24.686,0-44.699-20.011-44.699-44.698H301.15z M401.299,214.956
                c3.375,13.572,0.934,27.23-5.748,38.34l18.275,10.99c9.496-15.785,12.965-35.195,8.166-54.482
                c-4.803-19.289-16.969-34.801-32.756-44.295l-10.986,18.275C389.357,190.466,397.916,201.384,401.299,214.956z M458.722,200.661
                c-7.326-29.434-25.886-53.106-49.974-67.591l-11.268,18.732c19.295,11.604,34.162,30.565,40.031,54.138
                c5.864,23.576,1.625,47.295-9.98,66.588l18.733,11.268C460.749,259.704,466.048,230.093,458.722,200.661z M133.75,183.784
                l-10.986-18.275c-15.787,9.494-27.953,25.006-32.756,44.295c-4.799,19.287-1.33,38.697,8.166,54.482l18.275-10.99
                c-6.682-11.109-9.123-24.768-5.748-38.34C114.084,201.384,122.643,190.466,133.75,183.784z M65.735,283.796l18.734-11.268
                c-11.605-19.293-15.846-43.012-9.98-66.588c5.869-23.572,20.736-42.534,40.031-54.138l-11.268-18.732
                c-24.088,14.484-42.648,38.157-49.975,67.591C45.952,230.093,51.25,259.704,65.735,283.796z"></path>
            </svg>
        </i>
</div>
{% highlight html %}
<i class="icon icon--bell" aria-hidden="true"></i>
{% endhighlight %}

##icon with text

> If icon have text, add a parent span with class "icon-text"

<div class="penguin-example">
    <span class="icon-text">
        <i class="icon icon--invert" aria-hidden="true">
            <svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 512 512" enable-background="new 0 0 512 512" xml:space="preserve"> <path d="M160.879,312.387V205.609h117.064v-39.627l93.178,93.016l-93.178,93.018v-39.629H160.879z M90,256
            c0,91.756,74.258,166,166,166c91.755,0,166-74.258,166-166c0-91.755-74.258-166-166-166C164.245,90,90,164.259,90,256z M462,256
            c0,113.771-92.229,206-206,206S50,369.771,50,256c0-113.771,92.229-206,206-206S462,142.229,462,256z"></path> </svg>
        </i>
        Icon text
    </span>
</div>
{% highlight html %}
<span class="icon-text">
    <i class="icon icon--invert" aria-hidden="true">
        *Your icon here*
    </i>
    Button 1
</span>
{% endhighlight %}

<div class="penguin-example">
<button class="btn btn--primary">
    <span class="icon-text">
        <i class="icon" aria-hidden="true">
        <svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 512 512" enable-background="new 0 0 512 512" xml:space="preserve"> <path d="M160.879,312.387V205.609h117.064v-39.627l93.178,93.016l-93.178,93.018v-39.629H160.879z M90,256
        c0,91.756,74.258,166,166,166c91.755,0,166-74.258,166-166c0-91.755-74.258-166-166-166C164.245,90,90,164.259,90,256z M462,256
        c0,113.771-92.229,206-206,206S50,369.771,50,256c0-113.771,92.229-206,206-206S462,142.229,462,256z"></path> </svg>
        </i>Button 1</span>
</button>
</div>
{% highlight html %}
<button class="btn btn--primary">
    <span class="icon-text"><i class="icon" aria-hidden="true"></i>Button 1</span>
</button>
{% endhighlight %}

##iconic fonts

penguin can use iconic fonts like [font awesome](http://fortawesome.github.io/Font-Awesome/ "font awesome web"), gives you scalable vector icons that can instantly be customized — size, color, drop shadow, and anything that can be done with CSS. [Documentation for installation](http://fortawesome.github.io/Font-Awesome/get-started/ "font awesome web")

<div class="penguin-example">
    <i class="icon icon--invert" aria-hidden="true">
        <svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 512 512" enable-background="new 0 0 512 512" xml:space="preserve"> <polygon points="398.218,92.985 199.729,291.475 113.754,205.476 50,269.242 199.733,419.015 462,156.726 "></polygon> </svg>
    </i>
</div>
{% highlight html %}
<i class="fa fa-check"></i>
{% endhighlight %}

<div class="penguin-example">
    <span class="icon-text">
    <i class="icon icon--invert" aria-hidden="true">
        <svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 512 512" enable-background="new 0 0 512 512" xml:space="preserve"> <polygon points="398.218,92.985 199.729,291.475 113.754,205.476 50,269.242 199.733,419.015 462,156.726 "></polygon> </svg>
    </i>
    Accept terms
    </span>
</div>
{% highlight html %}
<span class="icon-text"><i class="fa fa-check"></i>Accept terms</span>
{% endhighlight %}


Other iconic font system recomended is [fontello](http://fontello.com/ "fontello web")

##inline svg

We can add directly svg code inside the <i> tag.

<div class="penguin-example">
<i class="icon" aria-hidden="true">
    <svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 512 512" enable-background="new 0 0 512 512" xml:space="preserve">
        <path style="fill: black" d="M160.879,312.387V205.609h117.064v-39.627l93.178,93.016l-93.178,93.018v-39.629H160.879z M90,256
            c0,91.756,74.258,166,166,166c91.755,0,166-74.258,166-166c0-91.755-74.258-166-166-166C164.245,90,90,164.259,90,256z M462,256
            c0,113.771-92.229,206-206,206S50,369.771,50,256c0-113.771,92.229-206,206-206S462,142.229,462,256z"></path>
    </svg>
</i>
</div>

{% highlight html %}
<i class="icon" aria-hidden="true">
    <svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 512 512" enable-background="new 0 0 512 512" xml:space="preserve">
        <path d="M160.879,312.387V205.609h117.064v-39.627l93.178,93.016l-93.178,93.018v-39.629H160.879z M90,256
            c0,91.756,74.258,166,166,166c91.755,0,166-74.258,166-166c0-91.755-74.258-166-166-166C164.245,90,90,164.259,90,256z M462,256
            c0,113.771-92.229,206-206,206S50,369.771,50,256c0-113.771,92.229-206,206-206S462,142.229,462,256z"></path>
    </svg>
</i>
{% endhighlight %}

##css background

In this option, we call icon directly 

<div class="penguin-example">
    <i class="icon icon--invert" aria-hidden="true">
        <svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"  viewBox="0 0 512 512" enable-background="new 0 0 512 512" xml:space="preserve">
            <polygon points="256,60.082 318.979,190.002 462.001,209.75 357.9,309.793 383.315,451.918 256,383.828
128.685,451.918 154.1,309.793 49.999,209.75 193.021,190.002 "></polygon>
        </svg>
    </i>
</div>
{% highlight css %}
.icon-star {
  width: 32px;
  height: 32px;
  color: red;
  background: url(path/star.svg);
  background-size: 32px 32px;
}

<i class="icon icon-star"></i>
{% endhighlight %}