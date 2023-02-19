# Learn_Bootstrap5

### Size

```
<div class="container" style="margin-top: 20px">
    <!-- Width -->
    <div class="bg-danger w-25 p-3">Width 25%</div>
    <div class="bg-danger w-50 p-3">Width 50%</div>
    <div class="bg-danger w-75">Width 75%</div>
    <div class="bg-danger w-100">Width 100%</div>
    <div class="bg-danger w-auto">Width Auto</div>

    <!-- Height -->
    <div style="height: 300px">
    <div class="bg-primary h-25 my-1">Height 25%</div>
    <div class="bg-primary h-50 my-1">Height 50%</div>
    <div class="bg-primary h-75 my-1">Height 75%</div>
    <div class="bg-primary h-100">Height 100%</div>
    <div class="bg-primary h-auto">Height Auto</div>
    </div>
</div>
```

### Border

```
<div class="container" style="margin-top: 20px">
    <!-- กำหนดเส้นขอบ -->
    <div class="border my-2">Border</div>
    <div class="border-top my-2">Border Top</div>
    <div class="border-bottom my-2">Border Bottom</div>
    <div class="border-start my-2">Border Start</div>
    <div class="border-end my-2">Border End</div>

    <!-- กำหนดสีเส้นขอบ -->
    <div class="border border-primary">Border Primary</div>
    <div class="border border-secondary">Border Secondary</div>
    <div class="border border-success">Border Success</div>
    <div class="border border-danger">Border Danger</div>
    <div class="border border-warning">Border Warning</div>
    <div class="border border-info">Border Info</div>
    <div class="border border-light">Border Light</div>
    <div class="border border-dark">Border Dark</div>
    <div class="border border-white">Border White</div>

    <!-- กำหนดความหนาเส้นขอบ -->
    <div class="border border-1 border-dark">Border 1</div>
    <div class="border border-2 border-dark">Border 2</div>
    <div class="border border-3 border-dark">Border 3</div>
    <div class="border border-4 border-dark">Border 4</div>
    <div class="border border-5 border-dark">Border 5</div>

    <!-- กำหนดความโค้งเส้นขอบ -->
    <div class="border my-3 border-dark rounded">Rounded</div>
    <div class="border my-3 border-dark rounded-top">Rounded-top</div>
    <div class="border my-3 border-dark rounded-bottom">Rounded-bottom</div>
    <div class="border my-3 border-dark rounded-start">Rounded-start</div>
    <div class="border my-3 border-dark rounded-end">Rounded-end</div>

    <!-- กำหนดขนาดความโค้งเส้นขอบ -->
    <div class="border my-3 border-dark rounded-0">Rounded 0</div>
    <div class="border my-3 border-dark rounded-1">Rounded 1</div>
    <div class="border my-3 border-dark rounded-2">Rounded 2</div>
    <div class="border my-3 border-dark rounded-3">Rounded 3</div>
</div>
```

### Button

```
<link rel="stylesheet" href="css/bootstrap.min.css" />
<script src="js/bootstrap.min.js"></script>
<script src="js/bootstrap.bundle.js"></script>
```

```
<div class="container" style="margin-top: 20px">
    <!-- สีของปุ่ม -->
    <button class="btn btn-primary">Primary</button>
    <button class="btn btn-secondary">Secondary</button>
    <button class="btn btn-success">Success</button>
    <button class="btn btn-danger">Danger</button>
    <button class="btn btn-warning">Warning</button>
    <button class="btn btn-info">Info</button>
    <button class="btn btn-light">Light</button>
    <button class="btn btn-dark">Dark</button>

    <!-- ปุ่มแบบ Link -->
    <button type="button" class="btn btn-link">Link</button>

    <br /><br />
    <!-- Button Tag -->
    <a href="#" class="btn btn-primary">Link</a>
    <button type="button" class="btn btn-success">Button</button>
    <input type="button" class="btn btn-danger" value="Button" />
    <input type="submit" class="btn btn-warning" value="Submit" />
    <input type="reset" class="btn btn-secondary" value="Reset" />
    <br /><br />

    <!-- Outline Button -->
    <button class="btn btn-outline-primary">Outline Primary</button>
    <button class="btn btn-outline-secondary">Outline Secondary</button>
    <button class="btn btn-outline-success">Outline Success</button>
    <button class="btn btn-outline-danger">Outline Danger</button>
    <button class="btn btn-outline-warning">Outline Warning</button>
    <button class="btn btn-outline-info">Outline Info</button>
    <button class="btn btn-outline-light">Outline Light</button>
    <button class="btn btn-outline-dark">Outline Dark</button>
    <br /><br />

    <!-- ขนาดของปุ่ม -->
    <button class="btn btn-success btn-lg">Large Button</button>
    <button class="btn btn-success btn-sm">Small Button</button>
    <br /><br />

    <!-- Block Button -->
    <div class="d-grid gap-2">
    <button class="btn btn-primary">Block Button</button>
    <button class="btn btn-success">Block Button</button>
    </div>

    <br /><br />
    <!-- Button Group -->
    <div class="btn-group">
    <button class="btn btn-success">Button 1</button>
    <button class="btn btn-success">Button 2</button>
    <button class="btn btn-success">Button 3</button>
    </div>
    <br /><br />
    <!-- Button Vertical Group -->
    <div class="btn-group-vertical">
    <button class="btn btn-primary">Button 1</button>
    <button class="btn btn-primary">Button 2</button>
    <button class="btn btn-primary">Button 3</button>
    </div>
    <br /><br />
    <!-- Dropdown Menu -->
    <div class="btn-group">
    <button class="btn btn-primary">Home</button>
    <button
        class="btn btn-primary dropdown-toggle"
        data-bs-toggle="dropdown"
    >
        Menu
    </button>
    <div class="dropdown-menu">
        <a href="#" class="dropdown-item">Item 1</a>
        <a href="#" class="dropdown-item">Item 2</a>
        <a href="#" class="dropdown-item">Item 3</a>
    </div>
    </div>
    <br /><br />
    <!-- Button style -->
    <button class="btn btn-danger">Regular</button>
    <button class="btn btn-danger active">Active</button>
    <button class="btn btn-danger disabled">Disabled</button>
</div>
```

### Navbar

```
<link rel="stylesheet" href="css/bootstrap.min.css" />
<script src="js/bootstrap.js"></script>
```

```
<body style="height: 1500px">
<nav class="navbar navbar-expand-sm">
    <div class="container-fluid">
    <a href="#" class="navbar-brand">KOPE</a>
    <ul class="navbar-nav">
        <li class="nav-item"><a href="#" class="nav-link">Home</a></li>
        <li class="nav-item"><a href="#" class="nav-link">About</a></li>
    </ul>
    </div>
</nav>
<br />

<!-- navbaar color -->
<nav class="navbar navbar-expand-sm navbar-dark bg-success">
    <div class="container-fluid">
    <a href="#" class="navbar-brand">KOPE</a>
    <ul class="navbar-nav">
        <li class="nav-item"><a href="#" class="nav-link">Home</a></li>
        <li class="nav-item"><a href="#" class="nav-link">About</a></li>
    </ul>
    </div>
</nav>
<br />

<!-- Navbar Toggle -->
<nav class="navbar navbar-expand-sm navbar-dark bg-dark">
    <div class="container-fluid">
    <a href="#" class="navbar-brand">KOPE</a>
    <button
        class="navbar-toggler"
        data-bs-toggle="collapse"
        data-bs-target="#navbarToggle"
    >
        <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarToggle">
        <ul class="navbar-nav">
        <li class="nav-item">
            <a href="#" class="nav-link">Home</a>
        </li>
        <li class="nav-item">
            <a href="#" class="nav-link">About</a>
        </li>
        <li class="nav-item">
            <a href="#" class="nav-link">Contact</a>
        </li>
        <li class="nav-item">
            <a href="#" class="nav-link">Product</a>
        </li>
        </ul>
    </div>
    </div>
</nav>
<br />

<!-- navbaar form -->
<nav class="navbar navbar-expand-sm navbar-dark bg-danger">
    <div class="container-fluid">
    <a href="#" class="navbar-brand">KOPE</a>
    <ul class="navbar-nav">
        <li class="nav-item"><a href="#" class="nav-link">Home</a></li>
        <li class="nav-item"><a href="#" class="nav-link">About</a></li>
    </ul>
    <form class="d-flex">
        <input
        type="text"
        class="form-control me-2"
        placeholder="ค้นหาข้อมูล"
        />
        <input type="submit" value="ค้นหา" class="btn btn-outline-dark" />
    </form>
    </div>
</nav>
<br />

<!-- Fixed-Top & Fixed-Bottom -->
<nav class="navbar navbar-expand-sm navbar-dark bg-primary fixed-bottom">
    <div class="container-fluid">
    <a href="#" class="navbar-brand">KOPE</a>
    <button
        class="navbar-toggler"
        data-bs-toggle="collapse"
        data-bs-target="#navbarToggle"
    >
        <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarToggle">
        <ul class="navbar-nav">
        <li class="nav-item">
            <a href="#" class="nav-link">Home</a>
        </li>
        <li class="nav-item">
            <a href="#" class="nav-link">About</a>
        </li>
        <li class="nav-item">
            <a href="#" class="nav-link">Contact</a>
        </li>
        <li class="nav-item">
            <a href="#" class="nav-link">Product</a>
        </li>
        </ul>
    </div>
    </div>
</nav>
<br />

<!-- Sticky-top -->
<nav class="navbar navbar-expand-sm navbar-dark bg-warning sticky-top">
    <div class="container-fluid">
    <a href="#" class="navbar-brand">KOPE</a>
    <button
        class="navbar-toggler"
        data-bs-toggle="collapse"
        data-bs-target="#navbarToggle"
    >
        <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarToggle">
        <ul class="navbar-nav">
        <li class="nav-item">
            <a href="#" class="nav-link">Home</a>
        </li>
        <li class="nav-item">
            <a href="#" class="nav-link">About</a>
        </li>
        <li class="nav-item">
            <a href="#" class="nav-link">Contact</a>
        </li>
        <li class="nav-item">
            <a href="#" class="nav-link">Product</a>
        </li>
        </ul>
    </div>
    </div>
</nav>
<br />

<!-- Dropdown-menu -->
<nav class="navbar navbar-expand-sm navbar-dark bg-secondary">
    <div class="container-fluid">
    <a href="#" class="navbar-brand">KOPE</a>
    <button
        class="navbar-toggler"
        data-bs-toggle="collapse"
        data-bs-target="#navbarToggle"
    >
        <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarToggle">
        <ul class="navbar-nav">
        <li class="nav-item">
            <a href="#" class="nav-link">Home</a>
        </li>
        <li class="nav-item">
            <a href="#" class="nav-link">About</a>
        </li>
        <li class="nav-item">
            <a href="#" class="nav-link">Contact</a>
        </li>
        <li class="nav-item dropdown">
            <a
            href="#"
            class="nav-link dropdown-toggle"
            data-bs-toggle="dropdown"
            >Dropdown Product</a
            >
            <ul class="dropdown-menu">
            <li><a href="#" class="dropdown-item">เฟอร์นิเจอร์</a></li>
            <li>
                <a href="#" class="dropdown-item">อุปกรณ์คอมพิวเตอร์</a>
            </li>
            </ul>
        </li>
        </ul>
    </div>
    </div>
</nav>
<br />
</body>
```

### List

```
<div class="container" style="margin-top: 20px">
    <!-- List แบบ UL -->
    <ul class="list-group">
    <li class="list-group-item">Item 1</li>
    <li class="list-group-item">Item 2</li>
    </ul>
    <br />
    <!-- List แบบ Link -->
    <ul class="list-group">
    <a class="list-group-item">Item 1</a>
    <a class="list-group-item">Item 2</a>
    </ul>
    <br />
    <!-- List แบบ Active -->
    <ul class="list-group">
    <a class="list-group-item active">Item 1</a>
    <a class="list-group-item">Item 2</a>
    </ul>
    <br />
    <!-- กำหนดสีให้ List -->
    <ul class="list-group">
    <li class="list-group-item">List Regular</li>
    <li class="list-group-item list-group-item-primary">List Primary</li>
    <li class="list-group-item list-group-item-secondary">
        List Secondary
    </li>
    <li class="list-group-item list-group-item-succes">List Success</li>
    <li class="list-group-item list-group-item-danger">List Danger</li>
    <li class="list-group-item list-group-item-warning">List Warning</li>
    <li class="list-group-item list-group-item-info">List Info</li>
    <li class="list-group-item list-group-item-light">List Light</li>
    <li class="list-group-item list-group-item-dark">List Dark</li>
    </ul>
    <br />
    <!-- List แบบไม่มีขอบ -->
    <ul class="list-group list-group-flush">
    <a class="list-group-item">Item 1</a>
    <a class="list-group-item">Item 2</a>
    <a class="list-group-item">Item 3</a>
    <a class="list-group-item">Item 4</a>
    </ul>
</div>
```

### BreadCrumb-Badge

```
<div class="container" style="margin-top: 20px">
    <!-- สร้าง BreadCrumb -->
    <ol class="breadcrumb">
    <li class="breadcrumb-item">สินค้า</li>
    <li class="breadcrumb-item"></li>เฟอร์นิเจอร์</li>
    <li class="breadcrumb-item active">โซฟา</li>
    </ol>
    <!-- แบบ Link -->
    <ol class="breadcrumb">
    <li class="breadcrumb-item"><a href="#">สินค้า</a></li>
    <li class="breadcrumb-item"><a href="#">เฟอร์นิเจอร์</a></li>
    <li class="breadcrumb-item active"><a href="#">โซฟา</a></li>
    </ol>
    <!-- Badge -->
    <ul class="list-group">
    <li class="list-group-item d-flex justify-content-between">สินค้าทั้งหมด<span class="badge bg-success">45</span></li>
    <li class="list-group-item d-flex justify-content-between">เฟอร์นิเจอร์<span class="badge bg-primary">15</span></li>
    <li class="list-group-item d-flex justify-content-between">เครื่องใช้ไฟฟ้า<span class="badge bg-danger">15</span></li>
    <li class="list-group-item d-flex justify-content-between">เครื่องสำอางค์<span class="badge bg-warning">15</span></li>
    </ul>
</div>
```

### Alert

```
<div class="container" style="margin-top: 20px">
    <!-- การสร้าง Alert -->
    <div class="alert">
    <strong>Simple Alert</strong>
    </div>

    <!-- กำหนดสีของ Alert -->
    <div class="alert alert-primary">
    <strong>Primary</strong>
    </div>
    <div class="alert alert-secondary">
    <strong>Secondary</strong>
    </div>
    <div class="alert alert-success">
    <strong>Success</strong>
    </div>
    <div class="alert alert-danger">
    <strong>Danger</strong>
    </div>
    <div class="alert alert-warning">
    <strong>Warning</strong>
    </div>
    <div class="alert alert-info">
    <strong>Info</strong>
    </div>
    <div class="alert alert-light">
    <strong>Light</strong>
    </div>
    <div class="alert alert-dark">
    <strong>Dark</strong>
    </div>

    <!-- Link Alert -->
    <div class="alert alert-success">
    <strong>Link Alert</strong>
    <a href="#" class="alert-link">Link</a>
    </div>

    <!-- การปิด Alert -->
    <div class="alert alert-success alert-dismissible">
    <button class="btn-close" data-bs-dismiss="alert"></button>
    <h2 class="alert-heading">Hello World</h2>
    <hr />
    <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Praesentium
        reprehenderit distinctio fuga magni maxime assumenda inventore,
        laudantium perferendis esse tempora.
    </p>
    </div>
</div>
```

### Progressbar

```
<div class="container" style="margin-top: 20px">
    <!-- การสร้าง Progressbar -->
    <div class="progress">
    <div class="progress-bar" style="width: 50%"></div>
    </div>
    <br />
    <!-- สร้าง Progressbar พร้อม Text -->
    <div class="progress">
    <div class="progress-bar" style="width: 50%">50%</div>
    </div>
    <br />
    <!-- กำหนดสีให้ Progressbar -->
    <div class="progress">
    <div class="progress-bar bg-success" style="width: 99%">Success</div>
    </div>
    <br />
    <div class="progress">
    <div class="progress-bar bg-warning" style="width: 99%">Warning</div>
    </div>
    <br />
    <div class="progress">
    <div class="progress-bar bg-primary" style="width: 99%">Primary</div>
    </div>
    <br />
    <!-- กำหนดความสูง -->
    <div class="progress" style="height: 50px">
    <div class="progress-bar bg-danger" style="width: 75%">75%</div>
    </div>
    <br />
    <!-- Striped Progressbar -->
    <div class="progress" style="height: 50px">
    <div
        class="progress-bar bg-success progress-bar-striped"
        style="width: 90%"
    >
        90%
    </div>
    </div>
    <br />
    <!-- กำหนด Striped Animation -->
    <div class="progress" style="height: 50px">
    <div
        class="progress-bar bg-primary progress-bar-striped progress-bar-animated"
        style="width: 90%"
    >
        90%
    </div>
    </div>
    <br />
    <!-- Multiple Progressbar -->
    <div class="progress" style="height: 50px">
    <div class="progress-bar bg-warning" style="width: 25%"></div>
    <div class="progress-bar bg-success" style="width: 25%"></div>
    <div class="progress-bar bg-primary" style="width: 50%"></div>
    </div>
</div>
```
