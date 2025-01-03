```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS </title>
    <link rel="stylesheet" href="Ques1.css">
</head>
<body>
    <h1>CSS</h1>

    <div class="equation-container">
        <p class="equation">
            <span class="partial">∂<sup>2</sup>u</span> / <span class="partial">∂t<sup>2</sup></span> = c<sup>2</sup> 
            <span class="partial">∂<sup>2</sup>u</span> / <span class="partial">∂x<sup>2</sup></span>
        </p>
    </div>
    
    <!-- Section 1: Rounded Rectangle with Dashed Border and Grayscale -->
    <section class="rounded-dashed">
        <img src="https://cdn.pixabay.com/photo/2023/01/08/14/22/sample-7705350_640.jpg" alt="Rounded Rectangle Image">
    </section>

    <!-- Section 2: Tooltip -->
    <section class="tooltip-section">
        <div class="tooltip">Hover over me
            <span class="tooltiptext">Tooltip text</span>
        </div>
    </section>

    <!-- Clip property  -->
    <div class="image-container">
        <img src="https://www.guvi.in/blog/wp-content/uploads/2023/10/GUVI-logo-1-1200x675.webp" alt="GUVI Logo" class="clipped-image">
    </div>
    
    <!-- Drop Caps -->
    <div class="drop-cap-container">
        <p class="text"><span class="drop-cap">D</span>rop caps can be used to add emphasis to blocks of text but know they can affect readability. </p>
    </div>

    <!-- Section 3: Cursor Types -->
    <section class="cursor-section">
        <p class="pointer-cursor">Pointer Cursor</p>
        <p class="text-cursor">Text Cursor</p>
        <p class="crosshair-cursor">Crosshair Cursor</p>
    </section>

    <!-- Section 4: Box Model -->
    <section class="box-model-section">
        <div class="box-model">Box Model Example</div>
    </section>

    <!-- Section 5: Hover Effect on Span -->
    <section class="hover-effect-section">
        <span class="hover-effect">Hover over me!</span>
    </section>

    <!-- Section 6: 2D Translate -->
    <section class="translate-section">
        <div class="translate-example">Moved with Translate</div>
    </section>

    <!-- Section 7: Centered Background Image -->
    <section class="background-image-section">
        <div class="background-image-example">Centered Background</div>
    </section>

    <!-- Section 8: Flex Direction Reverse -->
    <section class="flex-direction-section">
        <div class="flex-container">
            <div class="flex-item">Item 1</div>
            <div class="flex-item">Item 2</div>
            <div class="flex-item">Item 3</div>
        </div>
    </section>

    <!-- Section 9: Image Border -->
    <section class="image-border-section">
        <img class="image-border" src="https://nikonrumors.com/wp-content/uploads/2014/03/Nikon-1-V3-sample-photo.jpg" alt="Image Border Example">
        <!-- <div class="image-border">Image Border Example</div> -->
    </section>

    <!-- Section 10: Rounded Corner -->
    <section class="rounded-corner-section">
        <div class="rounded-corner">Rounded Corner</div>
    </section>

    <!-- Section 11: Hover Opacity -->
    <section class="hover-opacity-section">
        <img class="hover-opacity" src="https://static.remove.bg/sample-gallery/graphics/bird-thumbnail.jpg" alt="Hover Effect Image">
    </section>

    <!-- Section 12: Absolute Position -->
    <section class="absolute-position-section">
        <div class="absolute-right">Absolute Right</div>
    </section>

    <!-- Section 13: Scrollable Content -->
    <section class="scrollable-section">
        <div class="scrollable-content">This is a scrollable content area. Lorem ipsum dolor sit amet consectetur, adipisicing elit. Alias molestias consectetur quis assumenda, voluptatibus nostrum dolor blanditiis, voluptatem quisquam, cum velit vitae ipsum sapiente provident! Consequuntur aliquam totam ex quam!</div>
    </section>

    <!-- Section 14: Gradient Background -->
    <section class="gradient-background-section">
        <div class="gradient-background">Gradient Background</div>
    </section>

    <!-- Section 15: Rotate -->
    <section class="rotate-section">
        <div class="rotate">Rotated Element</div>
    </section>
</body>
</html>
```

```css
.equation-container {
    background-color: #f0f0f0; /* Light gray background */
    padding: 20px;
    border-radius: 10px;
    max-width: 600px;
    margin: 20px auto;
    text-align: center;
    font-family: 'Georgia', serif;
}

.equation {
    font-size: 24px;
    line-height: 1.6;
    font-weight: bold;
    margin: 0;
}

.partial {
    font-size: 28px;
    vertical-align: middle;
}

sup {
    font-size: 16px;
    vertical-align: super;
}


/* Section 1: Rounded Rectangle, Dashed Border, Grayscale */
.rounded-dashed img {
    border: 2px dashed black;
    border-radius: 15px;
    filter: grayscale(100%);
    width: 300px;
}

/* Section 2: Tooltip */
.tooltip {
    position: relative;
    display: inline-block;
    cursor: pointer;
    margin-top: 30px;
    margin-bottom: 30px;
}

.tooltip .tooltiptext {
    visibility: hidden;
    background-color: black;
    color: #fff;
    text-align: center;
    padding: 5px;
    border-radius: 5px;
    position: absolute;
    z-index: 1;
}

.tooltip:hover .tooltiptext {
    visibility: visible;
}

.image-container {
    width: 500px; 
    height: 500px; 
    overflow: hidden;
    position: relative; 
}

/* Image with clipping applied */
.clipped-image {
    width: 100%;
    height: 100%;
    object-fit: cover; 
    clip: rect(0, 500px, 500px, 0); 
    position: absolute; 
}

.drop-cap-container {
    background-color: #f0f0f0; 
    padding: 20px;
    border-radius: 10px;
    max-width: 600px;
    margin: 20px auto;
}

.drop-cap {
    font-size: 60px;
    font-weight: bold;
    float: left;
    line-height: 1;
    padding-right: 10px;
    padding-top: 10px;
    margin-top: 5px;
}

.text {
    font-size: 18px;
    line-height: 1.6;
    margin-left: 70px; 
}

/* Section 3: Cursor Types */
.cursor-section .pointer-cursor {
    cursor: pointer;
}

.cursor-section .text-cursor {
    cursor: text;
}

.cursor-section .crosshair-cursor {
    cursor: crosshair;
}

/* Section 4: Box Model */
.box-model {
    padding: 20px;
    margin: 10px;
    border: 5px solid blue;
    background-color: lightgray;
}

/* Section 5: Hover Effect on Span */
.hover-effect {
    font-size: 16px;
    color: black;
    font-family: Arial, sans-serif;
}

.hover-effect:hover {
    font-size: 20px;
    color: red;
    font-family: 'Courier New', Courier, monospace;
}

/* Section 6: 2D Translate */
.translate-example {
    transform: translate(50px, 50px);
    background-color: lightblue;
    padding: 10px;
}

/* Section 7: Centered Background Image */
.background-image-example {
    background: url('background.jpg') center center no-repeat;
    height: 200px;
}

/* Section 8: Flex Direction Reverse */
.flex-container {
    display: flex;
    flex-direction: row-reverse;
}

.flex-item {
    padding: 10px;
    background-color: lightgreen;
    margin: 5px;
}

/* Section 9: Image Border */
.image-border {
    border-image: url('border.png') 30 fill;
    border-width: 10px;
    border-style: solid;
    background-size: 100% 100%;
}

/* Section 10: Rounded Corner */
.rounded-corner {
    /* border-radius: 0 0 25px 25px; */
    background-color: lightcoral;
    padding: 20px;
    border-bottom-left-radius: 25px 25px;
}

/* Section 11: Hover Opacity */
.hover-opacity {
    opacity: 0.5;
    transition: opacity 0.3s;
    width: 200px;
}

.hover-opacity:hover {
    opacity: 1;
}

/* Section 12: Absolute Positioning */
.absolute-right {
    position: absolute;
    right: 0;
    background-color: lightyellow;
    padding: 10px;
}

/* Section 13: Scrollable Content */
.scrollable-content {
    width: 200px;
    height: 100px;
    overflow: scroll;
    border: 1px solid black;
}

/* Section 14: Gradient Background */
.gradient-background {
    background: linear-gradient(to bottom, white, red, blue, green);
    padding: 20px;
    color: #fff;
}

/* Section 15: Rotate */
.rotate {
    transform: rotate(45deg);
    background-color: lightpink;
    padding: 20px;
    display: inline-block;
    margin-top: 80px;
}
```
