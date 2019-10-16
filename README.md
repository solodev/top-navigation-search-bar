# top-navigation-search-bar
Incorporating search bars can be difficult and often lead you making sacrifices to shove new input elements into your design. With a search bar that replaces your top navigation, however, you can direct user behavior while maintaining the consistency of your design.

## Tutorial		  
For detailed instruction's, view Solodev's []() article.
 
## Demo
  		  
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/2yput4vh/3/).

## HTML

The tutorial contains the following basic HTML markup.

```
<div class="overlay" id="overlay">
      <div class="overlay-container">
        <div class="box-wrap ps-container ps-theme-default z-index-max nav-sidenav bg-eerie-black" data-ps-id="c7505214-71ed-31a3-86fc-ffd7385b7d66">
          <div class="d-flex align-items-center justify-content-between border-alpha2-white p-4"></div>
          <form class="search-form">
            <div class="input-group" data-children-count="1"> <span class="input-group-btn"><button class="submit" type="submit" value="" data-children-count="0"><span class="input-group-btn"><i class="fas fa-search"></i></span>
              </button>
              </span>
              <input aria-label="Side Nav Search Input" class="inp" name="search" type="search" placeholder="What are you searching for?">
            </div> 
          </form>
          <div class="ps-scrollbar-x-rail" style="left: 0px; bottom: 0px;">
            <div class="ps-scrollbar-x" tabindex="0" style="left: 0px; width: 0px;"></div>
          </div>
          <div class="ps-scrollbar-y-rail" style="top: 0px; right: 0px;">
            <div class="ps-scrollbar-y" tabindex="0" style="top: 0px; height: 0px;"></div>
          </div>
        </div>  
      </div>
      <!-- .overlay-container -->
      <div class="close-container visible-xs">
        <i class="fas fa-times fa-lg text-white" aria-label="Menu Toggle"></i>
      </div>
      <!-- .close-container -->
    </div>
    <header class="top">
      <div class="container">
        <div class="row">
          <div class="col-md-10 col-xs-6 d-flex justify-content-end">
            <div class="col-xl-3 col-lg-2 col-sm-4 col-5">
              <a href="/">
                <img alt="LunarXP Logo" class="img-fluid py-3" src="https://raw.githubusercontent.com/solodev/top-navigation-search-bar/master/images/logo.png" aria-role="logo">
              </a>
            </div>
            <!-- .logo -->
            <nav>
              <ul class="topmenu nolist">
                <li><a href="#">About</a>
                </li>
                <li><a href="#">Locations</a>
                </li>
                <li><a href="#">Products</a>
                </li>
                <li><a href="#">Shop</a>
                </li>
                <li><a href="#">Contact</a>
                </li>
                <li class="search">
                  <a href="#">
                    <img src="https://raw.githubusercontent.com/solodev/top-navigation-search-bar/master/images/search.png" alt="" class="img-responsive">
                  </a>
                </li>
              </ul>
            </nav>
            <button class="menu-hamburger"> <span class="icon-bar"></span>
              <span class="icon-bar"></span>
              <span class="icon-bar"></span>
            </button>
            <div class="search-bar">
              <form class="d-flex w-100 justify-content-center" method="GET">
                <input class="search-input form-control" type="text" name="s" placeholder="What are you searching for?">
                <button type="submit"><i class="fas fa-search"></i>
                </button>
              </form>
            </div>
          </div>
          <!-- .header-content -->
        </div>
        <!-- .row -->
      </div>
      <!-- .container -->
    </header>
```

## CSS
All required CSS is contained with style.css


## External Resources

This tutorial includes the following third party resources.

```
<<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css" rel="stylesheet">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/1000hz-bootstrap-validator/0.11.9/validator.min.js"></script>

```

