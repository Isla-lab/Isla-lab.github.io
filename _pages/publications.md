---
title: "ISLa - Publications"
layout: gridlay
excerpt: "ISLa Group Publications."
sitemap: false
permalink: /publications/
---

<h2>ISLa Group Publications</h2>

<!-- Spinner di caricamento -->
<div id="loading-spinner" class="spinner"></div>

<!-- Div per BibBase -->
<div id="bibbase"></div>

<!-- BibBase script -->
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
  margin: 30px auto;
}

@keyframes spin {
  0% { transform: rotate(0deg); }
  100% { transform: rotate(360deg); }
}
</style>

<!-- Nascondi spinner quando BibBase ha finito -->
<script>
  const observer = new MutationObserver((mutations, obs) => {
    const bibContent = document.querySelector('#bibbase .bibbase_group');
    if (bibContent) {
      document.getElementById('loading-spinner').style.display = 'none';
      obs.disconnect();
    }
  });

  observer.observe(document.getElementById('bibbase'), {
    childList: true,
    subtree: true
  });
</script>
