---
layout: archive
title: ""
permalink: /miscellaneous/
author_profile: true
---

## Habits
---
I enjoy film, cooking and taking photos of nature in my spare time.

## Galaries
---
<div style="display: flex; justify-content: center;">
  <div style="margin-right: 10px;">
    <img src="/images/snow1.bmp" alt="Snow Image 1" style="width: 450px; height: auto;">
  </div>
  <div>
    <img src="/images/snow2.jpg" alt="Snow Image 2" style="width: 450px; height: auto;">
  </div>
</div>
<div style="text-align: center;">
  Sivan and Amily enjoyed their skiing advanture in an icy world. Then they made a cute little snowman.
</div>

---
<div class="gallery-wrapper">
    <div class="gallery-container" id="galleryContainer">
        <img src="/images/hubei1.jpg" alt="Hubei Image 1" class="gallery-image">
        <img src="/images/hubei2.jpg" alt="Hubei Image 2" class="gallery-image">
        <img src="/images/hubei3.jpg" alt="Hubei Image 3" class="gallery-image">
        <img src="/images/hubei4.jpg" alt="Hubei Image 4" class="gallery-image">
    </div>
</div>

<input type="range" min="1" max="100" value="1" class="slider" id="myRange">

<center>你的配文</center>

<style>
.gallery-wrapper {
    width: 900px;
    overflow: hidden;
    margin: 0 auto;
}

.gallery-container {
    width: 1800px;
    transition: transform 0.3s ease;
}

.gallery-image {
    width: 450px;
    height: auto;
    float: left;
}

.slider {
    width: 80%;
    margin: 20px auto;
    display: block;
}
</style>

<script>
document.getElementById('myRange').addEventListener('input', function(e) {
    var value = e.target.value;
    document.getElementById('galleryContainer').style.transform = 'translateX(' + -(value * 9) + 'px)';
});
</script>
