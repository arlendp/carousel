# carousel
a carousel with vertical and horizontal sliding based on bootstrap

## Usage

### horizontal sliding

```html
<div class="carousel slide" id="carousel-demo" data-ride="carousel">
    <ul class="carousel-indicators">
        <li data-target="#carousel-demo" data-slide-to="0" class="active"></li>
        <li data-target="#carousel-demo" data-slide-to="1"></li>
        <li data-target="#carousel-demo" data-slide-to="2"></li>
    </ul>
    <div class="carousel-inner">
        <div class="item active">
            <p>here is the item1</p>
        </div>
        <div class="item">
            <p>here is the item2</p>
        </div>
        <div class="item">
            <p>here is the item3</p>
        </div>
    </div>
    <a class="left carousel-control" href="#carousel-demo" data-slide="prev">
        <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#carousel-demo" data-slide="next">
        <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
    </a>
</div>
```

### vertical sliding

```html
<div class="carousel slide vertical " id="carousel-demo" data-ride="carousel">
    <ul class="carousel-indicators vertical">
        <li data-target="#carousel-demo" data-slide-to="0" class="active"></li>
        <li data-target="#carousel-demo" data-slide-to="1"></li>
        <li data-target="#carousel-demo" data-slide-to="2"></li>
    </ul>
    <div class="carousel-inner">
        <div class="item active">
            <p>here is the item1</p>
        </div>
        <div class="item">
            <p>here is the item2</p>
        </div>
        <div class="item">
            <p>here is the item3</p>
        </div>
    </div>
    <a class="up carousel-control vertical" href="#carousel-demo" data-slide="before">
        <span class="glyphicon glyphicon-chevron-up" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
    </a>
    <a class="down carousel-control vertical" href="#carousel-demo" data-slide="after">
        <span class="glyphicon glyphicon-chevron-down" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
    </a>
</div>
```