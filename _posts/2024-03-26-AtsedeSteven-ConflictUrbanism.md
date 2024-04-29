---
layout: post
date:   2023-03-26
image: "/conflict_urbanism_sp2024/images/AddisGroup_test/AerialviewofAddispre1935.png"
title:  " Navigating Addis Ababa:  Analyzing landmarks as nodes of neocolonial infiltration in the capital of African independence"
author: "Atsede Assayehgen, Steven Duncan"
---

<style>
    body {
        background-color: #FAF9f6; */
        color: #235347; /* Green color for text */
        font-family: 'Helvetica Neue', helvetica;
    }
</style>

**Research Topic**  


This project will specifically look at Africa Hall and the African Union Conference Center (AUCC), two landmarks molded by external investment that personify the tension between Ethiopia’s dual welcome and refusal of colonialism.  



*Image below*    

<div style="display: flex; justify-content: space-between; align-items: center;">
  <div style="width: 33%; text-align: center;">
    <img src="/conflict_urbanism_sp2024/images/AddisGroup_test/download1.png" alt="Description of image 1" style="width: 100%;">
    <p>1964</p>
  </div>
  <div style="width: 33%; text-align: center;">
    <img src="/conflict_urbanism_sp2024/images/AddisGroup_test/Buildup1990.png" alt="Description of image 2" style="width: 100%;">
    <p>1990</p>
  </div>
  <div style="width: 33%; text-align: center;">
    <img src="/conflict_urbanism_sp2024/images/AddisGroup_test/Buildup2022.png" alt="Description of image 3" style="width: 100%;">
    <p>2022</p>
  </div>
</div>

---
layout: post
title: "Your Post Title"
date: YYYY-MM-DD
---

<div class="carousel">
  <div class="carousel-images">
    <img src="/conflict_urbanism_sp2024/images/AddisGroup_test/download1.png" alt="1964">
    <img src="/conflict_urbanism_sp2024/images/AddisGroup_test/Buildup1990.png" alt="1990">
    <img src="/conflict_urbanism_sp2024/images/AddisGroup_test/Buildup2022.png.jpg" alt="2022">
  </div>
  <button class="prev" onclick="changeSlide(-1)">❮</button>
  <button class="next" onclick="changeSlide(1)">❯</button>
</div>

<p id="caption">1964</p>

<style>
.carousel {
  position: relative;
  max-width: 100%;
  margin: auto;
  overflow: hidden;
  display: flex;
  align-items: center;
}

.carousel-images img {
  width: 100%;
  display: none;
}

button {
  cursor: pointer;
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  background-color: transparent;
  border: none;
  font-size: 24px;
  color: black;
  padding: 10px;
}

.prev {
  left: 10px;
}

.next {
  right: 10px;
}
</style>

<script>
let slideIndex = 0;
showSlides(slideIndex);

function changeSlide(n) {
  showSlides(slideIndex += n);
}

function showSlides(n) {
  let slides = document.querySelectorAll('.carousel-images img');
  let caption = document.getElementById('caption');
  if (n >= slides.length) {slideIndex = 0}
  if (n < 0) {slideIndex = slides.length - 1}
  for (let i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";
  }
  slides[slideIndex].style.display = "block";
  // Update caption based on the image alt attribute
  caption.innerHTML = slides[slideIndex].alt;
}
</script>

![Map of Addis Ababa, 1964, Imperial Ethiopian Mapping & Geography Institute](/conflict_urbanism_sp2024/images/AddisGroup_test/download1.png)  


<div id="mapContainer" style="position: relative; height: 500px; overflow: hidden;">
    <iframe src="https://sfdduncan.github.io/PersonalProjects/" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" frameborder="0"></iframe>
    <button onclick="toggleFullscreen()" style="position: absolute; top: 10px; right: 10px; z-index: 10;">Toggle Fullscreen</button>
</div>

<script>
function toggleFullscreen() {
    let elem = document.getElementById('mapContainer');
    if (!document.fullscreenElement) {
        elem.requestFullscreen().catch(err => {
            alert(`Error attempting to enable fullscreen mode: ${err.message} (${err.name})`);
        });
    } else {
        if (document.exitFullscreen) {
            document.exitFullscreen();
        }
    }
}
</script>



 
