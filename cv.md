---
layout: default
title: CV
---

# Curriculum Vitae

<style>
.pdf-container {
    position: relative;
    width: 100%;
    height: 1055px; /* Height of an A4 page at 96 DPI (roughly equivalent to one full page) */
    overflow: hidden;
    border: 1px solid var(--card-border);
    transition: border-color 0.3s ease;
    background-color: var(--card-bg);
}
.pdf-container iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: 0;
    background-color: white; /* PDF viewer always needs white background */
}
@media screen and (max-width: 600px) {
    .pdf-container {
        height: 80vh; /* Use viewport height on mobile for better experience */
    }
}
/* Dark mode adjustments */
[data-theme="dark"] .pdf-container {
    box-shadow: 0 0 10px rgba(255, 255, 255, 0.1);
}
</style>

<div class="pdf-container">
    <iframe src="https://docs.google.com/viewer?url=https://danielcarstensen.com/assets/pdf/cv.pdf&embedded=true" title="Daniel Carstensen CV"></iframe>
</div>

<br>

You can also download my CV directly:
<a href="/assets/pdf/cv.pdf" class="cv-download-link">PDF<i class="fas fa-download"></i></a>
