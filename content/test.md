---
title: "Maries me-sida"
views:
    byline:
        region: main
        template: anax/v2/block/default
        sort: 2
        data:
            meta:
                type: single
                route: block/byline
---
Min testsida för Markdown
=========================

Rubriker
H1      {#header1}
===
eller
# H1
## H2
### H3
#### H4
##### H5
###### H6

#### Listor
* Unordered list can use asterisks
- Or minuses
+ Or pluses

1. First ordered list item
2. Another item
⋅⋅* Unordered sub-list.

#### Blockquotes
Om jag har lite kod att visa:
> kodrad 1
> kodrad 2
> kodrad 3

#### Länkar
Snyggt med titel:
[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[Link back to header 1](#header1)

#### Tabeller
Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

#### Youtube
Jag som hoppar längd på KA 2-spelen 2015:
[![Marie hoppar längd](https://www.youtube.com/watch?v=ABDWzlnop88&list=PLnhcceG_8gZB2CzyAzI9FkDAbuPrk244g&index=88)](https://www.youtube.com/watch?v=ABDWzlnop88&list=PLnhcceG_8gZB2CzyAzI9FkDAbuPrk244g&index=88)

#### Markdown inuti html
<div markdown="1">
This is *true* markdown text.
</div>

#### Förkortningar
The HTML specification
is maintained by the W3C.
*[HTML]: Hyper Text Markup Language
