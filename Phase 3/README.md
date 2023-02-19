# Learn_Bootstrap5

### Table

```
<div class="container" style="margin-top: 20px">
    <!-- การสร้างหมายเลขหน้า -->
    <nav>
    <ul class="pagination">
        <li class="page-item">
        <a href="#" class="page-link">ก่อนหน้า</a>
        </li>
        <li class="page-item">
        <a href="#" class="page-link">1</a>
        </li>
        <li class="page-item">
        <a href="#" class="page-link">2</a>
        </li>
        <li class="page-item">
        <a href="#" class="page-link">3</a>
        </li>
        <li class="page-item">
        <a href="#" class="page-link">ถัดไป</a>
        </li>
    </ul>
    </nav>

    <!-- Alignment -->
    <nav>
    <ul class="pagination justify-content-start">
        <li class="page-item">
        <a href="#" class="page-link">ก่อนหน้า</a>
        </li>
        <li class="page-item">
        <a href="#" class="page-link">1</a>
        </li>
        <li class="page-item">
        <a href="#" class="page-link">2</a>
        </li>
        <li class="page-item">
        <a href="#" class="page-link">3</a>
        </li>
        <li class="page-item">
        <a href="#" class="page-link">ถัดไป</a>
        </li>
    </ul>
    </nav>
    <nav>
    <ul class="pagination justify-content-center">
        <li class="page-item">
        <a href="#" class="page-link">ก่อนหน้า</a>
        </li>
        <li class="page-item">
        <a href="#" class="page-link">1</a>
        </li>
        <li class="page-item">
        <a href="#" class="page-link">2</a>
        </li>
        <li class="page-item">
        <a href="#" class="page-link">3</a>
        </li>
        <li class="page-item">
        <a href="#" class="page-link">ถัดไป</a>
        </li>
    </ul>
    </nav>
    <nav>
    <ul class="pagination justify-content-end">
        <li class="page-item">
        <a href="#" class="page-link">ก่อนหน้า</a>
        </li>
        <li class="page-item">
        <a href="#" class="page-link">1</a>
        </li>
        <li class="page-item">
        <a href="#" class="page-link">2</a>
        </li>
        <li class="page-item">
        <a href="#" class="page-link">3</a>
        </li>
        <li class="page-item">
        <a href="#" class="page-link">ถัดไป</a>
        </li>
    </ul>
    </nav>

    <!-- Active & Disabled -->
    <nav>
    <ul class="pagination justify-content-start">
        <li class="page-item disabled">
        <a href="#" class="page-link">ก่อนหน้า</a>
        </li>
        <li class="page-item">
        <a href="#" class="page-link">1</a>
        </li>
        <li class="page-item">
        <a href="#" class="page-link">2</a>
        </li>
        <li class="page-item active">
        <a href="#" class="page-link">3</a>
        </li>
        <li class="page-item">
        <a href="#" class="page-link">ถัดไป</a>
        </li>
    </ul>
    </nav>

    <!-- กำหนดขนาด -->
    <nav>
    <ul class="pagination pagination-lg">
        <li class="page-item disabled">
        <a href="#" class="page-link">ก่อนหน้า</a>
        </li>
        <li class="page-item">
        <a href="#" class="page-link">1</a>
        </li>
        <li class="page-item">
        <a href="#" class="page-link">2</a>
        </li>
        <li class="page-item active">
        <a href="#" class="page-link">3</a>
        </li>
        <li class="page-item">
        <a href="#" class="page-link">ถัดไป</a>
        </li>
    </ul>
    </nav>

    <!-- Pagination แบบ Arrow -->
    <nav>
    <ul class="pagination pagination-lg">
        <li class="page-item">
        <a href="#" class="page-link">
            <span>&laquo;</span>
        </a>
        </li>
        <li class="page-item">
        <a href="#" class="page-link">1</a>
        </li>
        <li class="page-item">
        <a href="#" class="page-link">2</a>
        </li>
        <li class="page-item">
        <a href="#" class="page-link">3</a>
        </li>
        <li class="page-item">
        <a href="#" class="page-link">
            <span>&raquo;</span>
        </a>
        </li>
    </ul>
    </nav>
</div>
```

### Form

```
<div class="container" style="margin-top: 20px">
    <form>
    <!-- Text Field -->
    <div class="mb-3">
        <label for="name" class="form-label">ชื่อ</label>
        <input type="text" placeholder="กรุณาป้อนชื่อ" class="form-control" />
    </div>
    <div class="mb-3">
        <label for="email" class="form-label">อีเมล</label>
        <input
        type="email"
        placeholder="กรุณาป้อนอีเมล"
        class="form-control"
        />
    </div>
    <div class="mb-3">
        <label for="password" class="form-label">รหัสผ่าน</label>
        <input
        type="password"
        placeholder="กรุณาป้อนรหัสผ่าน"
        class="form-control"
        />
    </div>
    <!-- Select -->
    <div class="mb-3">
        <label for="job" class="form-label">อาชีพ</label>
        <select name="job" class="form-select">
        <option>Programmer</option>
        <option>Developer</option>
        <option>อาจารย์</option>
        <option>ทนายความ</option>
        </select>
    </div>
    <!-- TextArea -->
    <div class="mb-3">
        <label class="form-label">ที่อยู่</label>
        <textarea class="form-control" cols="30" rows="5"></textarea>
    </div>
    <!-- File -->
    <div class="mb-3">
        <label class="form-label">เอกสาร</label>
        <input type="file" class="form-control" />
    </div>
    <!-- Range -->
    <div class="mb-3">
        <label class="form-label">ประสบการณ์ทำงาน</label>
        <input type="range" min="1" max="5" value="5" class="form-range" />
    </div>
    <input
        type="submit"
        name=""
        id=""
        value="บันทึกข้อมูล"
        class="btn btn-success"
    />
    </form>
    <br />
    <!-- Form Check -->
    <form class="mb-3">
    <div>
        <label class="form-label">ชื่อ</label>
        <input type="text" placeholder="กรุณาป้อนชื่อ" class="form-control" />
    </div>
    <div>
        <label class="form-label">รหัสผ่าน</label>
        <input
        type="password"
        placeholder="กรุณาป้อนรหัสผ่าน"
        class="form-control"
        />
    </div>
    <div class="form-check">
        <label>
        <input
            type="checkbox"
            name=""
            class="form-check-input"
        />ฉันยอมรับเงื่อนไข
        </label>
    </div>
    <button class="btn btn-danger">ส่งข้อมูล</button>
    </form>
    <br />
    <!-- Validation -->
    <div class="mb-3">
    <label for="name" class="form-label">ชื่อ</label>
    <input
        type="text"
        placeholder="กรุณาป้อนชื่อ"
        class="form-control is-valid"
    />
    </div>
    <div class="mb-3">
    <label for="email" class="form-label">อีเมล</label>
    <input
        type="email"
        placeholder="กรุณาป้อนอีเมล"
        class="form-control is-invalid"
    />
    </div>
    <div class="mb-3">
    <label for="password" class="form-label">รหัสผ่าน</label>
    <input
        type="password"
        placeholder="กรุณาป้อนรหัสผ่าน"
        class="form-control is-invalid"
    />
    <div class="invalid-feedback">ป้อนรหัสผ่านไม่ถูกต้อง</div>
    </div>
</div>
```

### Input Group

```
<div class="container" style="margin-top: 20px;">
    <!-- Text Field -->
    <div class="input-group mb-3">
        <div class="input-group-prepend">
            <span class="input-group-text">ชื่อ</span>
        </div>
        <input type="text" placeholder="ป้อนชื่อพร้อมคำนำหน้า" class="form-control">
    </div>
    <div class="input-group mb-3">
        <div class="input-group-prepend">
            <span class="input-group-text">นามสกุล</span>
        </div>
        <input type="text" placeholder="ป้อนนามสกุล" class="form-control">
    </div>
    <div class="input-group mb-3">
        <div class="input-group-prepend">
            <span class="input-group-text">เบอร์โทรศัพท์</span>
        </div>
        <input type="tel" placeholder="06x-xxx-xxx-x" class="form-control">
    </div>
    <!-- Multiple TextField -->
    <div class="input-group mb-3">
        <div class="input-group-prepend">
            <span class="input-group-text">ชื่อและนามสกุล</span>
        </div>
        <input type="text" placeholder="ป้อนชื่อพร้อมคำนำหน้า" class="form-control">
        <input type="text" placeholder="ป้อนนามสกุล" class="form-control">
    </div>
    <!-- Checkbox -->
    <div class="input-group mb-3">
        <div class="input-group-text">
            <input type="checkbox">
            </div>
        <input type="text" class="form-control">
    </div>

    <!-- Radio-->
    <div class="input-group mb-3">
        <div class="input-group-text">
            <input type="radio">
            </div>
        <input type="text" class="form-control">
    </div>
    <!-- Button-->
    <div class="input-group mb-3">
        <input type="text" placeholder="ค้นหาข้อมูล" class="form-control">
        <div class="input-group-prepend">
            <button class="btn btn-success">Search</button>
        </div>
    </div>
</div>
```

### Card

```
<div class="container" style="margin-top: 20px">
    <!-- สร้างการ์ดเบื้องต้น -->
    <div class="card">
    <div class="card-body">
        <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti
        aliquam autem eum dolores amet iure ea sit beatae? Enim dolorum esse
        tempore optio animi tempora ipsam ducimus quia totam. Blanditiis?
        </p>
    </div>
    </div>
    <br />

    <!-- กำหนดรายละเอียดการ์ด -->
    <div class="card">
    <div class="card-body">
        <h4 class="card-title">เที่ยวทะเล</h4>
        <h6 class="card-subtitle mb-2 text-muted">เผยแพร่ 01/01/2021</h6>
        <p class="card-text">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti
        aliquam autem eum dolores amet iure ea sit beatae? Enim dolorum esse
        tempore optio animi tempora ipsam ducimus quia totam. Blanditiis?
        </p>
        <a href="#" class="btn btn-success">อ่านบทความ</a>
    </div>
    </div>
    <br />

    <!-- ใส่ภาพในการ์ด -->
    <div class="card">
    <img
        src="https://cdn.pixabay.com/photo/2018/08/14/13/23/ocean-3605547__340.jpg"
        alt=""
        class="card-img-top"
    />
    <div class="card-body">
        <h4 class="card-title">เที่ยวทะเล</h4>
        <h6 class="card-subtitle mb-2 text-muted">เผยแพร่ 01/01/2021</h6>
        <p class="card-text">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti
        aliquam autem eum dolores amet iure ea sit beatae? Enim dolorum esse
        tempore optio animi tempora ipsam ducimus quia totam. Blanditiis?
        </p>
        <a href="#" class="btn btn-success">อ่านบทความ</a>
    </div>
    </div>
    <br />

    <!-- ใส่ Header & Footerในการ์ด -->
    <div class="card">
    <div class="card-header">หมวดหมู่ท่องเที่ยว</div>
    <img
        src="https://cdn.pixabay.com/photo/2018/08/14/13/23/ocean-3605547__340.jpg"
        alt=""
        class="card-img-top"
    />
    <div class="card-body">
        <h4 class="card-title">เที่ยวทะเล</h4>
        <h6 class="card-subtitle mb-2 text-muted">เผยแพร่ 01/01/2021</h6>
        <p class="card-text">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti
        aliquam autem eum dolores amet iure ea sit beatae? Enim dolorum esse
        tempore optio animi tempora ipsam ducimus quia totam. Blanditiis?
        </p>
        <a href="#" class="btn btn-success">อ่านบทความ</a>
    </div>
    <div class="card-footer">ผู้เขียนบทความ, โก๊ป</div>
    </div>
    <br />

    <!-- Card Nvaigation -->
    <div class="card">
    <div class="card-header">
        <ul class="nav nav-tabs card-header-tabs">
        <li class="nav-item">
            <a href="#" class="nav-link active">ทะเล</a>
        </li>
        <li class="nav-item"><a href="#" class="nav-link">ภูเขา</a></li>
        <li class="nav-item"><a href="#" class="nav-link">น้าตก</a></li>
        </ul>
    </div>
    <div class="card-body">
        <h4 class="card-title">เที่ยวทะเล</h4>
        <h6 class="card-subtitle mb-2 text-muted">เผยแพร่ 01/01/2021</h6>
        <p class="card-text">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti
        aliquam autem eum dolores amet iure ea sit beatae? Enim dolorum esse
        tempore optio animi tempora ipsam ducimus quia totam. Blanditiis?
        </p>
        <a href="#" class="btn btn-success">อ่านบทความ</a>
    </div>
    </div>
    <br />

    <!-- Image Overlay -->
    <div class="card">
    <img
        src="https://cdn.pixabay.com/photo/2014/12/16/22/25/woman-570883__340.jpg"
        alt=""
        class="card-img-top"
    />
    <div class="card-body card-img-overlay">
        <h4 class="card-title text-white">เที่ยวทะเล</h4>
        <h6 class="card-subtitle mb-2 text-muted">เผยแพร่ 01/01/2021</h6>
        <p class="card-text text-white">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti
        aliquam autem eum dolores amet iure ea sit beatae? Enim dolorum esse
        tempore optio animi tempora ipsam ducimus quia totam. Blanditiis?
        </p>
        <a href="#" class="btn btn-success">อ่านบทความ</a>
    </div>
    <div class="card-footer">ผู้เขียนบทความ, โก๊ป</div>
    </div>
    <br />

    <!-- Card Background -->
    <div class="card bg-primary text-white">
    <div class="card-body">
        <h4 class="card-title">เที่ยวทะเล</h4>
        <h6 class="card-subtitle mb-2">เผยแพร่ 01/01/2021</h6>
        <p class="card-text">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti
        aliquam autem eum dolores amet iure ea sit beatae? Enim dolorum esse
        tempore optio animi tempora ipsam ducimus quia totam. Blanditiis?
        </p>
        <a href="#" class="btn btn-danger">อ่านบทความ</a>
    </div>
    </div>
    <br />

    <!-- Card Border -->
    <div class="card border-danger">
    <div class="card-body">
        <h4 class="card-title">เที่ยวทะเล</h4>
        <h6 class="card-subtitle mb-2">เผยแพร่ 01/01/2021</h6>
        <p class="card-text">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti
        aliquam autem eum dolores amet iure ea sit beatae? Enim dolorum esse
        tempore optio animi tempora ipsam ducimus quia totam. Blanditiis?
        </p>
        <a href="#" class="btn btn-danger">อ่านบทความ</a>
    </div>
    </div>
    <br />

    <!-- card group -->
    <div class="card-group">
    <div class="card">
        <img
        src="https://cdn.pixabay.com/photo/2018/08/14/13/23/ocean-3605547__340.jpg"
        alt=""
        class="card-img-top"
        />
        <div class="card-body">
        <h4 class="card-title">เที่ยวทะเล</h4>
        <h6 class="card-subtitle mb-2 text-muted">เผยแพร่ 01/01/2021</h6>
        <p class="card-text">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti
            aliquam autem eum dolores amet iure ea sit beatae? Enim dolorum
            esse tempore optio animi tempora ipsam ducimus quia totam.
            Blanditiis?
        </p>
        <a href="#" class="btn btn-success">อ่านบทความ</a>
        </div>
    </div>
    <div class="card">
        <img
        src="https://cdn.pixabay.com/photo/2018/08/14/13/23/ocean-3605547__340.jpg"
        alt=""
        class="card-img-top"
        />
        <div class="card-body">
        <h4 class="card-title">เที่ยวทะเล</h4>
        <h6 class="card-subtitle mb-2 text-muted">เผยแพร่ 01/01/2021</h6>
        <p class="card-text">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti
            aliquam autem eum dolores amet iure ea sit beatae? Enim dolorum
            esse tempore optio animi tempora ipsam ducimus quia totam.
            Blanditiis?
        </p>
        <a href="#" class="btn btn-success">อ่านบทความ</a>
        </div>
    </div>
    <div class="card">
        <img
        src="https://cdn.pixabay.com/photo/2018/08/14/13/23/ocean-3605547__340.jpg"
        alt=""
        class="card-img-top"
        />
        <div class="card-body">
        <h4 class="card-title">เที่ยวทะเล</h4>
        <h6 class="card-subtitle mb-2 text-muted">เผยแพร่ 01/01/2021</h6>
        <p class="card-text">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti
            aliquam autem eum dolores amet iure ea sit beatae? Enim dolorum
            esse tempore optio animi tempora ipsam ducimus quia totam.
            Blanditiis?
        </p>
        <a href="#" class="btn btn-success">อ่านบทความ</a>
        </div>
    </div>
    </div>
</div>
```

### Grid System

```
<div class="container-fluid">
    <!-- 100% -->
    <div class="row">
    <div class="col-sm-12 alert alert-success">
        <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Unde iure
        et sequi quo accusamus alias id at veritatis quidem culpa!
        </p>
    </div>
    </div>
    <br />

    <!-- 50% -->
    <div class="row">
    <div class="col-sm-6 alert alert-success">
        <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Unde iure
        et sequi quo accusamus alias id at veritatis quidem culpa!
        </p>
    </div>
    <div class="col-sm-6 alert alert-success">
        <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Unde iure
        et sequi quo accusamus alias id at veritatis quidem culpa!
        </p>
    </div>
    </div>
    <br />

    <!-- 33.33% -->
    <div class="row">
    <div class="alert alert-success col-sm-4">
        <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Unde iure
        et sequi quo accusamus alias id at veritatis quidem culpa!
        </p>
    </div>
    <div class="alert alert-success col-sm-4">
        <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Unde iure
        et sequi quo accusamus alias id at veritatis quidem culpa!
        </p>
    </div>
    <div class="alert alert-success col-sm-4">
        <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Unde iure
        et sequi quo accusamus alias id at veritatis quidem culpa!
        </p>
    </div>
    </div>
    <br />

    <!-- 25% -->
    <div class="row">
    <div class="alert alert-success col-sm-3">
        <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Unde iure
        et sequi quo accusamus alias id at veritatis quidem culpa!
        </p>
    </div>
    <div class="alert alert-success col-sm-3">
        <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Unde iure
        et sequi quo accusamus alias id at veritatis quidem culpa!
        </p>
    </div>
    <div class="alert alert-success col-sm-3">
        <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Unde iure
        et sequi quo accusamus alias id at veritatis quidem culpa!
        </p>
    </div>
    <div class="alert alert-success col-sm-3">
        <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Unde iure
        et sequi quo accusamus alias id at veritatis quidem culpa!
        </p>
    </div>
    </div>
</div>
```

### Grid System Responsive

```
<div class="container">
    <div class="row">
    <div class="alert alert-success col-sm-12 col-md-9 col-lg-6">
        <h1>ยินดีต้อนรับเข้าสู่เว็ปไซต์</h1>
        <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga,
        deleniti!
        </p>
    </div>
    <div class="alert alert-danger col-sm-12 col-md-3 col-lg-6">
        <h1>พื้นที่โฆษณา</h1>
    </div>
    </div>
    <br />

    <div class="row">
    <div class="alert alert-success col-sm-6 col-md-8 col-lg-9">
        <h1>ยินดีต้อนรับเข้าสู่เว็ปไซต์</h1>
        <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga,
        deleniti!
        </p>
    </div>
    <div class="alert alert-danger col-sm-6 col-md-4 col-lg-3">
        <h1>พื้นที่โฆษณา</h1>
    </div>
    </div>
    <br />
</div>
```
