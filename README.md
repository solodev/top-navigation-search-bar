# top-navigation-search-bar
Incorporating search bars can be difficult and often lead you making sacrifices to shove new input elements into your design. With a search bar that replaces your top navigation, however, you can direct user behavior while maintaining the consistency of your design.

## Tutorial		  
For detailed instruction's, view Solodev's [How to Create a Search Bar That Overlays Your Top Navigation](https://www.solodev.com/blog/how-to-create-a-search-bar-that-overlays-your-top-navigation.stml) article.
 
## Demo
  		  
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/2yput4vh/9/).

## HTML

The tutorial contains the following basic HTML markup.

```
<header class="top">
      <div class="container d-flex">
          <div class="col-md-10 col-xs-6 d-flex bd-highlight">
            <div class="col-xl-3 col-lg-2 col-sm-4 col-5 mr-auto p-2 bd-highlight">
              <a href="#">
                <img alt="Logo" class="img-fluid py-3" src="https://raw.githubusercontent.com/solodev/top-navigation-search-bar/master/images/logo.png" aria-role="logo">
              </a>
            </div>
            <!-- .logo -->
            <nav class="navbar-nav p-2 bd-highlight">
              <ul class="topmenu nolist">
                <li><a href="#">ABOUT</a>
                </li>
                <li><a href="#">LOCATIONS</a>
                </li>
                <li><a href="#">PRODUCTS</a>
                </li>
                <li><a href="#">SHOP</a>
                </li>
                <li><a href="#">CONTACT</a>
                </li>
                <li class="search">
                  <a href="#">
                     <i class="fas fa-search fa-lg pointer text-secondary-light"></i>
                  </a>
                </li>
              </ul>
            </nav>
            <div class="search-bar">
              <form class="d-flex w-100 justify-content-center" method="GET">
                <input class="align-self-center search-input form-control" type="text" name="s" placeholder="What are you searching for?">
                <button type="submit" class="align-self-center"><i class="fas fa-search"></i>
                </button>
              </form>
            </div>
          </div>
          <!-- .header-content -->
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

