---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

<!-- I am a motivated self-starter. I believe in doing things the right way. I believe that you should never stop learning. Automated tests allow you to refactor your code without fear of regressions. Stack Overflow is very handy, but documentation is a programmer's best friend.  -->

Following are some quotes from current and former colleagues of mine:

<div style="margin-left: 5%; margin-right: 5%">
{% for quote in site.data.quotes %}
  <p><q>{{ quote.text }}</q></p>
  <footer style="margin-left: 5%"><p>&mdash; {{ quote.author }}</p></footer>
{% endfor %}
</div>
