---
title: Nature photos
layout: page
---

{%- for image in site.static_files -%}
    {%- if image.path contains 'photos/Nature' -%}
        ![{{ image.basename}}]({{ image.path }})
    {%- endif -%}
{%- endfor -%}

