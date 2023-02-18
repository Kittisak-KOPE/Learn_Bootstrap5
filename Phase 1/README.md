# Learn_Bootstrap5

### Container

```
Container
Container-Fluid
Container-{breakpoint}
    X-Small             None            <576px
    Small               sm              >575px
    Medium              md              >787px
    Large               lg              >991px
    Extra large         xl              >1199px
    Extra extra large   xxl             >1399px
```

### Message handling

```
<div class="container" style="margin-top: 20px">
    <!-- p to h1-h6 -->
    <p class="h1">Heading 1</p>
    <p class="h2">Heading 2</p>

    <!-- Display Heading -->
    <h1 class="display-1">Display 1</h1>
    <h1 class="display-6">Display 6</h1>

    <!-- lead -->
    <p class="lead">
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Culpa officia
    magnam labore illo soluta totam rem, inventore quas, consequatur amet
    sapiente quaerat esse incidunt cumque voluptatibus vel autem quibusdam
    officiis.
    </p>

    <!-- Set the thickness of the text -->
    <p class="fw-bold">Bold</p>
    <p class="fw-bolder">Bolder</p>
    <p class="fw-normal">Normal</p>
    <p class="fw-light">Light</p>
    <p class="fw-lighter">Lighter</p>
    <p class="fst-italic">Italic</p>

    <!-- set the format of the text -->
    <p class="text-uppercase">Hello world</p>
    <p class="text-lowercase">Hello world</p>
    <p class="text-capitalize">Hello world</p>

    <!-- set the size of the text -->
    <p class="fs-1">Hello World</p>
    <p class="fs-6">Hello World</p>

    <!-- Blockquote -->
    <p class="blockqoute">
    Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quam rem,
    nihil laudantium tempore a laboriosam voluptatum numquam veritatis,
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolores cumque
    temporibus cum non asperiores eaque tempora mollitia, dolorum repellat
    veniam!
    </p>

    <!-- List -->
    <!-- <ul class="list-unstyled"> -->
    <ul class="list-inline"></ul>
    <li class="list-inline-item">Item 1</li>
    <li class="list-inline-item">Item 2</li>
    <li class="list-inline-item">Item 3</li>
    </ul>
</div>
```

### color and background

```
<div class="container" style="margin-top: 20px">
    <!-- text color -->
    <p class="text-primary">Primary</p>
    <p class="text-secondary">Secondary</p>
    <p class="text-success">Success</p>
    <p class="text-danger">Danger</p>
    <p class="text-warning">Warning</p>
    <p class="text-info">Info</p>
    <p class="text-light bg-dark">Light</p>
    <p class="text-dark">Dark</p>

    <!-- background color -->
    <p class="bg-primary">Background Primary</p>
    <p class="bg-secondary">Background Secondary</p>
    <p class="bg-success">Background Success</p>
    <p class="bg-danger">Background Danger</p>
    <p class="bg-warning">Background Warning</p>
    <p class="bg-info">Background Info</p>
    <p class="bg-light">Background Light</p>
    <p class="bg-dark text-light">Background Dark</p>
    <p class="bg-transparent">Background Transparent</p>

    <!-- Link color setting -->
    <p><a href="" class="text-primary">Link Primary</a></p>
    <p><a href="" class="text-secondary">Link Secondary</a></p>
    <p><a href="" class="text-success">Link Success</a></p>
    <p><a href="" class="text-danger">Link Danger</a></p>
    <p><a href="" class="text-warning">Link Warning</a></p>
    <p><a href="" class="text-info">Link Info</a></p>
    <p><a href="" class="text-light bg-dark">Link Light</a></p>
    <p><a href="" class="text-dark">Link Dark</a></p>
    <p><a href="" class="text-body">Link Body</a></p>
    <p><a href="" class="text-muted">Link Muted</a></p>
</div>
```

### Alignment & Display

```
<div class="container" style="margin-top: 20px">
    <!-- กำหนดตำแหน่ง (แนวนอน) -->
    <p class="text-start">Hello World Start</p>
    <p class="text-center">Hello World Center</p>
    <p class="text-end">Hello World End</p>

    <!-- Block to Inline -->
    <h1 class="bg-success d-inline">Hello World</h1>
    <h1 class="bg-success d-inline">Hello Bootstrap</h1>

    <!-- Inline to Block -->
    <span class="bg-warning d-block">Hello Block</span>

    <!-- Inline-Block -->
    <div class="bg-success d-inline-block">
    <h3>Hello</h3>
    This is Bootstrap 5
    </div>
</div>
```

### Float & Fixed Position

```
<div class="container" style="margin-top: 20px">
    <!-- Float & Fixed Position Responsive-->
    <div>
    <img
        src="https://cdn.pixabay.com/photo/2020/10/23/17/47/girl-5679419__340.jpg"
        alt=""
        class="float-start"
    />
    <p>Float Start</p>
    </div>

    <div>
    <img
        src="https://cdn.pixabay.com/photo/2020/10/23/17/47/girl-5679419__340.jpg"
        alt=""
        class="float-end"
    />
    <p>Float End</p>
    </div>

    <div>
    <img
        src="https://cdn.pixabay.com/photo/2020/10/23/17/47/girl-5679419__340.jpg"
        alt=""
        class="float-none"
    />
    <p>Float None</p>
    </div>

    <!-- ClearFix -->
    <div class="bg-success clearfix">
    <button class="float-start">Float Left</button>
    <button class="float-end">Float Right</button>
    </div>
    <h3>Hello Bootstrap 5</h3>
    <p>
    Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ex adipisci
    obcaecati qui reprehenderit cumque, dolore quia veniam in facere, eius
    explicabo sunt officia eos alias omnis ad ducimus. Non, facilis!
    </p>

    <!-- Fixed -->
    <h3 class="fixed-top">Fixed Top</h3>
    <h3 class="sticky-top">Sticky Top</h3>
    <p>
    Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quae
    repudiandae ea eveniet expedita velit iure sapiente praesentium in optio
    labore veritatis, minus nesciunt, cupiditate adipisci est aliquid harum,
    consequuntur quaerat laudantium ipsum nobis molestiae qui corrupti? Quod
    laudantium delectus officia nam inventore consequatur explicabo adipisci
    iure odio doloribus sint temporibus fuga cum voluptatum architecto rerum
    suscipit hic, dolorum voluptatem sequi saepe assumenda! Nam, blanditiis
    omnis autem minima expedita provident accusamus tenetur debitis modi
    possimus corporis error, similique magnam asperiores quis quidem
    maiores. Perspiciatis aliquid consectetur laboriosam eligendi, cum
    maiores, ducimus, atque placeat pariatur quasi voluptates sequi optio.
    Veritatis, modi quaerat.
    </p>
    <h3 class="fixed-bottom">Fixed Bottom</h3>
    <p>
    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Laborum,
    fugiat consequuntur? Aliquam harum cum expedita perferendis ea officiis
    explicabo ad minus neque! Fuga corrupti quia necessitatibus soluta eos
    odio. Provident illo qui vitae odit id facere. Quod nam, ad iusto
    voluptatibus obcaecati dignissimos non blanditiis. Deleniti quo delectus
    soluta at incidunt eos numquam sunt aut aperiam quia quibusdam quae,
    expedita dolor consequuntur similique fugit voluptatem voluptatum dicta
    enim? Alias veniam quis ut quam doloribus molestiae pariatur ab,
    explicabo nobis atque magnam. Minima voluptate, aliquid laboriosam
    commodi atque sint esse, eius consequuntur praesentium, hic ab dicta
    temporibus! Molestias aut assumenda dignissimos.
    </p>

    <!-- Invisible -->
    <h1 class="invisible">Hello Visible</h1>
</div>
```

### Margin

```
<div class="container" style="margin-top: 20px">
    <!-- Margin Spacing -->
    <h1 class="bg-success mb-0">Margin Bottom 0</h1>
    <h1 class="bg-success mb-1">Margin Bottom 1</h1>
    <h1 class="bg-success mb-2">Margin Bottom 2</h1>
    <h1 class="bg-success mb-3">Margin Bottom 3</h1>
    <h1 class="bg-success mb-4">Margin Bottom 4</h1>
    <h1 class="bg-success mb-5">Margin Bottom 5</h1>

    <!-- Margin Side -->
    <h1 class="bg-warning mt-3">Margin Top</h1>
    <h1 class="bg-warning mb-5">Margin Bottom</h1>
    <h1 class="bg-warning ms-5">Margin Left</h1>
    <h1 class="bg-warning me-3">Margin Right</h1>

    <!-- ML & MR Spacing -->
    <h1 class="bg-primary me-5">Margin Right 5</h1>
    <h1 class="bg-primary ms-3">Margin Left 3</h1>

    <!-- MX -->
    <h1 class="bg-danger mx-5">Margin Left & Right 5</h1>
    <!-- MY -->
    <h1 class="bg-danger my-5">Margin Top & Bottom 5</h1>
    <!-- Blank -->
    <h1 class="bg-danger m-5">Margin Blank</h1>
</div>
```

### Padding

```
<div class="container" style="margin-top: 20px">
    <!-- Padding Spacing -->
    <h1 class="bg-success pb-0">Padding Bottom 0</h1>
    <h1 class="bg-success pb-1">Padding Bottom 1</h1>
    <h1 class="bg-success pb-2">Padding Bottom 2</h1>
    <h1 class="bg-success pb-3">Padding Bottom 3</h1>
    <h1 class="bg-success pb-4">Padding Bottom 4</h1>
    <h1 class="bg-success pb-5">Padding Bottom 5</h1>

    <!-- Padding Side -->
    <h1 class="bg-warning pt-4">Padding Top</h1>
    <h1 class="bg-warning pb-4">Padding Bottom</h1>
    <h1 class="bg-warning ps-4">Padding Left</h1>
    <h1 class="bg-warning text-end pe-4">Padding Right</h1>

    <!-- PL & PR Spacing -->
    <h1 class="bg-primary text-end pe-5">Padding Right 5</h1>
    <h1 class="bg-primary ps-3">Padding Left 3</h1>

    <!-- PX -->
    <h1 class="bg-danger px-5">Padding Left & Right 5</h1>
    <!-- PY -->
    <h1 class="bg-danger py-5">Padding Top & Bottom 5</h1>
    <!-- Blank -->
    <h1 class="bg-danger p-5">Padding Blank</h1>
</div>
```
