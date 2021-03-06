---
layout: component
title:  "Grid"
---

Grids on demand are awesome. They are semantic, flexible and powerful. We combine [susy](http://susy.oddbird.net/) with [breakpoint-slicer](https://github.com/lolmaus/breakpoint-slicer) and [breakpoint](https://github.com/at-import/breakpoint) to manage the layout, the grid and the breakpoints.

If grids on demand don't like you doesn't matter penguin has a solution. By default **penguin includes a grid system** allows you to create a responsive grid layout just using the proper css classes. Be sure set to true the $grid-system variable.

By default, these are the sass variables values:

{% highlight scss %}
// Grid
$grid-columns             : 12;
$grid-gutter              : 30;
{% endhighlight %}

###breakpoints

Also we can set breakpoints, and their names:

{% highlight scss %}
// Breakpoints
$slicer-breakpoints       : 0   400px   600px   800px   1050px;
$slicer-breakpoint-names  :  'a'     'b'     'c'     'd'      'e';
{% endhighlight %}

####generated grid example

| Slicer name    | mediaquery                                  |
|----------------|---------------------------------------------|
| a              | (max-width: 400px)                          |
| b              | (min-width: 401px) and (max-width: 600)     |
| c              | (min-width: 601px) and (max-width: 800)     |
| d              | (min-width: 801px) and (max-width: 1050)    |
| e              | (min-width: 1050px)                         |

<div class="row penguin-example">
    <!-- 12 -->
    <div class="col-a-12 col-c-12 col-d-12 col-e-12">
        <span class="fill-col">.col-[var]-12</span>
    </div>
    <!-- 11 -->
    <div class="col-a-11 col-b-11 col-c-11 col-d-11 col-e-11">
        <span class="fill-col">.col-[var]-11</span>
    </div>
    <div class="col-a-1 col-b-1 col-c-1 col-d-1 col-e-1">
        <span class="fill-col">.col-[var]-1</span>
    </div>
    <!-- 10 -->
    <div class="col-a-10 col-b-10 col-c-10 col-d-10 col-e-10">
        <span class="fill-col">.col-[var]-10</span>
    </div>
    <div class="col-a-2 col-b-2 col-c-2 col-d-2 col-e-2">
        <span class="fill-col">.col-[var]-2</span>
    </div>
    <!-- 9 -->
    <div class="col-a-9 col-b-9 col-c-9 col-d-9 col-e-9">
        <span class="fill-col">.col-[var]-9</span>
    </div>
    <div class="col-a-3 col-b-3 col-c-3 col-d-3 col-e-3">
        <span class="fill-col">.col-[var]-3</span>
    </div>
    <!-- 8 -->
    <div class="col-a-8 col-b-8 col-c-8 col-d-8 col-e-8">
        <span class="fill-col">.col-[var]-8</span>
    </div>
    <div class="col-a-4 col-b-4 col-c-4 col-d-4 col-e-4">
        <span class="fill-col">.col-[var]-4</span>
    </div>
    <!-- 7 -->
    <div class="col-a-7 col-b-7 col-c-7 col-d-7 col-e-7">
        <span class="fill-col">.col-[var]-7</span>
    </div>
    <div class="col-a-5 col-b-5 col-c-5 col-d-5 col-e-5">
        <span class="fill-col">.col-[var]-5</span>
    </div>
    <!-- 6 -->
    <div class="col-a-6 col-b-6 col-c-6 col-d-6 col-e-6">
        <span class="fill-col">.col-[var]-6</span>
    </div>
    <div class="col-a-6 col-b-6 col-c-6 col-d-6 col-e-6">
        <span class="fill-col">.col-[var]-6</span>
    </div>
    <!-- 5 -->
    <div class="col-a-5 col-b-5 col-c-5 col-d-5 col-e-5">
        <span class="fill-col">.col-[var]-5</span>
    </div>
    <div class="col-a-5 col-b-5 col-c-5 col-d-5 col-e-5">
        <span class="fill-col">.col-[var]-5</span>
    </div>
    <div class="col-a-2 col-b-2 col-c-2 col-d-2 col-e-2">
        <span class="fill-col">.col-[var]-2</span>
    </div>
    <!-- 4 -->
    <div class="col-a-4 col-b-3 col-c-4 col-d-4 col-e-4">
        <span class="fill-col">.col-[var]-4</span>
    </div>
    <div class="col-a-4 col-b-3 col-c-4 col-d-4 col-e-4">
        <span class="fill-col">.col-[var]-4</span>
    </div>
    <div class="col-a-4 col-b-3 col-c-4 col-d-4 col-e-4">
        <span class="fill-col">.col-[var]-4</span>
    </div>
    <!-- 3 -->
    <div class="col-a-3 col-b-3 col-c-3 col-d-3 col-e-3">
        <span class="fill-col">.col-[var]-3</span>
    </div>
    <div class="col-a-3 col-b-3 col-c-3 col-d-3 col-e-3">
        <span class="fill-col">.col-[var]-3</span>
    </div>
    <div class="col-a-3 col-b-3 col-c-3 col-d-3 col-e-3">
        <span class="fill-col">.col-[var]-3</span>
    </div>
    <div class="col-a-3 col-b-3 col-c-3 col-d-3 col-e-3">
        <span class="fill-col">.col-[var]-3</span>
    </div>
    <!-- 2 -->
    <div class="col-a-2 col-b-2 col-c-2 col-d-2 col-e-2">
        <span class="fill-col">.col-[var]-2</span>
    </div>
    <div class="col-a-2 col-b-2 col-c-2 col-d-2 col-e-2">
        <span class="fill-col">.col-[var]-2</span>
    </div>
    <div class="col-a-2 col-b-2 col-c-2 col-d-2 col-e-2">
        <span class="fill-col">.col-[var]-2</span>
    </div>
    <div class="col-a-2 col-b-2 col-c-2 col-d-2 col-e-2">
        <span class="fill-col">.col-[var]-2</span>
    </div>
    <div class="col-a-2 col-b-2 col-c-2 col-d-2 col-e-2">
        <span class="fill-col">.col-[var]-2</span>
    </div>
    <div class="col-a-2 col-b-2 col-c-2 col-d-2 col-e-2">
        <span class="fill-col">.col-[var]-2</span>
    </div>
    <!-- 1 -->
    <div class="col-a-1 col-b-1 col-c-1 col-d-1 col-e-1">
        <span class="fill-col">.col-[var]-1</span>
    </div>
    <div class="col-a-1 col-b-1 col-c-1 col-d-1 col-e-1">
        <span class="fill-col">.col-[var]-1</span>
    </div>
    <div class="col-a-1 col-b-1 col-c-1 col-d-1 col-e-1">
        <span class="fill-col">.col-[var]-1</span>
    </div>
    <div class="col-a-1 col-b-1 col-c-1 col-d-1 col-e-1">
        <span class="fill-col">.col-[var]-1</span>
    </div>
    <div class="col-a-1 col-b-1 col-c-1 col-d-1 col-e-1">
        <span class="fill-col">.col-[var]-1</span>
    </div>
    <div class="col-a-1 col-b-1 col-c-1 col-d-1 col-e-1">
        <span class="fill-col">.col-[var]-1</span>
    </div>
    <div class="col-a-1 col-b-1 col-c-1 col-d-1 col-e-1">
        <span class="fill-col">.col-[var]-1</span>
    </div>
    <div class="col-a-1 col-b-1 col-c-1 col-d-1 col-e-1">
        <span class="fill-col">.col-[var]-1</span>
    </div>
    <div class="col-a-1 col-b-1 col-c-1 col-d-1 col-e-1">
        <span class="fill-col">.col-[var]-1</span>
    </div>
    <div class="col-a-1 col-b-1 col-c-1 col-d-1 col-e-1">
        <span class="fill-col">.col-[var]-1</span>
    </div>
    <div class="col-a-1 col-b-1 col-c-1 col-d-1 col-e-1">
        <span class="fill-col">.col-[var]-1</span>
    </div>
    <div class="col-a-1 col-b-1 col-c-1 col-d-1 col-e-1">
        <span class="fill-col">.col-[var]-1</span>
    </div>
</div>
{% highlight html %}
<div class="row penguin-example">
    <!-- 12 -->
    <div class="col-a-12 col-c-12 col-d-12 col-e-12">
        <span class="fill-col">.col-[var]-12</span>
    </div>
    <!-- 11 -->
    <div class="col-a-11 col-b-11 col-c-11 col-d-11 col-e-11">
        <span class="fill-col">.col-[var]-11</span>
    </div>
    <div class="col-a-1 col-b-1 col-c-1 col-d-1 col-e-1">
        <span class="fill-col">.col-[var]-1</span>
    </div>
    <!-- 10 -->
    <div class="col-a-10 col-b-10 col-c-10 col-d-10 col-e-10">
        <span class="fill-col">.col-[var]-10</span>
    </div>
    <div class="col-a-2 col-b-2 col-c-2 col-d-2 col-e-2">
        <span class="fill-col">.col-[var]-2</span>
    </div>
    <!-- 9 -->
    <div class="col-a-9 col-b-9 col-c-9 col-d-9 col-e-9">
        <span class="fill-col">.col-[var]-9</span>
    </div>
    <div class="col-a-3 col-b-3 col-c-3 col-d-3 col-e-3">
        <span class="fill-col">.col-[var]-3</span>
    </div>
    <!-- 8 -->
    <div class="col-a-8 col-b-8 col-c-8 col-d-8 col-e-8">
        <span class="fill-col">.col-[var]-8</span>
    </div>
    <div class="col-a-4 col-b-4 col-c-4 col-d-4 col-e-4">
        <span class="fill-col">.col-[var]-4</span>
    </div>
    <!-- 7 -->
    <div class="col-a-7 col-b-7 col-c-7 col-d-7 col-e-7">
        <span class="fill-col">.col-[var]-7</span>
    </div>
    <div class="col-a-5 col-b-5 col-c-5 col-d-5 col-e-5">
        <span class="fill-col">.col-[var]-5</span>
    </div>
    <!-- 6 -->
    <div class="col-a-6 col-b-6 col-c-6 col-d-6 col-e-6">
        <span class="fill-col">.col-[var]-6</span>
    </div>
    <div class="col-a-6 col-b-6 col-c-6 col-d-6 col-e-6">
        <span class="fill-col">.col-[var]-6</span>
    </div>
    <!-- 5 -->
    <div class="col-a-5 col-b-5 col-c-5 col-d-5 col-e-5">
        <span class="fill-col">.col-[var]-5</span>
    </div>
    <div class="col-a-5 col-b-5 col-c-5 col-d-5 col-e-5">
        <span class="fill-col">.col-[var]-5</span>
    </div>
    <div class="col-a-2 col-b-2 col-c-2 col-d-2 col-e-2">
        <span class="fill-col">.col-[var]-2</span>
    </div>
    <!-- 4 -->
    <div class="col-a-4 col-b-3 col-c-4 col-d-4 col-e-4">
        <span class="fill-col">.col-[var]-4</span>
    </div>
    <div class="col-a-4 col-b-3 col-c-4 col-d-4 col-e-4">
        <span class="fill-col">.col-[var]-4</span>
    </div>
    <div class="col-a-4 col-b-3 col-c-4 col-d-4 col-e-4">
        <span class="fill-col">.col-[var]-4</span>
    </div><br>    <!-- 3 -->
    <div class="col-a-3 col-b-3 col-c-3 col-d-3 col-e-3">
        <span class="fill-col">.col-[var]-3</span>
    </div>
    <div class="col-a-3 col-b-3 col-c-3 col-d-3 col-e-3">
        <span class="fill-col">.col-[var]-3</span>
    </div>
    <div class="col-a-3 col-b-3 col-c-3 col-d-3 col-e-3">
        <span class="fill-col">.col-[var]-3</span>
    </div>
    <div class="col-a-3 col-b-3 col-c-3 col-d-3 col-e-3">
        <span class="fill-col">.col-[var]-3</span>
    </div>
    <!-- 2 -->
    <div class="col-a-2 col-b-2 col-c-2 col-d-2 col-e-2">
        <span class="fill-col">.col-[var]-2</span>
    </div>
    <div class="col-a-2 col-b-2 col-c-2 col-d-2 col-e-2">
        <span class="fill-col">.col-[var]-2</span>
    </div>
    <div class="col-a-2 col-b-2 col-c-2 col-d-2 col-e-2">
        <span class="fill-col">.col-[var]-2</span>
    </div>
    <div class="col-a-2 col-b-2 col-c-2 col-d-2 col-e-2">
        <span class="fill-col">.col-[var]-2</span>
    </div>
    <div class="col-a-2 col-b-2 col-c-2 col-d-2 col-e-2">
        <span class="fill-col">.col-[var]-2</span>
    </div>
    <div class="col-a-2 col-b-2 col-c-2 col-d-2 col-e-2">
        <span class="fill-col">.col-[var]-2</span>
    </div>
    <!-- 1 -->
    <div class="col-a-1 col-b-1 col-c-1 col-d-1 col-e-1">
        <span class="fill-col">.col-[var]-1</span>
    </div>
    <div class="col-a-1 col-b-1 col-c-1 col-d-1 col-e-1">
        <span class="fill-col">.col-[var]-1</span>
    </div>
    <div class="col-a-1 col-b-1 col-c-1 col-d-1 col-e-1">
        <span class="fill-col">.col-[var]-1</span>
    </div>
    <div class="col-a-1 col-b-1 col-c-1 col-d-1 col-e-1">
        <span class="fill-col">.col-[var]-1</span>
    </div>
    <div class="col-a-1 col-b-1 col-c-1 col-d-1 col-e-1">
        <span class="fill-col">.col-[var]-1</span>
    </div>
    <div class="col-a-1 col-b-1 col-c-1 col-d-1 col-e-1">
        <span class="fill-col">.col-[var]-1</span>
    </div>
    <div class="col-a-1 col-b-1 col-c-1 col-d-1 col-e-1">
        <span class="fill-col">.col-[var]-1</span>
    </div>
    <div class="col-a-1 col-b-1 col-c-1 col-d-1 col-e-1">
        <span class="fill-col">.col-[var]-1</span>
    </div>
    <div class="col-a-1 col-b-1 col-c-1 col-d-1 col-e-1">
        <span class="fill-col">.col-[var]-1</span>
    </div>
    <div class="col-a-1 col-b-1 col-c-1 col-d-1 col-e-1">
        <span class="fill-col">.col-[var]-1</span>
    </div>
    <div class="col-a-1 col-b-1 col-c-1 col-d-1 col-e-1">
        <span class="fill-col">.col-[var]-1</span>
    </div>
    <div class="col-a-1 col-b-1 col-c-1 col-d-1 col-e-1">
        <span class="fill-col">.col-[var]-1</span>
    </div>
</div>
{% endhighlight %}
