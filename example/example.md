---
title: An Astronomy and astrophysics (A\&A) Template
description: An A&A template suitable for journal submissions
short_title: A&A Template
date: 2025-03-21
authors:
    - name: Morgan Fouesneau
      orcid: 0000-0001-9256-5516
      affiliation: mpia
      corresponding: true
      email: fouesneau@mpia.de
    - name: Others
affiliations:
    - id: mpia
      institution: Max Planck Institute for Astronomy, Königstuhl 17, 69117 Heidelberg, Germany 
      ror: https://ror.org/01vhnrs90
      isni: 0000 0004 0491 677X
      department: Data Science Department
      address: Königstuhl 17
      city: Heidelberg
      country: Germany
      postal_code: 69117
abstract: >
    Morbi eu neque et enim euismod cursus sit amet sit amet elit: Fusce eget neque placerat, vehicula dui id, placerat velit. Proin pellentesque fermentum sollicitudin. Etiam egestas sed dolor rutrum faucibus. Nunc ac viverra justo. Vestibulum eget erat pretium sem blandit placerat ullamcorper nec velit. Aliquam orci enim, luctus tempor euismod a, aliquam in ex. Morbi ultrices sapien quis neque sagittis condimentum.
options:
keywords:
    - tutorial
    - python
    - seismic
    - attributes
exports:
  - format: pdf
    template: aa
    engine: pdflatex
    output: example.pdf
    line_numbers: true
    options:
       class_options: longauth
  - format: tex
    template: aa
    line_numbers: true
    options:
       class_options: longauth
bibliography: example.bib
---

# Introduction

Nam dui ligula, fringilla a, euismod sodales, sollicitudin vel,
wisi. Morbi auctor lorem non justo. Nam lacus libero, pretium
at, lobortis vitae, ultricies et, tellus. Donec aliquet, tortor sed
accumsan bibendum, erat ligula aliquet magna, vitae ornare
odio metus a mi. Morbi ac orci et nisl hendrerit mollis. Sus-
pendisse ut massa. Cras nec ante. Pellentesque a nulla. Cum
sociis natoque penatibus et magnis dis parturient montes, nasce-
tur ridiculus mus. Aliquam tincidunt urna. Nulla ullamcorper
vestibulum turpis. Pellentesque cursus luctus mauris.

Nulla malesuada porttitor diam. Donec felis erat, congue non,
volutpat at, tincidunt tristique, libero. Vivamus viverra fermen-
tum felis. Donec nonummy pellentesque ante. Phasellus adip-
iscing semper elit. Proin fermentum massa ac quam. Sed diam
turpis, molestie vitae, placerat a, molestie nec, leo. Maecenas
lacinia. Nam ipsum ligula, eleifend at, accumsan nec, suscipit
a, ipsum. Morbi blandit ligula feugiat magna. Nunc eleifend
consequat lorem. Sed lacinia nulla vitae enim. Pellentesque tin-
cidunt purus vel magna. Integer non enim. Praesent euismod
nunc eu purus. Donec bibendum quam in tellus. Nullam cursus
pulvinar lectus. Donec et mi. Nam vulputate metus eu enim.
Vestibulum pellentesque felis eu massa.

(sec:headings)=
# Headings: first level

Sed commodo posuere pede. Mauris ut est. Ut quis purus. Sed
ac odio. Sed vehicula hendrerit sem. Duis non odio. Morbi ut
dui. Sed accumsan risus eget odio. In hac habitasse platea dic-
tumst. Pellentesque non elit. Fusce sed justo eu urna porta tin-
cidunt. Mauris felis odio, sollicitudin sed, volutpat a, ornare ac,
erat. Morbi quis dolor. Donec pellentesque, erat ac sagittis sem-
per, nunc dui lobortis purus, quis congue purus metus ultricies
tellus. Proin et quam. Class aptent taciti sociosqu ad litora
torquent per conubia nostra, per inceptos hymenaeos. Praesent
sapien turpis, fermentum vel, eleifend faucibus, vehicula eu, la-
cus.

See Section {numref}`sec:headings`.

## Headings: second level

Fusce mauris. Vestibulum luctus nibh at lectus. Sed bibendum,
nulla a faucibus semper, leo velit ultricies tellus, ac venenatis
arcu wisi vel nisl. Vestibulum diam. Aliquam pellentesque, au-
gue quis sagittis posuere, turpis lacus congue quam, in hendrerit
risus eros eget felis. Maecenas eget erat in sapien mattis port-
titor. Vestibulum porttitor. Nulla facilisi. Sed a turpis eu lacus
commodo facilisis. Morbi fringilla, wisi in dignissim interdum,
justo lectus sagittis dui, et vehicula libero dui cursus dui. Mau-
ris tempor ligula sed lacus. Duis cursus enim ut augue. Cras
ac magna. Cras nulla. Nulla egestas. Curabitur a leo. Quisque
egestas wisi eget nunc. Nam feugiat lacus vel est. Curabitur
consectetuer.

$$
\xi _{ij}(t)= {\frac {\alpha _{i}(t)a^{w_t}_{ij}\beta _{j}(t+1)b^{v_{t+1}}_{j}(y_{t+1})}{\sum _{i=1}^{N} \sum _{j=1}^{N} \alpha _{i}(t)a^{w_t}_{ij}\beta _{j}(t+1)b^{v_{t+1}}_{j}(y_{t+1})}}
$$

### Headings: third level
Suspendisse vel felis. Ut lorem lorem, interdum eu, tincidunt sit
amet, laoreet vitae, arcu. Aenean faucibus pede eu ante. Prae-
sent enim elit, rutrum at, molestie non, nonummy vel, nisl. Ut
lectus eros, malesuada sit amet, fermentum eu, sodales cursus,
magna. Donec eu purus. Quisque vehicula, urna sed ultricies
auctor, pede lorem egestas dui, et convallis elit erat sed nulla.
Donec luctus. Curabitur et nunc. Aliquam dolor odio, com-
modo pretium, ultricies non, pharetra in, velit. Integer arcu est,
nonummy in, fermentum faucibus, egestas vel, odio.

(sec:others)=
## Examples of citations, figures, tables, references

Pellentesque habitant morbi tristique senectus et netus et male-
suada fames ac turpis egestas. Donec odio elit, dictum in, hen-
drerit sit amet, egestas sed, leo. Praesent feugiat sapien aliquet
odio. Integer vitae justo. Aliquam vestibulum fringilla lorem.
Sed neque lectus, consectetuer at, consectetuer sed, eleifend ac,
lectus. Nulla facilisi. Pellentesque eget lectus. Proin eu metus.
Sed porttitor. In hac habitasse platea dictumst. Suspendisse
eu lectus. Ut mi mi, lacinia sit amet, placerat et, mollis vitae,
dui. Sed ante tellus, tristique ut, iaculis eu, malesuada ac, dui.
Mauris nibh leo, facilisis non, adipiscing quis, ultrices a, dui.

{cite:t}`kour2014real, kour2014fast`  {cite:p}`hadash2018estimate`.

## Figures


See Figure {ref}`fig-fig1`. 
Here is how you add footnotes[^bignote]. Sed feugiat. Cum
sociis natoque penatibus et magnis dis parturient montes, nasce-
tur ridiculus mus. Ut pellentesque augue sed urna. Vestibulum
diam eros, fringilla et, consectetuer eu, nonummy id, sapien.
Nullam at lectus. In sagittis ultrices mauris. Curabitur male-
suada erat sit amet massa. Fusce blandit. Aliquam erat volutpat.
Aliquam euismod. Aenean vel lectus. Nunc imperdiet justo nec
dolor.

^bignote: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.


```{figure} https://www.aanda.org/templates/template1/images/aa/logo_aa.svg
:label: fig-fig1

This is the figure caption!
Something! A legend!?
```