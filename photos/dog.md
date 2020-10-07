---
title: Dog photos
layout: page
---

{%- for image in site.static_files -%}
    {%- if image.path contains 'photos/Dog' -%}
        ![{{ image.basename}}]({{ image.path }})
    {%- endif -%}
{%- endfor -%}

