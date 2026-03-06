---
title: test HTML
date: 2026-03-06T00:36:50Z
link: {{ gh_repo_source_base_url }}/{{ file_path }}
use_html_content: yes
link2: https://raw.githubusercontent.com/Desvelao/dsi-me/refs/heads/main/feeds/20240501192310.md
image: https://images2.alphacoders.com/479/thumb-350-479565.webp
my_var: VAR from frontmatter
---
Este es un texto con **negrita**.

![Image](https://images2.alphacoders.com/479/thumb-350-479565.webp)

Más info en [mi web](https://ejemplo.com)


Testing template string:

my_var: {{ my_var }}

file_path: {{ file_path }}

file_name: {{ file_name }}

file_dir: {{ file_dir }}

file_ext: {{ file_ext }}

gh_repo_source_base_url: {{ gh_repo_source_base_url }}

gh_owner: {{ gh_owner }}

gh_repo: {{ gh_repo }}

gh_pages_base_url: {{ gh_pages_base_url }}

gh_repo_source_base_url: {{ gh_repo_source_base_url }}
