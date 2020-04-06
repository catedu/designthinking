# Créditos

## Autoría

Elena Bernia Armengod

{% for item in book.collaborators %}

{{item.name}}: {{item.edited}}

{% endfor %}

{% GitHubContributors %}
{% endGitHubContributors %}

{% include "git+https://github.com/catedu/faq-aularagon.git/imagenes_creditos.md" %}

