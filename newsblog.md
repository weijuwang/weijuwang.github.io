---
layout: page
title: News blog
permalink: /newsblog/
---

*Intermittent, short articles about news in my area*

<ul class="post-list">
    {%- for post in site.posts -%}
    <li>
    {%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
    <span class="post-meta">{{ post.date | date: date_format }}</span>
    <h3>
        <a class="post-link" href="{{ post.url | relative_url }}">
        {{ post.title | escape }}
        </a>
    </h3>
    {%- if site.show_excerpts -%}
        {{ post.excerpt }}
    {%- endif -%}
    </li>
    {%- endfor -%}
</ul>

### Purpose

I write these articles when I feel that there is news of importance to my community that has not been well-covered by other sources, or that I feel I could investigate and cover in more depth. Information is best when it is accessible to everyone; unfortunately, not all information is distributed equally. I feel that, in an increasingly globalized world, we focus too much on inter-community and not *intra*-community. In reality, both are equally important, and so I hope to contribute to the latter by making sure my readers come away highly informed about the topics I cover.

In particular, I like to make use of investigate journalism rather than simple research and compilation of existing news, as it allows me to present information that would otherwise be scattered and difficult for the public to access. Though this often requires use of unofficial sources, this does not necessarily make the information less valuable; for example, if a rumor is spreading but is not being reported, understanding why such a rumor exists in the first place can give important insights into how the topic is perceived in the public eye.