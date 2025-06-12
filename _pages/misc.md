---
layout: page
title: misc
permalink: /misc/
description: Personal interests, hobbies, and places I've been to.
nav: true
nav_order: 9
---

<div class="misc-content">

<p>I'm deeply drawn to the humanities and the arts. I'm trained in Chinese calligraphy and poetry, and music has long been part of my life — I enjoy symphonies and live shows, and I rap as well. I once organized a <a href="#" onclick="openImageModal('rock-concert-image')" style="text-decoration: none; color: #007bff; cursor: pointer;">rock concert at SJTU</a>, and recently <a href="https://www.youtube.com/watch?v=3G4NKzmfC-Q" target="_blank" style="text-decoration: none; color: #007bff;">Vltava</a> has been echoing in my mind.</p>

<p>I stay active through speed cycling, tennis, ping pong, volleyball, and swimming.</p>

<p>I'm part of the <a href="#" target="_blank" style="text-decoration: none; color: #007bff;">Rongchang Chucai Program</a> — a university-wide initiative for nurturing future leaders. Through it, I've joined social practice projects in Guangxi and the Greater Bay Area. I also co-founded the Rongchang AI Club and <a href="#" target="_blank" style="text-decoration: none; color: #007bff;">Jiaorong Tech</a>.</p>

<p>Lately, I've been exploring photography with my new camera. Below is a list of places I've visited, along with the memories that stayed with me.</p>

<br>

<h3>Places I have been to:</h3>

<div class="travel-section">
  <h4>International Destinations</h4>
  <div class="destinations-grid">
    <div class="destination-item">
      <div class="destination-flag">🇺🇸</div>
      <span>California, New York</span>
    </div>
    <div class="destination-item">
      <div class="destination-flag">🇯🇵</div>
      <span>Tokyo, Kyoto, Osaka</span>
    </div>
    <div class="destination-item">
      <div class="destination-flag">🇰🇷</div>
      <span>Seoul, Jeju Island</span>
    </div>
    <div class="destination-item">
      <div class="destination-flag">🇰🇭</div>
      <span>Cambodia</span>
    </div>
    <div class="destination-item">
      <div class="destination-flag">🇹🇼</div>
      <span>Taiwan</span>
    </div>
    <div class="destination-item">
      <div class="destination-flag">🇭🇰</div>
      <span>Hong Kong</span>
    </div>
    <div class="destination-item">
      <div class="destination-flag">🇲🇴</div>
      <span>Macau</span>
    </div>
  </div>

  <h4>Domestic Destinations (China)</h4>
  <div class="destinations-grid">
    <div class="destination-item">
      <div class="destination-flag">🏙️</div>
      <span>Shanghai, Beijing</span>
    </div>
    <div class="destination-item">
      <div class="destination-flag">🏡</div>
      <span>Zhejiang (hometown)</span>
    </div>
    <div class="destination-item">
      <div class="destination-flag">🌸</div>
      <span>Guangdong, Jiangsu</span>
    </div>
    <div class="destination-item">
      <div class="destination-flag">🏔️</div>
      <span>Hebei, Inner Mongolia</span>
    </div>
    <div class="destination-item">
      <div class="destination-flag">❄️</div>
      <span>Liaoning, Jilin, Heilongjiang</span>
    </div>
    <div class="destination-item">
      <div class="destination-flag">🌊</div>
      <span>Fujian, Shandong</span>
    </div>
    <div class="destination-item">
      <div class="destination-flag">🏞️</div>
      <span>Jiangxi, Henan, Hubei</span>
    </div>
    <div class="destination-item">
      <div class="destination-flag">🌿</div>
      <span>Hunan, Guangxi, Sichuan</span>
    </div>
    <div class="destination-item">
      <div class="destination-flag">🏜️</div>
      <span>Shanxi, Gansu, Qinghai</span>
    </div>
  </div>
</div>

<br>

<h3>Places I'm going soon:</h3>
<div class="upcoming-destinations">
  <div class="destination-item upcoming">
    <div class="destination-flag">🇸🇬</div>
    <span>Singapore</span>
  </div>
  <div class="destination-item upcoming">
    <div class="destination-flag">🇦🇺</div>
    <span>Sydney</span>
  </div>
  <div class="destination-item upcoming">
    <div class="destination-flag">🇪🇺</div>
    <span>Europe</span>
  </div>
</div>

<br>

<h3>Places I'm going later:</h3>
<div class="future-destinations">
  <div class="destination-item future">
    <div class="destination-flag">🌍</div>
    <span>Anywhere else in the world</span>
  </div>
</div>

</div>

<!-- Modal for rock concert image -->
<div id="imageModal" class="modal" style="display: none; position: fixed; z-index: 1000; padding-top: 100px; left: 0; top: 0; width: 100%; height: 100%; overflow: auto; background-color: rgba(0,0,0,0.9);">
  <span class="close" onclick="closeImageModal()" style="position: absolute; top: 15px; right: 35px; color: #f1f1f1; font-size: 40px; font-weight: bold; cursor: pointer;">&times;</span>
  <img class="modal-content" id="modalImage" style="margin: auto; display: block; width: 80%; max-width: 700px;">
  <div id="caption" style="margin: auto; display: block; width: 80%; max-width: 700px; text-align: center; color: #ccc; padding: 10px 0; height: 150px;"></div>
</div>

<style>
.misc-content {
  max-width: 800px;
  margin: 0 auto;
  line-height: 1.6;
}

.misc-content p {
  margin-bottom: 1.5em;
  font-size: 1.1em;
}

.travel-section {
  margin: 2em 0;
}

.travel-section h4 {
  color: #333;
  border-bottom: 2px solid #007bff;
  padding-bottom: 0.5em;
  margin: 1.5em 0 1em 0;
}

.destinations-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 0.8em;
  margin-bottom: 1.5em;
}

.destination-item {
  display: flex;
  align-items: center;
  padding: 0.8em 1em;
  background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
  border-radius: 8px;
  border-left: 4px solid #007bff;
  transition: all 0.3s ease;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.destination-item:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 8px rgba(0,0,0,0.15);
  background: linear-gradient(135deg, #e3f2fd 0%, #bbdefb 100%);
}

.destination-flag {
  font-size: 1.5em;
  margin-right: 0.8em;
  min-width: 30px;
}

.destination-item span {
  font-weight: 500;
  color: #333;
}

.upcoming-destinations, .future-destinations {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 0.8em;
  margin: 1em 0;
}

.destination-item.upcoming {
  border-left-color: #28a745;
  background: linear-gradient(135deg, #f1f8e9 0%, #dcedc8 100%);
}

.destination-item.upcoming:hover {
  background: linear-gradient(135deg, #e8f5e8 0%, #c8e6c8 100%);
}

.destination-item.future {
  border-left-color: #6c757d;
  background: linear-gradient(135deg, #f8f9fa 0%, #dee2e6 100%);
}

.destination-item.future:hover {
  background: linear-gradient(135deg, #e9ecef 0%, #ced4da 100%);
}

.modal:hover {
  cursor: pointer;
}

@media (max-width: 768px) {
  .destinations-grid {
    grid-template-columns: 1fr;
  }
  
  .upcoming-destinations, .future-destinations {
    grid-template-columns: 1fr;
  }
}
</style>

<script>
function openImageModal(imageId) {
  // You can replace this with actual image path when you have the rock concert image
  const modal = document.getElementById("imageModal");
  const modalImg = document.getElementById("modalImage");
  const captionText = document.getElementById("caption");
  
  modal.style.display = "block";
  modalImg.src = "/assets/img/rock_concert_placeholder.jpg"; // Replace with actual image path
  captionText.innerHTML = "Rock concert organized at SJTU";
}

function closeImageModal() {
  document.getElementById("imageModal").style.display = "none";
}

// Close modal when clicking outside the image
window.onclick = function(event) {
  const modal = document.getElementById("imageModal");
  if (event.target == modal) {
    modal.style.display = "none";
  }
}
</script> 