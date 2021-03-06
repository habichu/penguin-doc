---
layout: component
title: Components
order: 1
permalink: /components/
---

<div class="theme-bar">
    <div class="theme-bar__col theme-bar__select col-a-12">
        <!-- <form action="">
        <label></label>
        </form> -->
        Choose your favorite theme: {% file_lister bower_components/penguin-themes/themes %}
    </div>
    <div class="theme-bar__col theme-bar__buttons col-a-12">
        <ul class="btn-group">
            <li>
                <a id="link-github" href="https://github.com/bq/penguin-themes/tree/master/themes/penguin-doc" class="btn" target="_blank">
                    <span class="icon-text">
                        <i class="icon icon--invert"><svg viewBox="0 0 16 16">
                          <path d="M7.999,0.431c-4.285,0-7.76,3.474-7.76,7.761 c0,3.428,2.223,6.337,5.307,7.363c0.388,0.071,0.53-0.168,0.53-0.374c0-0.184-0.007-0.672-0.01-1.32 c-2.159,0.469-2.614-1.04-2.614-1.04c-0.353-0.896-0.862-1.135-0.862-1.135c-0.705-0.481,0.053-0.472,0.053-0.472 c0.779,0.055,1.189,0.8,1.189,0.8c0.692,1.186,1.816,0.843,2.258,0.645c0.071-0.502,0.271-0.843,0.493-1.037 C4.86,11.425,3.049,10.76,3.049,7.786c0-0.847,0.302-1.54,0.799-2.082C3.768,5.507,3.501,4.718,3.924,3.65 c0,0,0.652-0.209,2.134,0.796C6.677,4.273,7.34,4.187,8,4.184c0.659,0.003,1.323,0.089,1.943,0.261 c1.482-1.004,2.132-0.796,2.132-0.796c0.423,1.068,0.157,1.857,0.077,2.054c0.497,0.542,0.798,1.235,0.798,2.082 c0,2.981-1.814,3.637-3.543,3.829c0.279,0.24,0.527,0.713,0.527,1.437c0,1.037-0.01,1.874-0.01,2.129 c0,0.208,0.14,0.449,0.534,0.373c3.081-1.028,5.302-3.935,5.302-7.362C15.76,3.906,12.285,0.431,7.999,0.431z"/>
                        </svg></i>See theme in gitHub
                    </span>
                </a>
            </li>
            <li>
                <a id="link-css" href="/bower_components/penguin-themes/themes/penguin-doc/dist/css/penguin-doc.css" class="btn" target="_blank">Download CSS (uncompressed)</a>
            </li>
        </ul>
    </div>
</div>

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

<div class="penguin-example">
	<nav class="breadcrumb" role="navigation">
	    <h1 class="invisible">Guía de navegación</h1>
	    <ol class="breadcrumb__menu" itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb">
	        <li class="breadcrumb__menu__item" itemprop="child" itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb">
	            <a class="breadcrumb__menu__link" itemprop="url" href="#"><span itemprop="title">Home</span></a>
	        </li>
	        <li class="breadcrumb__menu__item" itemprop="child" itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb">
	            <a class="breadcrumb__menu__link" itemprop="url" href="#"><span itemprop="title">Category</span></a>
	        </li>
	        <li class="breadcrumb__menu__item" itemprop="child" itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb">
	            <a class="breadcrumb__menu__link" itemprop="url" href="#"><span itemprop="title">Page</span></a>
	        </li>
	    </ol>
	</nav>
</div>

<div class="penguin-example">
	<ul class="btn-group">
	    <li class="btn-group__item"><button class="btn btn--primary">Primary</button></li>
	    <li class="btn-group__item"><button class="btn btn--secondary">Secondary</button></li>
	    <li class="btn-group__item"><button class="btn btn--disabled">Disabled</button></li>
	</ul>
</div>

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

<div class="penguin-example">
    <p class="modifier">btn--primary</p>
    <div class="dropdown">
        <a href="#single_dropdown" class="dropdown__link" data-rel="dropdown">Item 1</a>
        <ul id="single_dropdown" class="dropdown__menu" role="menu" data-dropdown>
            <li class="dropdown__menu__item">
                <a href="#" class="dropdown__menu__link">Item 1</a>
            </li>
            <li class="dropdown__menu__item">
                <a href="#" class="dropdown__menu__link">Item 2</a>
            </li>
            <li class="dropdown__menu__item">
                <a href="#" class="dropdown__menu__link">Item 3</a>
            </li>
        </ul>
    </div>
</div>

<div class="penguin-example">
     <div class="dropdown">
        <a href="#icon_dropdown" class="dropdown__link" data-rel="dropdown">
            <span class="icon-text">
                <i class="icon" aria-hidden="true">
                    <svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
                         viewBox="0 0 512 512" enable-background="new 0 0 512 512" xml:space="preserve">
                        <path d="M160.879,312.387V205.609h117.064v-39.627l93.178,93.016l-93.178,93.018v-39.629H160.879z M90,256
                            c0,91.756,74.258,166,166,166c91.755,0,166-74.258,166-166c0-91.755-74.258-166-166-166C164.245,90,90,164.259,90,256z M462,256
                            c0,113.771-92.229,206-206,206S50,369.771,50,256c0-113.771,92.229-206,206-206S462,142.229,462,256z"/>
                    </svg>
                </i>Item 1
            </span>
        </a>
        <ul id="icon_dropdown" class="dropdown__menu" role="menu" data-dropdown>
            <li class="dropdown__menu__item">
                <a href="#" class="dropdown__menu__link">Item 1</a>
            </li>
            <li class="dropdown__menu__item">
                <a href="#" class="dropdown__menu__link">Item 2</a>
            </li>
            <li class="dropdown__menu__item">
                <a href="#" class="dropdown__menu__link">Item 3</a>
            </li>
        </ul>
    </div>
</div>

<div class="penguin-example">
    <div class="dropdown dropdown--fluid">
        <a href="#fluid_dropdown" class="dropdown__link" data-rel="dropdown">
            <span class="icon-text">
                <i class="icon" aria-hidden="true">
                    <svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
                         viewBox="0 0 512 512" enable-background="new 0 0 512 512" xml:space="preserve">
                        <path d="M160.879,312.387V205.609h117.064v-39.627l93.178,93.016l-93.178,93.018v-39.629H160.879z M90,256
                            c0,91.756,74.258,166,166,166c91.755,0,166-74.258,166-166c0-91.755-74.258-166-166-166C164.245,90,90,164.259,90,256z M462,256
                            c0,113.771-92.229,206-206,206S50,369.771,50,256c0-113.771,92.229-206,206-206S462,142.229,462,256z"/>
                    </svg>
                </i>Item 1
            </span>
        </a>
        <ul id="fluid_dropdown" class="dropdown__menu" role="menu" data-dropdown>
            <li class="dropdown__menu__item">
                <a href="#" class="dropdown__menu__link">Item 1</a>
            </li>
            <li class="dropdown__menu__item">
                <a href="#" class="dropdown__menu__link">Item 2</a>
            </li>
            <li class="dropdown__menu__item">
                <a href="#" class="dropdown__menu__link">Item 3</a>
            </li>
        </ul>
    </div>
</div>

<div class="penguin-example">
    <nav class="nav nav--inline" role="navigation">
        <h1 class="invisible">Navigation</h1>
        <ul class="nav__menu">
            <li class="nav__menu__item dropdown">
                <a href="#menu1" class="nav__menu__link" data-rel="dropdown">Item 1</a>
                <ul id="menu1" class="nav__submenu" role="menu" data-dropdown>
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 1</a></li>
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 2</a></li>
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 3</a></li>
                </ul>
            </li>
            <li class="nav__menu__item dropdown">
                <a href="#menu2" class="nav__menu__link" data-rel="dropdown">Item 2</a>
                <ul id="menu2" class="nav__submenu" role="menu" data-dropdown>
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 1</a></li>
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 2</a></li>
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 3</a></li>
                </ul>
            </li>
            <li class="nav__menu__item dropdown">
                <a href="#menu3" class="nav__menu__link" data-rel="dropdown">Item 3</a>
                <ul id="menu3" class="nav__submenu" role="menu" data-dropdown>
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 1</a></li>
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 2</a></li>
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 3</a></li>
                </ul>
            </li>
            <li class="nav__menu__item dropdown">
                <a href="#menu4" class="nav__menu__link" data-rel="dropdown">Item 4</a>
                <ul id="menu4" class="nav__submenu" role="menu" data-dropdown>
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 1</a></li>
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 2</a></li>
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 3</a></li>
                </ul>
            </li>
        </ul>
    </nav>
</div>

<div class="penguin-example">
	<div class="form">
        <form id="form-login">
            <fieldset>
            <legend>Sample form</legend>
                <!-- input type="email"-->
                <div class="form-control">
                    <label for="email" class="invisible">Email</label>
                    <span class="input input--icon">
                        <input type="email" id="email" name="email" placeholder="Email">
                        <i class="icon icon--invert" aria-hidden="true">
                            <svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
                                     viewBox="0 0 512 512" enable-background="new 0 0 512 512" xml:space="preserve">
                                <path d="M407.448,360.474c-59.036-13.617-113.989-25.541-87.375-75.717
                                    c81.01-152.729,21.473-234.406-64.072-234.406c-87.231,0-145.303,84.812-64.072,234.406c27.412,50.482-29.608,62.393-87.375,75.717
                                    c-59.012,13.609-54.473,44.723-54.473,101.176h411.838C461.919,405.196,466.458,374.083,407.448,360.474z"/>
                            </svg>
                        </i>
                    </span>
                </div>
                <!-- input type="password" -->
                <div class="form-control">
                    <label for="password" class="invisible">Password</label>
                    <span class="input input--icon">
                        <input type="password" id="password" name="password" placeholder="Password">
                        <i class="icon icon--invert" aria-hidden="true">
                            <svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
                                     width="512px" height="512px" viewBox="0 0 512 512" enable-background="new 0 0 512 512" xml:space="preserve">
                                <path d="M195.334,223.333h-50v-62.666C145.334,99.645,194.979,50,256,50c61.022,0,110.667,49.645,110.667,110.667
                                    v62.666h-50v-62.666C316.667,127.215,289.452,100,256,100c-33.451,0-60.666,27.215-60.666,60.667V223.333z M404,253.333V462H108
                                    V253.333H404z M283,341c0-14.912-12.088-27-27-27s-27,12.088-27,27c0,7.811,3.317,14.844,8.619,19.773
                                    c4.385,4.075,6.881,9.8,6.881,15.785V399.5h23v-22.941c0-5.989,2.494-11.708,6.881-15.785C279.683,355.844,283,348.811,283,341z"/>
                            </svg>
                        </i>
                    </span>
                </div>
                <!-- textarea -->
                <div class="form-control">
                    <label for="textarea">Textarea</label>
                    <span class="input">
                        <textarea id="textarea" name="textarea" rows="3"></textarea>
                    </span>
                </div>
                <!-- select -->
                <div class="form-control">
                    <label for="select" class="invisible">Select</label>
                    <span class="input">
                        <select id="select" name="select">
                            <option>Item 1</option>
                            <option>Item 2</option>
                            <option>Item 3</option>
                            <option>Item 4</option>
                            <option>Item 5</option>
                        </select>
                    </span>
                </div>
                <!-- select multiple -->
                <div class="form-control">
                    <label for="select-multiple" class="invisible">Select</label>
                    <span class="input">
                        <select id="select-multiple" multiple name="select">
                            <option>Item 1</option>
                            <option>Item 2</option>
                            <option>Item 3</option>
                            <option>Item 4</option>
                            <option>Item 5</option>
                        </select>
                    </span>
                </div>
                <!-- input type="file" -->
                <div class="form-control">
                    <label for="file">File</label>
                    <span class="input">
                        <input id="file" type="file" name="file">
                    </span>
                </div>
                <!-- input type="checkbox" -->
                <fieldset>
                    <legend>Checkbox</legend>
                    <div class="form-control">
                        <span class="input input--checkbox">
                            <input type="checkbox" id="remember-1" name="remember">
                        </span>
                        <label for="remember-1">Checkbox 1</label>
                    </div>
                    <div class="form-control">
                        <span class="input input--checkbox">
                            <input type="checkbox" id="remember-2" name="remember">
                        </span>
                        <label for="remember-2">Checkbox 2</label>
                    </div>
                </fieldset>
                <!-- input type="radio" -->
                <fieldset>
                    <legend>Sex</legend>
                    <div class="form-control form-control--inline">
                        <span class="input input--radio">
                            <input type="radio" id="male" name="sex" value="male">
                        </span>
                        <label for="male">Male</label>
                    </div>
                    <div class="form-control form-control--inline">
                        <span class="input input--radio">
                            <input type="radio" id="female" name="sex" value="female">
                        </span>
                        <label for="female">Female</label>
                    </div>
                </fieldset>
                <!-- single button -->
                <div class="btn-group">
                    <button class="btn btn--primary">Submit</button>
                </div>
            </fieldset>
        </form>
    </div>
</div>

<div class="penguin-example">
    <div class="form">
        <form>
            <fieldset>
                <legend>Sign in</legend>
                <div class="form-control">
                    <div class="row row--inline row--collapse">
                        <div class="col-a-12 col-d-2">
                            <label for="email-horizontal">Email</label>
                        </div>
                        <div class="col-a-12 col-d-10">
                            <span class="input">
                                <input type="email" id="email-horizontal" class="warn">
                            </span>
                        </div>
                    </div>
                </div>
                <div class="form-control">
                    <div class="row row--inline row--collapse">
                        <div class="col-a-12 col-d-2">
                            <label for="password-horizontal">Contraseña</label>
                        </div>
                        <div class="col-a-12 col-d-10">
                            <span class="input">
                                <input type="password" id="password-horizontal">
                            </span>
                        </div>
                    </div>
                </div>
                <div class="row row--collapse">
                    <div class="col-md-offset-2 col-lg-offset-2 col-lg-10">
                        <div class="form-control">
                            <div class="input input--checkbox">
                                <input type="checkbox" id="remember-horizontal" name="remember">
                            </div>
                            <label for="remember-horizontal">Remember me</label>
                        </div>
                        <div class="btn-group">
                            <input type="submit" class="btn btn--primary" value="Login">
                        </div>
                    </div>
                </div>
            </fieldset>
        </form>
    </div>
</div>

<div class="penguin-example">
    <div class="form">
        <form id="form-2col">
            <div class="grid grid--2col">
                <div class="grid__item">
                    <fieldset>
                        <legend>Account data</legend>
                        <div class="form-control">
                            <label for="name-2col">Username</label>
                            <span class="input">
                                <input id="name-2col" type="text" name="user">
                            </span>
                        </div>
                        <div class="form-control">
                            <label for="email-2col">Email</label>
                            <span class="input">
                                <input type="email" id="email-2col" name="email">
                            </span>
                        </div>
                        <div class="form-control">
                            <label for="password-2col">Password</label>
                            <span class="input">
                                <input type="password" id="password-2col" name="password">
                            </span>
                        </div>
                    </fieldset>
                </div>
                <div class="grid__item">
                    <fieldset>
                        <legend>User data</legend>
                        <div class="form-control">
                            <label for="user-name-2col">Full name</label>
                            <span class="input">
                                <input id="user-name-2col" type="text" name="user-name">
                            </span>
                        </div>
                        <div class="form-control">
                            <label for="address-2col">Address</label>
                            <span class="input">
                                <input id="address-2col" type="text" name="address">
                            </span>
                        </div>
                        <fieldset>
                            <legend>Sex</legend>
                            <div class="form-control form-control--inline">
                                <span class="input input--radio">
                                    <input type="radio" id="male-2col" name="sex" value="male">
                                </span>
                                <label for="male-2col">Male</label>
                            </div>
                            <div class="form-control form-control--inline">
                                <span class="input input--radio">
                                    <input type="radio" id="female-2col" name="sex" value="female">
                                </span>
                                <label for="female-2col">Female</label>
                            </div>
                        </fieldset>
                    </fieldset>
                </div>
            </div>
            <div class="btn-group text-right">
                <input type="reset" class="btn btn--secondary" value="Reset">
                <input type="submit" class="btn btn--primary" value="Submit">
            </div>
        </form>
    </div>
</div>

<div class="penguin-example">
    <div class="form">
        <form>
            <fieldset>
                <legend>Legend</legend>
                <div class="row row--collapse">
                    <div class="col-a-3">
                        <div class="form-control">
                            <label for="name-4col">Username</label>
                            <span class="input">
                                <input id="name-4col" type="text" name="user">
                            </span>
                        </div>
                    </div>
                    <div class="col-a-3">
                        <div class="form-control">
                            <label for="email-4col">Email</label>
                            <span class="input">
                                <input type="email" id="email-4col" name="email-4col">
                            </span>
                        </div>
                    </div>
                    <div class="col-a-3">
                        <div class="form-control">
                            <label for="password-4col">Password</label>
                            <span class="input">
                                <input type="password" id="password-4col" name="password">
                            </span>
                        </div>
                    </div>
                    <div class="col-a-3">
                        <div class="form-control">
                            <label for="user-name-4col">Full name</label>
                            <span class="input">
                                <input id="user-name-4col" type="text" name="user-name-4col">
                            </span>
                        </div>
                    </div>
                    <div class="col-a-3">
                        <div class="form-control">
                            <label for="address-4col">Address</label>
                            <span class="input">
                                <input id="address-4col" type="text" name="address-4col">
                            </span>
                        </div>
                    </div>
                    <div class="col-a-3">
                        <fieldset class="form-control--inline">
                            <legend>Sex</legend>
                            <div class="form-control form-control--inline">
                                <span class="input input--radio">
                                    <input type="radio" id="male-4col" name="sex" value="male">
                                </span>
                                <label for="male-4col">Male</label>
                            </div>
                            <div class="form-control form-control--inline">
                                <span class="input input--radio">
                                    <input type="radio" id="female-4col" name="sex" value="female">
                                </span>
                                <label for="female-4col">Female</label>
                            </div>
                        </fieldset>
                    </div>
                </div>
                <div class="row row--collapse">
                    <div class="col-a-12">
                        <div class="btn-group"><br /><input type="submit" class="btn btn--primary" value="Submit"></div>
                    </div>
                </div>
            </fieldset>
        </form>
    </div>
</div>

<div class="penguin-example">
	<div class="demo demo--target"></div>
	<button class="btn btn--primary" data-rel="modal" data-target=".demo--target" data-modal="{title: 'Modal', content: 'Content', buttons: {btn: [{text: 'Accept', className: 'btn btn--primary'}]}}">Target modal</button>
</div>

<div class="penguin-example">
	<nav class="nav nav--inline" role="navigation">
	    <h1 class="invisible">Navigation</h1>
	    <ul class="nav__menu">
	        <li class="nav__menu__item nav__menu__item--selected"><a href="#" class="nav__menu__link">Item 1</a></li>
	        <li class="nav__menu__item"><a href="#" class="nav__menu__link">Item 2</a></li>
	        <li class="nav__menu__item nav__menu__item--lead"><a href="#" class="nav__menu__link">Item 3</a></li>
	        <li class="nav__menu__item"><a href="#" class="nav__menu__link">Item 4</a></li>
	    </ul>
	</nav>
</div>

<div class="penguin-example">
    <nav class="nav nav--inline" role="navigation">
        <h1 class="invisible">Navigation</h1>
        <ul class="nav__menu">
            <li class="nav__menu__item dropdown">
                <a href="#menu11" class="nav__menu__link" data-rel="dropdown">Item 1</a>
                <ul id="menu11" class="nav__submenu" role="menu" data-dropdown="">
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 1</a></li>
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 2</a></li>
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 3</a></li>
                </ul>
            </li>
            <li class="nav__menu__item dropdown">
                <a href="#menu12" class="nav__menu__link" data-rel="dropdown">Item 2</a>
                <ul id="menu12" class="nav__submenu" role="menu" data-dropdown="">
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 1</a></li>
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 2</a></li>
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 3</a></li>
                </ul>
            </li>
            <li class="nav__menu__item dropdown">
                <a href="#menu13" class="nav__menu__link" data-rel="dropdown">Item 3</a>
                <ul id="menu13" class="nav__submenu" role="menu" data-dropdown="">
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 1</a></li>
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 2</a></li>
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 3</a></li>
                </ul>
            </li>
            <li class="nav__menu__item dropdown">
                <a href="#menu14" class="nav__menu__link" data-rel="dropdown">Item 4</a>
                <ul id="menu14" class="nav__submenu" role="menu" data-dropdown="">
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 1</a></li>
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 2</a></li>
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 3</a></li>
                </ul>
            </li>
        </ul>
    </nav>
</div>

<div class="penguin-example">
    <nav class="nav nav--bar" role="navigation">
        <h1 class="invisible">Navigation</h1>
        <ul class="nav__menu">
            <li class="nav__menu__item nav__menu__item--selected"><a href="#" class="nav__menu__link">Item 1</a></li>
            <li class="nav__menu__item"><a href="#" class="nav__menu__link">Item 2</a></li>
            <li class="nav__menu__item nav__menu__item--lead"><a href="#" class="nav__menu__link">Item 3</a></li>
            <li class="nav__menu__item"><a href="#" class="nav__menu__link">Item 4</a></li>
        </ul>
    </nav>
</div>

<div class="penguin-example">
    <nav class="nav nav--fluid" role="navigation">
        <h1 class="invisible">Navigation</h1>
        <ul class="nav__menu">
            <li class="nav__menu__item nav__menu__item--selected"><a href="#" class="nav__menu__link">Item 1</a></li>
            <li class="nav__menu__item"><a href="#" class="nav__menu__link">Item 2</a></li>
            <li class="nav__menu__item nav__menu__item--lead"><a href="#" class="nav__menu__link">Item 3</a></li>
            <li class="nav__menu__item"><a href="#" class="nav__menu__link">Item 4</a></li>
        </ul>
    </nav>
</div>

<div class="penguin-example">
    <nav class="nav nav--bar" role="navigation">
        <h1 class="invisible">Navigation</h1>
        <ul class="nav__menu">
            <li class="nav__menu__item dropdown">
                <a href="#menu_dropdown1" class="nav__menu__link" data-rel="dropdown">Item 1</a>
                <ul id="menu_dropdown1" class="nav__submenu" role="menu" data-dropdown="">
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 1</a></li>
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 2</a></li>
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 3</a></li>
                </ul>
            </li>
            <li class="nav__menu__item dropdown">
                <a href="#menu_dropdown2" class="nav__menu__link" data-rel="dropdown">Item 2</a>
                <ul id="menu_dropdown2" class="nav__submenu" role="menu" data-dropdown="">
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 1</a></li>
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 2</a></li>
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 3</a></li>
                </ul>
            </li>
            <li class="nav__menu__item dropdown">
                <a href="#menu_dropdown3" class="nav__menu__link" data-rel="dropdown">Item 3</a>
                <ul id="menu_dropdown3" class="nav__submenu" role="menu" data-dropdown="">
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 1</a></li>
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 2</a></li>
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 3</a></li>
                </ul>
            </li>
            <li class="nav__menu__item dropdown">
                <a href="#menu_dropdown4" class="nav__menu__link" data-rel="dropdown">Item 4</a>
                <ul id="menu_dropdown4" class="nav__submenu" role="menu" data-dropdown="">
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 1</a></li>
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 2</a></li>
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 3</a></li>
                </ul>
            </li>
        </ul>
    </nav>
</div>

<div class="penguin-example">
    <nav class="nav nav--stacked" role="navigation">
        <h1 class="invisible">Navigation</h1>
        <ul class="nav__menu">
            <li class="nav__menu__item nav__menu__item--selected"><a href="#" class="nav__menu__link">Item 1</a></li>
            <li class="nav__menu__item"><a href="#" class="nav__menu__link">Item 2</a></li>
            <li class="nav__menu__item nav__menu__item--lead"><a href="#" class="nav__menu__link">Item 3</a></li>
            <li class="nav__menu__item"><a href="#" class="nav__menu__link">Item 4</a></li>
        </ul>
    </nav>
</div>

<div class="penguin-example">
    <nav class="nav nav--stacked" role="navigation">
        <h1 class="invisible">Navigation</h1>
        <ul class="nav__menu">
            <li class="nav__menu__item dropdown dropdown--stacked">
                <a href="#menu41" class="nav__menu__link" data-rel="dropdown">Item 1</a>
                <ul id="menu41" class="nav__submenu" role="menu" data-dropdown="">
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 1</a></li>
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 2</a></li>
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 3</a></li>
                </ul>
            </li>
            <li class="nav__menu__item dropdown dropdown--stacked">
                <a href="#menu42" class="nav__menu__link" data-rel="dropdown">Item 2</a>
                <ul id="menu42" class="nav__submenu" role="menu" data-dropdown="">
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 1</a></li>
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 2</a></li>
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 3</a></li>
                </ul>
            </li>
            <li class="nav__menu__item dropdown dropdown--stacked">
                <a href="#menu43" class="nav__menu__link" data-rel="dropdown">Item 3</a>
                <ul id="menu43" class="nav__submenu" role="menu" data-dropdown="">
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 1</a></li>
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 2</a></li>
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 3</a></li>
                </ul>
            </li>
            <li class="nav__menu__item dropdown dropdown--stacked">
                <a href="#menu44" class="nav__menu__link" data-rel="dropdown">Item 4</a>
                <ul id="menu44" class="nav__submenu" role="menu" data-dropdown="">
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 1</a></li>
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 2</a></li>
                    <li class="nav__submenu__item"><a href="#" class="nav__submenu__link">Item 3</a></li>
                </ul>
            </li>
        </ul>
    </nav>
</div>

<div class="penguin-example">
    <nav class="nav nav--bar" role="navigation">
        <h1 class="hidden">Navigation</h1>
        <ul class="nav__menu">
            <li class="nav__menu__item nav__menu__item--selected">
                <a href="#" class="nav__menu__link">
                    <span class="icon-text">
                        <i class="icon" aria-hidden="true">
                            <svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
                                 width="512px" height="512px" viewBox="0 0 512 512" enable-background="new 0 0 512 512" xml:space="preserve">
                                <path d="M160.879,312.387V205.609h117.064v-39.627l93.178,93.016l-93.178,93.018v-39.629H160.879z M90,256
                                    c0,91.756,74.258,166,166,166c91.755,0,166-74.258,166-166c0-91.755-74.258-166-166-166C164.245,90,90,164.259,90,256z M462,256
                                    c0,113.771-92.229,206-206,206S50,369.771,50,256c0-113.771,92.229-206,206-206S462,142.229,462,256z"/>
                            </svg>
                        </i>
                        Item 1
                    </span>
                </a>
            </li>
            <li class="nav__menu__item">
                <a href="#" class="nav__menu__link">
                    <span class="icon-text">
                        <i class="icon" aria-hidden="true">
                            <svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
                             width="512px" height="512px" viewBox="0 0 512 512" enable-background="new 0 0 512 512" xml:space="preserve">
                                <path d="M160.879,312.387V205.609h117.064v-39.627l93.178,93.016l-93.178,93.018v-39.629H160.879z M90,256
                                c0,91.756,74.258,166,166,166c91.755,0,166-74.258,166-166c0-91.755-74.258-166-166-166C164.245,90,90,164.259,90,256z M462,256
                                c0,113.771-92.229,206-206,206S50,369.771,50,256c0-113.771,92.229-206,206-206S462,142.229,462,256z"/>
                            </svg>
                        </i>
                        Item 2
                    </span>
                </a>
            </li>
            <li class="nav__menu__item nav__menu__item--lead">
                <a href="#" class="nav__menu__link">
                    <span class="icon-text">
                        <i class="icon" aria-hidden="true">
                            <svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
                                width="512px" height="512px" viewBox="0 0 512 512" enable-background="new 0 0 512 512" xml:space="preserve">
                                <path d="M160.879,312.387V205.609h117.064v-39.627l93.178,93.016l-93.178,93.018v-39.629H160.879z M90,256
                                c0,91.756,74.258,166,166,166c91.755,0,166-74.258,166-166c0-91.755-74.258-166-166-166C164.245,90,90,164.259,90,256z M462,256
                                c0,113.771-92.229,206-206,206S50,369.771,50,256c0-113.771,92.229-206,206-206S462,142.229,462,256z"/>
                            </svg>
                        </i>
                        Item 3
                    </span>
                </a>
            </li>
            <li class="nav__menu__item">
                <a href="#" class="nav__menu__link">
                    <span class="icon-text">
                        <i class="icon" aria-hidden="true">
                            <svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
                             width="512px" height="512px" viewBox="0 0 512 512" enable-background="new 0 0 512 512" xml:space="preserve">
                                <path d="M160.879,312.387V205.609h117.064v-39.627l93.178,93.016l-93.178,93.018v-39.629H160.879z M90,256
                                c0,91.756,74.258,166,166,166c91.755,0,166-74.258,166-166c0-91.755-74.258-166-166-166C164.245,90,90,164.259,90,256z M462,256
                                c0,113.771-92.229,206-206,206S50,369.771,50,256c0-113.771,92.229-206,206-206S462,142.229,462,256z"/>
                            </svg>
                        </i>
                        Item 4
                    </span>
                </a>
            </li>
        </ul>
    </nav>
</div>

<div class="penguin-example">
    <ul class="paginator paginator--inline">
        <li class="paginator__item"><a href="#" class="paginator__link">First</a></li>
        <li class="paginator__item"><a href="#" class="paginator__link">Previous</a></li>
        <li class="paginator__item paginator__item--selected"><a href="#" class="paginator__link">1</a></li>
        <li class="paginator__item"><a href="#" class="paginator__link">2</a></li>
        <li class="paginator__item"><a href="#" class="paginator__link">3</a></li>
        <li class="paginator__item"><a href="#" class="paginator__link">4</a></li>
        <li class="paginator__item"><a href="#" class="paginator__link">Next</a></li>
        <li class="paginator__item"><a href="#" class="paginator__link">Last</a></li>
    </ul>
</div>

<div class="penguin-example">
	<ul class="paginator paginator--bar">
	    <li class="paginator__item"><a href="#" class="paginator__link">First</a></li>
	    <li class="paginator__item"><a href="#" class="paginator__link">Previous</a></li>
	    <li class="paginator__item paginator__item--selected"><a href="#" class="paginator__link">1</a></li>
	    <li class="paginator__item"><a href="#" class="paginator__link">2</a></li>
	    <li class="paginator__item"><a href="#" class="paginator__link">3</a></li>
	    <li class="paginator__item"><a href="#" class="paginator__link">4</a></li>
	    <li class="paginator__item"><a href="#" class="paginator__link">Next</a></li>
	    <li class="paginator__item"><a href="#" class="paginator__link">Last</a></li>
	</ul>
</div>

<div class="penguin-example">
	<section class="panel panel--dropdown">
	    <div class="dropdown dropdown--stacked dropdown--selected" data-selected="">
	        <h1 class="panel__title">Panel title</h1>
	        <a data-rel="dropdown" href="#content">
	        	<i class="icon" aria-hidden="true">
	        		<svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
						 viewBox="0 0 512 512" enable-background="new 0 0 512 512" xml:space="preserve">
						<polygon points="206.422,462 134.559,390.477 268.395,256 134.559,121.521 206.422,50 411.441,256 "/>
					</svg>
	        	</i>
	       	</a>
	        <div id="content" class="panel__content" data-dropdown="">Panel content</div>
	    </div>
	</section>
</div>

<div class="penguin-example penguin-example--margin">
    <div class="grid grid--2col">
        <div class="grid__item">
            <div class="demo demo--a demo--spinner">
            </div>
            <ul class="btn-group">
                <li><button class="btn btn--primary btn--spinner-demo--a">Launch here</button></li>
                <li><button class="btn btn--primary btn--spinner-clear-a">Clear</button></li>
            </ul>
        </div>
        <div class="grid__item">
            <div class="demo demo--b demo--spinner">
            </div>
            <ul class="btn-group">
                <li><button class="btn btn--primary btn--spinner-demo--b">Launch here</button></li>
                <li><button class="btn btn--primary btn--spinner-clear-b">Clear</button></li>
            </ul>
        </div>
    </div>
</div>

<div class="penguin-example">
    <div class="tab tab--inline" data-tab="">
        <ul class="tab__block" role="tablist">
            <li class="tab__block__item tab__block__item--selected" role="tab">
                <a href="#tab1-inline" class="tab__block__link">Tab 1</a>
            </li>
            <li class="tab__block__item" role="tab">
                <a href="#tab2-inline" class="tab__block__link">Tab 2</a>
            </li>
            <li class="tab__block__item" role="tab">
                <a href="#tab3-inline" class="tab__block__link">Tab 3</a>
            </li>
            <li class="tab__block__item" role="tab">
                <a href="#tab4-inline" class="tab__block__link">Tab 4</a>
            </li>
        </ul>
        <div class="tab__content">
            <div class="tab__content__item tab__content__item--selected" id="tab1-inline" role="tabpanel">Tab 1 content</div>
            <div class="tab__content__item" id="tab2-inline" role="tabpanel">Tab 2 content</div>
            <div class="tab__content__item" id="tab3-inline" role="tabpanel">Tab 3 content</div>
            <div class="tab__content__item" id="tab4-inline" role="tabpanel">Tab 4 content</div>
        </div>
    </div>
</div>

<div class="penguin-example">
    <div class="tab tab--bar" data-tab="">
        <ul class="tab__block" role="tablist">
            <li class="tab__block__item tab__block__item--selected" role="tab"><a href="#tab1-bar" class="tab__block__link">Tab 1</a></li>
            <li class="tab__block__item" role="tab"><a href="#tab2-bar" class="tab__block__link">Tab 2</a></li>
            <li class="tab__block__item" role="tab"><a href="#tab3-bar" class="tab__block__link">Tab 3</a></li>
            <li class="tab__block__item" role="tab"><a href="#tab4-bar" class="tab__block__link">Tab 4</a></li>
        </ul>
        <div class="tab__content">
            <div class="tab__content__item tab__content__item--selected" id="tab1-bar">Tab 1 content</div>
            <div class="tab__content__item" id="tab2-bar">Tab 2 content</div>
            <div class="tab__content__item" id="tab3-bar">Tab 3 content</div>
            <div class="tab__content__item" id="tab4-bar">Tab 4 content</div>
        </div>
    </div>
</div>

<div class="penguin-example">
    <div class="tab tab--stacked" data-tab="">
        <ul class="tab__block" role="tablist">
            <li class="tab__block__item"><a href="#tab1-stacked" class="tab__block__link" role="tab">Tab 1</a></li>
            <li class="tab__block__item"><a href="#tab2-stacked" class="tab__block__link" role="tab">Tab 2</a></li>
            <li class="tab__block__item"><a href="#tab3-stacked" class="tab__block__link" role="tab">Tab 3</a></li>
            <li class="tab__block__item tab__block__item--selected"><a href="#tab4-stacked" class="tab__block__link">Tab 4</a></li>
        </ul>
        <div class="tab__content">
            <div class="tab__content__item" id="tab1-stacked" role="tabpanel">Tab 1 content</div>
            <div class="tab__content__item" id="tab2-stacked" role="tabpanel">Tab 2 content</div>
            <div class="tab__content__item" id="tab3-stacked" role="tabpanel">Tab 3 content</div>
            <div class="tab__content__item tab__content__item--selected" id="tab4-stacked" role="tabpanel">Tab 4 content</div>
        </div>
    </div>
</div>

<div class="penguin-example">
    <table class="table">
        <thead>
            <tr>
                <th>#</th>
                <th>Table heading</th>
                <th>Table heading</th>
                <th>Table heading</th>
                <th>Table heading</th>
            </tr>
        </thead>
        <tfoot>
            <tr>
                <td colspan="5">table footer</td>
            </tr>
        </tfoot>
        <tbody>
            <tr>
                <td><a href="">1</a></td>
                <td>Table cell</td>
                <td>Table cell</td>
                <td>Table cell</td>
                <td>Table cell</td>
            </tr>
            <tr>
                <td><a href="">2</a></td>
                <td>Table cell</td>
                <td>Table cell</td>
                <td>Table cell</td>
                <td>Table cell</td>
            </tr>
            <tr><td><a href="">3</a></td>
                <td>Table cell</td>
                <td>Table cell</td>
                <td>Table cell</td>
                <td>Table cell</td>
            </tr>
            <tr><td><a href="">4</a></td>
                <td>Table cell</td>
                <td>Table cell</td>
                <td>Table cell</td>
                <td>Table cell</td>
            </tr>
            <tr><td><a href="">5</a></td>
                <td>Table cell</td>
                <td>Table cell</td>
                <td>Table cell</td>
                <td>Table cell</td>
            </tr>
        </tbody>
    </table>
</div>

<div class="penguin-example text">
    <h1>This is a h1 text</h1>
    <h2>This is a h2 text</h2>
    <h3>This is a h3 text</h3>
    <h4>This is a h4 text</h4>
    <h5>This is a h5 text</h5>
    <h6>This is a h6 text</h6>
</div>

<div class="penguin-example text">
    <p>Default paragraph</p>
    <p class="text-large">This is a large text</p>
    <p>Default paragraph with a <strong>heavier font-weight</strong></p>
    <p>Default paragraph with a <em>snippet of text with italics</em></p>
    <p class="text-small">This is a small text</p>
    <p class="text"><small>This is a small label</small></p>
</div>

<div class="penguin-example text">
    <ul>
        <li>A</li>
        <li>B</li>
        <li>
            <strong>C</strong>
            <ul>
                <li>C1</li>
                <li>C2</li>
            </ul>
        </li>
        <li>D</li>
    </ul>
    <ol>
        <li>one</li>
        <li>two</li>
        <li>three</li>
        <li>four</li>
    </ol>
</div>



<script src="/bower_components/jquery/dist/jquery.min.js"></script>
<script>

    $(function () {
        var themeDefault = 'penguin-doc'

        $('#select-theme option[value='+ themeDefault +']').attr('selected', 'selected');

        $(document).on('change', '#select-theme', function () {
            changeTheme($('#select-theme :selected').val());
        });
    });

    function changeTheme(theme) {
        var theme = theme.toLowerCase()
            styleSheet = $('[title="penguin-theme"]')
            linkGitHub = $('#link-github')
            linkCss = $('#link-css')
            pathGitHub = 'https://github.com/bq/penguin-themes/tree/master/themes/'+ theme
            pathCss = '/bower_components/penguin-themes/themes/'+ theme +'/dist/css/' + theme.toLowerCase() +'.css';

            linkCss.attr('href', pathCss);
            styleSheet.attr('href', pathCss);
            linkGitHub.attr('href', pathGitHub);
    }
</script>