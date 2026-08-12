---
layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 5
description:
---

<div style="display: flex; flex-wrap: wrap; gap: 0.75rem; margin-bottom: 1rem">
  <a href="{{ '/assets/pdf/mycv.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer">Open PDF in a new tab</a>
  <a href="{{ '/assets/pdf/mycv.pdf' | relative_url }}" download>Download PDF</a>
</div>

<object
  data="{{ '/assets/pdf/mycv.pdf' | relative_url }}#view=FitH"
  type="application/pdf"
  aria-label="Zeyu Zhang curriculum vitae"
  style="width: 100%; height: calc(100vh - 180px); min-height: 700px; border: 1px solid var(--global-divider-color); border-radius: 0.25rem"
>
  <p>
    Your browser cannot display the embedded PDF.
    <a href="{{ '/assets/pdf/mycv.pdf' | relative_url }}">Open or download the CV</a>.
  </p>
</object>
