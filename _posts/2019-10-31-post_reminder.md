---
layout: post
section-type: post
title: Post reminder
category: misc
tags: [ 'welcome' ]
---

# Post reminder

This article is just a reminder for posts creation on Jekyll and what we can do.

## Article syntax

Standard markdown.

To block the print of an post on the index use the balise defined in [_config.yml](https://github.com/fteychene/blog/blob/master/_config.yml) `post-preview-break`

## Code hihjlight

Syntax highlight is managed
```
{
    "json": true
}
```

## Images

Class usable for img [documentation](https://getbootstrap.com/docs/4.3/content/images/)

Responsive : `![title](/path.jpg){:class="img-fluid"}`

![Fractal responsive](/img/fractal.jpg){:class="img-fluid"}

![Fractal responsive 2](/img/fractal2.jpg){:class="img-fluid"}

Thumbnails (rounded 1px border appearance.) : `![title](/path.jpg){:class="img-thumbnail"}`

![Fractal thumbnails](/img/fractal2.jpg){:class="img-thumbnail"}