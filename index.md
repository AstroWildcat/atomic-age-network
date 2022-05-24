---
title: Atomic Age Network
layout: html
---
# Atomic Age Network
This is a [webring](https://en.wikipedia.org/wiki/Webring) for those on Neocities (or elsewhere!) who have a website centered around vintage aesthetics and/or content. Vintage, in this case, is defined as any era before the year of 1980.

If this sounds like something you're interested in being a part of, [join the webring]({{'join'|relative_url}})!

If the ring is broken, please [submit an error report on GitHub](https://github.com/AstroWildcat/atomic-age-network/issues/new/).

## Members ({{site.data.members.size}}) {#members}
{% for member in site.data.members %}
<p><a href="{{member.url | xml_escape}}" markdown=0>{{member.name | xml_escape | newline_to_br}}</a> ({{member.decades}})</p>{% endfor %}
