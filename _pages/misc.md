---
layout: page
title: Miscellaneous
permalink: /misc/
description: 
nav: true
nav_order: 9
---

<div class="misc-content">

<p>I'm deeply drawn to the humanities and the arts. I’m well-versed in Chinese calligraphy and poetry, and music has long been part of my life — I enjoy symphonies and live shows, and I do some rap and violin. I once organized a <a href="#" onclick="openImageModal('rock-concert-image')" style="text-decoration: none; color: #007bff; cursor: pointer;">concert at SJTU</a>, and recently <a href="https://www.youtube.com/watch?v=Kl0-Pdo0vi8" target="_blank" style="text-decoration: none; color: #007bff;">Vltava</a> has been echoing in my mind.</p>

<p>I stay active through <a href="#" onclick="openImageModal('cycling-image')" style="text-decoration: none; color: #007bff; cursor: pointer;">speed cycling</a>, tennis, ping pong, volleyball, and swimming.</p>

<p>I'm part of the <a href="https://youth.sjtu.edu.cn/qc_qmgc/3733.html" target="_blank" style="text-decoration: none; color: #007bff;">Rongchang Chucai Program</a> — a university-wide initiative for nurturing future leaders. I co-founded the Rongchang AI Club and Jiaorong Tech.</p>

<p>Lately, I've been exploring photography with my new camera.</p>

</div>

<!-- Modal for rock concert image -->
<div id="imageModal" class="modal" style="display: none; position: fixed; z-index: 1000; padding-top: 50px; left: 0; top: 0; width: 100%; height: 100%; overflow: auto; background-color: rgba(0,0,0,0.9);">
  <span class="close" onclick="closeImageModal()" style="position: absolute; top: 15px; right: 35px; color: #f1f1f1; font-size: 40px; font-weight: bold; cursor: pointer; z-index: 1001;">&times;</span>
  <img class="modal-content" id="modalImage" style="margin: auto; display: block; width: 80%; max-width: 700px; border-radius: 8px;">
  <div id="caption" style="margin: auto; display: block; width: 80%; max-width: 700px; text-align: center; color: #ccc; padding: 10px 0; font-size: 1.2rem;"></div>
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

/* Modal styles */
.modal {
  animation: fadeIn 0.3s ease;
}

@keyframes fadeIn {
  from { opacity: 0; }
  to { opacity: 1; }
}

.modal-content {
  animation: slideIn 0.3s ease;
}

@keyframes slideIn {
  from { transform: translateY(-50px); opacity: 0; }
  to { transform: translateY(0); opacity: 1; }
}

.close:hover {
  opacity: 0.7;
  transform: scale(1.1);
  transition: all 0.2s ease;
}

@media (max-width: 768px) {
  .modal-content {
    width: 95%;
    padding: 0 10px;
  }
  
  #caption {
    width: 95%;
    font-size: 1rem;
  }
}
</style>

<script>
function openImageModal(imageId) {
  const modal = document.getElementById("imageModal");
  const modalImg = document.getElementById("modalImage");
  const captionText = document.getElementById("caption");
  
  modal.style.display = "block";
  
  // Set different images and captions based on imageId
  if (imageId === 'rock-concert-image') {
    modalImg.src = "/assets/img/rock_concert.JPG";
    captionText.innerHTML = "Rock concert organized at SJTU - An unforgettable night of music and energy!";
  } else if (imageId === 'cycling-image') {
    modalImg.src = "/assets/img/cycling.jpg";
    captionText.innerHTML = "Speed cycling - Embracing the wind and the freedom of the road!";
  }
  
  // Prevent body scroll when modal is open
  document.body.style.overflow = 'hidden';
}

function closeImageModal() {
  const modal = document.getElementById("imageModal");
  modal.style.display = "none";
  
  // Restore body scroll
  document.body.style.overflow = 'auto';
}

// Close modal when clicking outside the image
window.onclick = function(event) {
  const modal = document.getElementById("imageModal");
  if (event.target == modal) {
    closeImageModal();
  }
}

// Close modal with ESC key
document.addEventListener('keydown', function(event) {
  if (event.key === 'Escape') {
    closeImageModal();
  }
});
</script> 
