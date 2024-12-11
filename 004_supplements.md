---
layout: default
title: Supplements
number: 4
---

# Supplements

{% assign media = site.media_metadata | where_exp: "item", "item.name == 'burned'" %} {% include media.html pages=media %}
{% assign media = site.media_metadata | where_exp: "item", "item.name == 'looking'" %} {% include media.html pages=media %}

# Timeline

<iframe src='https://cdn.knightlab.com/libs/timeline3/latest/embed/index.html?source=1KV2ZkC5afvL5YQ8R8ZY46kVCT93boiaYwolvdMLwk3c&font=Default&lang=en&initial_zoom=2&height=650' width='100%' height='650' webkitallowfullscreen mozallowfullscreen allowfullscreen frameborder='0'></iframe>

# Supplementary Websites

[(https://www.britannica.com/place/Germany/World-War-II)]
[(https://www.nationalww2museum.org/war/articles/how-did-adolf-hitler-happen)]
[(https://www.history.com/topics/world-war-ii/world-war-ii-history)]
[(https://encyclopedia.ushmm.org/content/en/article/world-war-ii-in-europe-1)]

# Supplementary Media Files
{% assign media = site.media_metadata | where_exp: "item", "item.name == 'German Propaganda'" %} {% include media.html pages=media %}
Insert videos or images here.
