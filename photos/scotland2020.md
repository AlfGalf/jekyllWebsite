---
title: Scotland 2020 photos
layout: page
---

{%- for image in site.static_files -%}
    {%- if image.path contains 'photos/Scotland2020' -%}
        ![{{ image.basename}}]({{ image.path }})
    {%- endif -%}
{%- endfor -%}

