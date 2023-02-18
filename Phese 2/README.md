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
    <!-- Content -->
    <div class="container-fluid">
    <!-- Brand -->
    <a href="#" class="navbar-brand">KongRuksiam</a>
    <!-- Menu -->
    <ul class="navbar-nav">
        <li class="nav-item">
        <a href="#" class="nav-link">Home</a>
        </li>
        <li class="nav-item">
        <a href="#" class="nav-link">About</a>
        </li>
    </ul>
    </div>
</nav>
<br />
<!-- Navbar Color -->
<nav class="navbar navbar-expand-sm navbar-dark bg-success">
    <!-- Content -->
    <div class="container-fluid">
    <!-- Brand -->
    <a href="#" class="navbar-brand">KongRuksiam</a>
    <!-- Menu -->
    <ul class="navbar-nav">
        <li class="nav-item">
        <a href="#" class="nav-link">Home</a>
        </li>
        <li class="nav-item">
        <a href="#" class="nav-link">About</a>
        </li>
    </ul>
    </div>
</nav>

<br />
<!-- Navbar Toggle -->
<nav class="navbar navbar-expand-sm navbar-dark bg-dark">
    <!-- Content -->
    <div class="container-fluid">
    <!-- Brand -->
    <a href="#" class="navbar-brand">KongRuksiam</a>
    <button
        class="navbar-toggler"
        data-bs-toggle="collapse"
        data-bs-target="#navbarToggle"
    >
        <span class="navbar-toggler-icon"></span>
    </button>
    <!-- Menu -->
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
<!-- Navbar Form -->
<nav class="navbar navbar-expand-sm navbar-dark bg-danger">
    <!-- Content -->
    <div class="container-fluid">
    <!-- Brand -->
    <a href="#" class="navbar-brand">KongRuksiam</a>
    <!-- Menu -->
    <ul class="navbar-nav">
        <li class="nav-item">
        <a href="#" class="nav-link">Home</a>
        </li>
        <li class="nav-item">
        <a href="#" class="nav-link">About</a>
        </li>
        <form class="d-flex">
        <input
            type="text"
            class="form-control me-2"
            placeholder="ป้อนข้อมูล"
        />
        <input type="submit" value="ค้นหา" class="btn btn-outline-dark" />
        </form>
    </ul>
    </div>
</nav>

<br />
<!-- Fixed-Top -->
<nav class="navbar navbar-expand-sm navbar-dark bg-primary fixed-bottom">
    <!-- Content -->
    <div class="container-fluid">
    <!-- Brand -->
    <a href="#" class="navbar-brand">KongRuksiam</a>
    <button
        class="navbar-toggler"
        data-bs-toggle="collapse"
        data-bs-target="#navbarToggle"
    >
        <span class="navbar-toggler-icon"></span>
    </button>
    <!-- Menu -->
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
<!-- Fixed-Bottom -->
<br />
<!-- Sticky-Top -->
<nav class="navbar navbar-expand-sm navbar-dark bg-warning sticky-top">
    <!-- Content -->
    <div class="container-fluid">
    <!-- Brand -->
    <a href="#" class="navbar-brand">KongRuksiam</a>
    <button
        class="navbar-toggler"
        data-bs-toggle="collapse"
        data-bs-target="#navbarToggle"
    >
        <span class="navbar-toggler-icon"></span>
    </button>
    <!-- Menu -->
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
<!-- Dropdown Menu -->
<nav class="navbar navbar-expand-sm navbar-dark bg-secondary">
    <!-- Content -->
    <div class="container-fluid">
    <!-- Brand -->
    <a href="#" class="navbar-brand">KongRuksiam</a>
    <button
        class="navbar-toggler"
        data-bs-toggle="collapse"
        data-bs-target="#navbarToggle"
    >
        <span class="navbar-toggler-icon"></span>
    </button>
    <!-- Menu -->
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
            >สินค้า</a
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
    <a href="#" class="list-group-item">Item 1</a>
    <a href="#" class="list-group-item">Item 2</a>
    </ul>
    <br />
    <!-- List แบบ Active -->
    <ul class="list-group">
    <a href="#" class="list-group-item active">Item 1</a>
    <a href="#" class="list-group-item">Item 2</a>
    </ul>
    <br />
    <!-- กำหนดสีให้ List -->
    <ul class="list-group">
    <li class="list-group-item">List Regular</li>
    <li class="list-group-item list-group-item-primary">List Primary</li>
    <li class="list-group-item list-group-item-secondary">
        List Secondary
    </li>
    <li class="list-group-item list-group-item-success">List Success</li>
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

```
