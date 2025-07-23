---
title: "ISLa - Publications"
layout: gridlay
excerpt: "ISLa Group Publications."
sitemap: false
permalink: /publications/
---

<h2>ISLa Group Publications</h2>

<!-- Loading message -->
<p id="loading-text" style="text-align:center; margin: 20px 0;">Loading publications...</p>

<!-- BibBase container -->
<div id="bibbase"></div>

<!-- BibBase script -->
<script src="https://bibbase.org/show?bib=https://raw.githubusercontent.com/Isla-lab/Isla-lab.github.io/refs/heads/master/_data/pubs.bib&group0=year&jsonp=1&owner=none"></script>

<!-- Script to hide the loading message after BibBase finishes loading -->
<script>
  function hideLoadingTextWhenReady() {
    const loadingText = document.getElementById('loading-text');
    const checkExist = setInterval(() => {
      const bibContent = document.querySelector('#bibbase .bibbase_group');
      if (bibContent && bibContent.children.length > 0) {
        loadingText.style.display = 'none';
        clearInterval(checkExist);
      }
    }, 200); // check every 200ms
  }

  document.addEventListener("DOMContentLoaded", hideLoadingTextWhenReady);
</script>
