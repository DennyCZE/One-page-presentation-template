# One-page-presentation-template
Template made for one page presentation sites using mostly Bootstrap 3.

## Instalation
Just copy or download repository. It is basing HTML template which can be integrated anywhere.

## Features

### Including HTML snippets
```html
<div include-html="snippet.html"></div>
```

### Centered text carousel
```html
<div id="text-carousel" class="carousel slide" data-ride="carousel">
    <!-- Wrapper for slides -->
    <div class="row">
        <div class="col-xs-offset-3 col-xs-6">
            <div class="carousel-inner">
                <div class="item active">
                    <div class="carousel-content">
                        <div>
                            <p>Sapiente, ducimus, voluptas, mollitia voluptatibus nemo explicabo sit blanditiis laborum dolore illum fuga veniam quae expedita libero accusamus quas harum ex numquam necessitatibus provident deleniti tenetur iusto officiis recusandae corporis culpa quaerat?</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- Controls -->
    <a class="left carousel-control" href="#text-carousel" data-slide="prev">
        <span class="glyphicon glyphicon-chevron-left"></span>
    </a>
    <a class="right carousel-control" href="#text-carousel" data-slide="next">
        <span class="glyphicon glyphicon-chevron-right"></span>
    </a>
</div>
```

### Custom gallery by Nabeel Kondotty
```html
<div class="container gal-container">
    <div class="col-md-12 col-sm-12 co-xs-12 gal-item">
        <div class="box">
            <a href="#" data-toggle="modal" data-target="#1">
                <img src="assets/images/placeholder.png">
            </a>
            <div class="modal fade" id="1" tabindex="-1" role="dialog">
                <div class="modal-dialog" role="document">
                    <div class="modal-content">
                        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
                        <div class="modal-body">
                            <img src="assets/images/placeholder.png">
                        </div>
                        <div class="col-md-12 description">
                            <h4>Title of the image</h4>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
```
