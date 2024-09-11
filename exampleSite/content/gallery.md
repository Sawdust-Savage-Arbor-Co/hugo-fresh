---
title: "Gallery"
---
  <div class="gallery">
    <!-- Add your images here -->
    <div class="gallery-item">
      <img src="/gallery/1.png" alt="Image 1">
    </div>
    <div class="gallery-item">
      <img src="/gallery/2.png" alt="Image 2">
    </div>
    <!-- Repeat for all images -->
  </div>
<style>
.gallery {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
}
.gallery-item {
  flex: 1 1 calc(33.333% - 10px);
  box-sizing: border-box;
}
.gallery-item img {
  width: 100%;
  height: auto;
  display: block;
}
</style>
