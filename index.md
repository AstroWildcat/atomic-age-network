---
title: The Vintage Net Index
layout: html
---
::: .box
# The Vintage Net
This is a [webring](https://en.wikipedia.org/wiki/Webring) for those on Neocities (or elsewhere!) who have a website centered around vintage aesthetics and/or content. 
Vintage, in this case, is defined as anything before the year of 2000. However, we do prefer websites centered around content or aesthetics that is pre-1980s.
If this sounds like something you're interested in being a part of, [join the webring]({{'join'|relative_url}})!

If the ring is broken, please [submit an error report on GitHub](https://github.com/AstroWildcat/thevintagenet/issues/new/).

## Members ({{site.data.members.size}}) {#members}
{% for member in site.data.members %}
- <a href="{{member.url | xml_escape}}" markdown=0>{{member.name | xml_escape | newline_to_br}}</a>{% endfor %}
:::
