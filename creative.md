---
title: Applied Work
layout: base
date: 2025-09-30
homepage: TRUE
position: 3
summary: This page highlights visual and applied work, including maps, spatial analyses, and planning outputs that translate data into practical, real-world insights.
thumbnail: assets/images/Group.jpeg
---
{% include images/jumbotron.html
  image-path="/assets/images/grad1.jpeg"
  height="50vh"
  box-align="left"
  title="Lifestyle"
  text="What makes you happy doesn’t need to make sense to anyone else"
%}
---
To rename this page, change the `title` field in the front matter above and update the corresponding entry in `_data/nav-top.yml`.

---

## Memories That Matter
{% assign images =
"/scrollstories/forest/images/beach hands.jpeg,
/scrollstories/forest/images/beach group.jpeg,
/scrollstories/forest/images/whiteshirts.JPG" | split: ','
%}

{% assign headers =
"A Photo Title,,
No caption here" | split: ','
%}

{% assign captions =
"It's useful to have informative captions|
This image has a caption, but no title|
" | split: '|'
%}

{% include images/carousel.html
  width="80%"
  class="center"
  images=images
  headers=headers
  captions=captions
%}

Write a paragraph or two introducing what this page is about. This is a good page to experiment with Xanthan's image components — `figure` (standalone, left/right/center) and `figure-wrap` (text wraps around the image) both work well for portfolio-style pages with lots of visual content.

Replace this text with your own. And if this page doesn't fit your portfolio at all, you can delete this file and remove its entry from `_data/nav-top.yml`.

---

## Projects or Works

### Item Title
Description of this piece, project, or publication. Add an image, a link, a date — whatever context helps a reader understand it.

### Item Title
Description. Keep the format consistent across entries.
