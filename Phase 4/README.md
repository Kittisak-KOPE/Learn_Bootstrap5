# Learn_Bootstrap5

### Grid Vertical Alignment

```
<div class="container my-2 bg-info">
    <div class="row" style="height: 500px">
    <div class="col align-self-center">
        <div class="card">
        <h1>Hello World</h1>
        <a href="#" class="btn btn-success">Register</a>
        </div>
    </div>
    <div class="col align-self-end">
        <div class="card">
        <h1>Hello World</h1>
        <a href="#" class="btn btn-success">Register</a>
        </div>
    </div>
    <div class="col align-self-start">
        <div class="card">
        <h1>Hello World</h1>
        <a href="#" class="btn btn-success">Register</a>
        </div>
    </div>
    </div>
</div>
```

### Grid Horizontal Alignment

```
<style>
    .col-item {
    border: 1px solid #333;
    width: 100px;
    height: 100px;
    background: orange;
    }
</style>
```

```
<div class="container bg-info">
    <div class="row justify-content-start">
    <div class="col-4 col-item">Area 1</div>
    <div class="col-4 col-item">Area 2</div>
    <div class="col-4 col-item">Area 3</div>
    </div>
    <br />

    <div class="row justify-content-center">
    <div class="col-4 col-item">Area 1</div>
    <div class="col-4 col-item">Area 2</div>
    <div class="col-4 col-item">Area 3</div>
    </div>
    <br />

    <div class="row justify-content-end">
    <div class="col-4 col-item">Area 1</div>
    <div class="col-4 col-item">Area 2</div>
    <div class="col-4 col-item">Area 3</div>
    </div>
    <br />

    <div class="row justify-content-around">
    <div class="col-4 col-item">Area 1</div>
    <div class="col-4 col-item">Area 2</div>
    <div class="col-4 col-item">Area 3</div>
    </div>
    <br />

    <div class="row justify-content-between">
    <div class="col-4 col-item">Area 1</div>
    <div class="col-4 col-item">Area 2</div>
    <div class="col-4 col-item">Area 3</div>
    </div>
    <br />
</div>
```

### Flexbox Class

```
<div class="container my-2">
    <!-- creating flexbox -->
    <div class="bg-info d-flex">
    <div class="p-4 bg-warning">Item 1</div>
    <div class="p-4 bg-warning">Item 2</div>
    <div class="p-4 bg-warning">Item 3</div>
    </div>
    <br />

    <!-- define direct -->
    <div class="bg-info d-flex flex-row">
    <div class="p-4 bg-warning">Item 1</div>
    <div class="p-4 bg-warning">Item 2</div>
    <div class="p-4 bg-warning">Item 3</div>
    </div>
    <br />
    <!-- row-reverse -->
    <div class="bg-info d-flex flex-row-reverse">
    <div class="p-4 bg-warning">Item 1</div>
    <div class="p-4 bg-warning">Item 2</div>
    <div class="p-4 bg-warning">Item 3</div>
    </div>
    <br />

    <!-- column -->
    <div class="bg-info d-flex flex-column">
    <div class="p-4 bg-warning">Item 1</div>
    <div class="p-4 bg-warning">Item 2</div>
    <div class="p-4 bg-warning">Item 3</div>
    </div>
    <br />

    <!-- column-reverse -->
    <div class="bg-info d-flex flex-column-reverse">
    <div class="p-4 bg-warning">Item 1</div>
    <div class="p-4 bg-warning">Item 2</div>
    <div class="p-4 bg-warning">Item 3</div>
    </div>
    <br />

    <!-- Horizontal Alignment || justity-content-start, center, end, around, between -->
    <div class="bg-info d-flex justify-content-center">
    <div class="p-4 bg-warning">Item 1</div>
    <div class="p-4 bg-warning">Item 2</div>
    <div class="p-4 bg-warning">Item 3</div>
    </div>
    <br />

    <!-- Vertical Alignment || align-items-start, center, end, stretch, baseline -->
    <div class="d-flex bg-info align-items-baseline" style="height: 200px">
    <div class="p-4 bg-success text-white">Item 1</div>
    <div class="p-4 bg-success text-white">Item 2</div>
    <div class="p-4 bg-success text-white">Item 3</div>
    </div>
    <br />

    <!-- align self item -->
    <div class="bg-info d-flex" style="height: 200px">
    <div class="p-4 bg-success align-self-start">Start</div>
    <div class="p-4 bg-success align-self-center">center</div>
    <div class="p-4 bg-success align-self-end">end</div>
    <div class="p-4 bg-success align-self-stretch">stretch</div>
    <div class="p-4 bg-success align-self-baseline">baseline</div>
    </div>
    <br />
</div>
```

### Carousel Slider

```
<div class="container">
    <div class="row">
        <div class="col-lg-8 m-auto">
            <!-- การสร้าง Carousel -->
            <div class="carousel slide" id="slider1" data-bs-ride="carousel">
                    <ol class="carousel-indicators">
                        <button  data-bs-target="#slider1" data-bs-slide-to="0"></button>
                        <button  data-bs-target="#slider1" data-bs-slide-to="1"></button>
                        <button  class="active" data-bs-target="#slider1" data-bs-slide-to="2"></button>
                        <button  data-bs-target="#slider1" data-bs-slide-to="3"></button>
                    </ol>
                    <div class="carousel-inner">
                        <div class="carousel-item">
                            <img src="https://cdn.pixabay.com/photo/2021/02/08/15/02/mountains-5995081__340.jpg" class="d-block w-100">
                            <div class="carousel-caption d-none d-md-block">
                                <h3>ภูเขา</h3>
                                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Sequi, nobis.</p>
                            </div>
                        </div>
                        <div class="carousel-item">
                            <img src="https://cdn.pixabay.com/photo/2020/06/15/01/06/sunset-5299957__340.jpg" class="d-block w-100">
                            <div class="carousel-caption d-none d-md-block">
                                <h3>ทะเล</h3>
                                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Sequi, nobis.</p>
                            </div>
                        </div>
                        <div class="carousel-item active">
                            <img src="https://cdn.pixabay.com/photo/2021/01/18/17/46/sunset-5928907__340.jpg" class="d-block w-100">
                            <div class="carousel-caption d-none d-md-block">
                                <h3>พระอาทิตย์ตกดิน</h3>
                                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Sequi, nobis.</p>
                            </div>
                        </div>
                        <div class="carousel-item">
                            <img src="https://cdn.pixabay.com/photo/2021/01/21/14/10/egret-5937499__340.jpg" class="d-block w-100">
                            <div class="carousel-caption d-none d-md-block">
                                <h3>หมอก</h3>
                                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Sequi, nobis.</p>
                            </div>
                        </div>
                    </div>
                    <!-- ควบคุมการ Slide ผ่านปุ่ม -->
                    <button class="carousel-control-prev" data-bs-slide="prev" data-bs-target="#slider1">
                        <span class="carousel-control-prev-icon"></span>
                    </button>
                    <button class="carousel-control-next" data-bs-slide="next" data-bs-target="#slider1">
                        <span class="carousel-control-next-icon"></span>
                    </button>
            </div>
        </div>
    </div>
</div>
```

### Collapse & Accordion

```

```
