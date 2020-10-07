---
title: Bath photos
layout: page
---

{%- for image in site.static_files -%}
    {%- if image.path contains 'photos/bath' -%}
        ![{{ image.basename}}]({{ image.path }})
    {%- endif -%}
{%- endfor -%}

