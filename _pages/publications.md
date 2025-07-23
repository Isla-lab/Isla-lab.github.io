---
title: "ISLa - Publications"
layout: gridlay
excerpt: "ISLa Group Publications."
sitemap: false
permalink: /publications/
---

<h2>ISLa Group Publications</h2>

<!-- Spinner + Testo -->
<div id="loading-container" style="text-align:center; margin: 20px 0;">
  <div id="loading-spinner" class="spinner"></div>
  <p id="loading-text">Loading...</p>
</div>

<!-- Div per BibBase -->
<div id="bibbase"></div>

<!-- Script BibBase -->
<script src="https://bibbase.org/show?bib=https://raw.githubusercontent.com/Isla-lab/Isla-lab.github.io/refs/heads/master/_data/pubs.bib&group0=year&jsonp=1&owner=none"></script>

<!-- Spinner CSS -->
<style>
.spinner {
  border: 6px solid #f3f3f3;
  border-top: 6px solid #555;
  border-radius: 50%;
  width: 40px;
  height: 40px;
  animation: spin 1s linear infinite;
  margin: 0 auto 10px auto;
}

@keyframes spin {
  0% { transform: rotate(0deg); }
  100% { transform: rotate(360deg); }
}
</style>

<!-- Nascondi spinner e testo quando BibBase ha caricato -->
<script>
  function hideLoadingWhenReady() {
    const container = document.getElementById('loading-container');
    const checkExist = setInterval(() => {
      const bibContent = document.querySelector('#bibbase .bibbase_group');
      if (bibContent && bibContent.children.length > 0) {
        container.style.display = 'none';
        clearInterval(checkExist);
      }
    }, 200); // controlla ogni 200ms
  }

  document.addEventListener("DOMContentLoaded", hideLoadingWhenReady);
</script>
