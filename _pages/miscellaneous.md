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


<div class="gallery-wrapper">
    <div class="gallery-container">
        <figure>
            <img src="/images/hubei1.jpg" alt="Hubei Image 1" class="gallery-image">
        </figure>
        <figure>
            <img src="/images/hubei2.jpg" alt="Hubei Image 2" class="gallery-image">
        </figure>
        <figure>
            <img src="/images/hubei3.jpg" alt="Hubei Image 3" class="gallery-image">
        </figure>
        <figure>
            <img src="/images/hubei4.jpg" alt="Hubei Image 4" class="gallery-image">
        </figure>
    </div>
</div>

<input type="range" min="0" max="450" value="0" class="slider" id="myRange">

<center>Views in Wuhan</center>

<style>
.gallery-wrapper {
    width: 900px;
    overflow: hidden;
    margin: 0 auto; /* for centering the gallery */
}

.gallery-container {
    display: flex;
    transition: margin-left 0.3s ease;
}

figure {
    margin: 0;
    position: relative;
    width: 450px;
}

.gallery-image {
    width: 450px;
    height: auto;
}

.slider {
    width: 80%;
    margin: 20px auto; /* for centering the slider */
    display: block;
}
</style>

<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
<script>
$(document).ready(function() {
    $("#myRange").on("input", function() {
        let value = $(this).val();
        $(".gallery-container").css("margin-left", -value + "px");
    });
});
</script>
