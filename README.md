
An example of responsive bootstrap carousel with videos instead of images.

Check out [Bootstrap Video Carousel Documentation](https://mdbootstrap.com/docs/standard/extended/video-carousel/) for detailed instructions & even more examples.

## Basic example

![Bootstrap 5 Video Carousel](https://mdbootstrap.com/img/Marketing/github/video-carousel/basic.png)

```html
<!-- Carousel wrapper -->
<div
  id="carouselVideoExample"
  class="carousel slide carousel-fade"
  data-mdb-ride="carousel"
>
  <!-- Indicators -->
  <div class="carousel-indicators">
    <button
      type="button"
      data-mdb-target="#carouselVideoExample"
      data-mdb-slide-to="0"
      class="active"
      aria-current="true"
      aria-label="Slide 1"
    ></button>
    <button
      type="button"
      data-mdb-target="#carouselVideoExample"
      data-mdb-slide-to="1"
      aria-label="Slide 2"
    ></button>
    <button
      type="button"
      data-mdb-target="#carouselVideoExample"
      data-mdb-slide-to="2"
      aria-label="Slide 3"
    ></button>
  </div>

  <!-- Inner -->
  <div class="carousel-inner">
    <!-- Single item -->
    <div class="carousel-item active">
      <video class="img-fluid" autoplay loop muted>
        <source src="https://mdbcdn.b-cdn.net/img/video/Tropical.mp4" type="video/mp4" />
      </video>
      <div class="carousel-caption d-none d-md-block">
        <h5>First slide label</h5>
        <p>
          Nulla vitae elit libero, a pharetra augue mollis interdum.
        </p>
      </div>
    </div>

    <!-- Single item -->
    <div class="carousel-item">
      <video class="img-fluid" autoplay loop muted>
        <source src="https://mdbcdn.b-cdn.net/img/video/forest.mp4" type="video/mp4" />
      </video>
      <div class="carousel-caption d-none d-md-block">
        <h5>Second slide label</h5>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit.
        </p>
      </div>
    </div>

    <!-- Single item -->
    <div class="carousel-item">
      <video class="img-fluid" autoplay loop muted>
        <source
          src="https://mdbcdn.b-cdn.net/img/video/Agua-natural.mp4"
          type="video/mp4"
        />
      </video>
      <div class="carousel-caption d-none d-md-block">
        <h5>Third slide label</h5>
        <p>
          Praesent commodo cursus magna, vel scelerisque nisl consectetur.
        </p>
      </div>
    </div>
  </div>
  <!-- Inner -->

  <!-- Controls -->
  <button
    class="carousel-control-prev"
    type="button"
    data-mdb-target="#carouselVideoExample"
    data-mdb-slide="prev"
  >
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button
    class="carousel-control-next"
    type="button"
    data-mdb-target="#carouselVideoExample"
    data-mdb-slide="next"
  >
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
<!-- Carousel wrapper -->
```

## How to use?

1. Download MDB 5 - free UI KIT

2. Choose your favourite customized component and click on the image

3. Copy & paste the code into your MDB project

[▶️ Subscribe to YouTube channel for web development tutorials & resources](https://www.youtube.com/MDBootstrap?sub_confirmation=1)

## More examples

[Bootstrap Full page video carousel:
![Bootstrap 5 Video Carousel](https://mdbootstrap.com/img/Marketing/github/video-carousel/section-2.png)](https://mdbootstrap.com/docs/standard/extended/video-carousel/#section-full-page-video-carousel)

___

## More extended Bootstrap documentation

<ul>
<li><a href="https://mdbootstrap.com/docs/standard/extended/bootstrap-address-form/">Bootstrap Address Form</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/avatar/">Bootstrap Avatar</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/back-to-top/">Bootstrap Back To Top Button</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/carousel-with-thumbnails/">Bootstrap Carousel Slider with Thumbnails</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/chat/">Bootstrap Chat</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/code/">Bootstrap Code Blocks</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/comments/">Bootstrap Comments</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/bootstrap-comparison-table/">Bootstrap Comparison Table</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/credit-card/">Bootstrap Credit Card Form</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/drawer/">Bootstrap Drawer</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/dropdown-multilevel/">Bootstrap Nested Dropdown</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/faq/">Bootstrap FAQ component / section</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/gallery/">Bootstrap Gallery</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/hamburger-menu/">Bootstrap Hamburger Menu</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/bootstrap-invoice/">Bootstrap Invoice</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/jumbotron/">Bootstrap Jumbotron</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/login/">Bootstrap Login Form</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/maps/">Bootstrap Maps</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/media-object/">Bootstrap Media Object</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/mega-menu/">Bootstrap Mega Menu</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/multiselect/">Bootstrap Multiselect</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/news-feed/">Bootstrap News Feed</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/offcanvas/">Bootstrap Offcanvas</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/order-details/">Bootstrap Order Details</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/page-transitions/">Bootstrap Page Transitions</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/payment-forms/">Bootstrap Payment Forms</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/product-cards/">Bootstrap Product Cards</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/profiles/">Bootstrap Profiles</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/quotes/">Bootstrap Quotes</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/registration/">Bootstrap Registration Form</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/search-expanding/">Bootstrap Expanding Search Bar</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/shopping-carts/">Bootstrap Shopping Carts</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/side-navbar/">Bootstrap Side Navbar</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/sidebar/">Bootstrap Sidebar</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/social-media/">Bootstrap Social Media Icons & Buttons</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/square-buttons/">Bootstrap Square Buttons</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/bootstrap-survey-form/">Bootstrap Survey Form</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/testimonial-slider/">Bootstrap Testimonial Slider</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/testimonials/">Bootstrap Testimonials</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/textarea/">Bootstrap Textarea</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/timeline/">Bootstrap Timeline</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/to-do-list/">Bootstrap To Do List</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/video-carousel/">Bootstrap Video Carousel / Gallery</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/weather/">Bootstrap Weather</a></li>  
</ul>

