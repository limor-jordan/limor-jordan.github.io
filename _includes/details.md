{%- comment -%}
  Include vars:
  label
  content
{%- endcomment -%}

<details markdown="1">
  <summary>
    {{ include.label }}
  </summary>
{{ include.content }}
</details>
