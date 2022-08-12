{% capture my_include %}{% include index.md %}{% endcapture %}
{{ my_include | markdownify }}
