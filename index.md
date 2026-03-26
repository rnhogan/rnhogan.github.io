---
title: Rachel N. Hogan
layout: nav-profile
date: 2024-12-02
---


# Rachel N. Hogan

I am a librarian interested in academic librarianship, information literacy, digital humanities, arts-based research, and arthurian literature.
---
{% include images/figure.html
  class="center"
  width="100%"
  caption="World Cloud for my DH work"
  alt-text="A word cloud of words associated with my digital humanities work at William & Mary"
  image-path="/assets/images/dhcloud.png"
%}

{% assign essays = site.pages | where: "homepage", true %}
{% include nav/card-stack.html cards = essays %}