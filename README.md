# ecommerce-carousel
Jquery carousel slider for view product, Touch work only on phones.

1. #### Make your html themplate.
This is bootstrap example.
```
<div class="product-carousel col-xs-12 col-sm-4 col-md-5">
    <div class="primary col-xs-12 col-sm-12 col-md-9">
        <img src="images/1.jpg" data-slide="0" draggable="false" class="center-block img-responsive">
    </div>
    <div class="thumbnails col-xs-12 col-sm-12 col-md-3">
        <div class="col-xs-3 col-sm-3 col-md-12">
            <img src="images/thumbnail/1.jpg" data-slide="0" data-original-picture="images/1.jpg" class="pointer item img-responsive"">
        </div>
        <div class="col-xs-3 col-sm-3 col-md-12">
            <img src="images/thumbnail/2.jpg" data-slide="1" data-original-picture="images/2.jpg" class="pointer item img-responsive"">
        </div>
        <div class="col-xs-3 col-sm-3 col-md-12">
            <img src="images/thumbnail/3.jpg" data-slide="2" data-original-picture="images/3.jpg" class="pointer item img-responsive"">
        </div>
    </div>
</div>
```

2. #### import jquery.ecommerc.slider.js file after jquery into your project.
 
```
  <script src="http://code.jquery.com/jquery-latest.min.js"></script>
  <script src="jquery.ecommerc.slider.js"></script>
```

2. #### Configuration settings.
```
  $(document).ready(function () {
        $('.product-carousel').products_carousel({interval: 5000,slide:1});
  });
```
 *interval and slide are Optional.*
