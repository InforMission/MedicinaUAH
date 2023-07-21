
---
Year: {{date | format("YYYY")}}
tags: Source
Authors: {{authors}}{{directors}}
---

Title:: {{title}}
URL: {{url}}
Zotero Link: {{pdfZoteroLink}}


{% for annotation in annotations -%}
    {%- if annotation.annotatedText -%}
    {{annotation.annotatedText}}
    {%- endif %}
    {%- if annotation.imageRelativePath -%}
    ![[{{annotation.imageRelativePath}}]] {%- endif %}
{% if annotation.comment %}
{{annotation.comment}}
{% endif %}

{% endfor -%}