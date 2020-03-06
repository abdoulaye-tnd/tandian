---
layout: page
title: Notes
description: >
  **Hydejack** is a Jekyll theme with JavaScript powers, combining the best of static sites and modern web apps.
  It features a suite of JavaScript that makes the page feel like an app, without sacrificing backwards-compatibility,
  page-load speed or SEO.
menu: true
order: 1
---

Here you can find a list of books that I have read and the notes that I have taken during the process. They are meant to be concise and to highlight the in my opinion most important aspects of the book. But, they may not reflect my own opinion.





## Features
Both versions include these features:

* Full in-app page loading, powered by [hy-push-state]{:.external}
* A customizable sidebar that turns into a drawer menu on mobile, powered by [hy-drawer]{:.external}
* Advanced FLIP animations, inspired by Material Design
* Good [Google PageSpeed Score][gpss][^4]
* Higher *perceived speed* thanks to content pre-fetching
* [Syntax highlighting](#syntax-highlighting), powered by [Rouge]
* [LaTeX math blocks](#latex-math-blocks), powered by [KaTeX]
* Change the wording of built-in strings and possibly translate in other languages
* Support for categories and tags
* Built-in icons for many social networks
* Simple and semantic HTML — can be viewed even with text-based browsers
* Author section below each article and support for multiple authors
* Progressive enhancement — sacrifice features, not content
* Google Analytics and Google Fonts support
* Disqus comments
* Print layout — Used to render Hydejack's [PDF documentation][pdf]
* Blog layout via `jekyll-paginate` (optional)
* SEO meta tags via `jekyll-seo-tag` (optional)
* Github avatars via `jekyll-avatar` (optional)
* Gist support via `jekyll-gist` (optional)

[^4]: Actual page load speed depends on your hosting provider, resolution of embedded images and usage of 3rd party plugins.  

### Syntax Highlighting
Syntax highlighting powered by [Rouge].

~~~ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
~~~



## Versions
### Free Version
The *free version* features the design and tech of **Hydejack**, but only supports basic blogging.

[**Download**][kit]



[download]: https://qwtel.com/download/
[welcome]: https://qwtel.com/hydejack/
[forms]: https://qwtel.com/hydejack/forms-by-example/

[feat]: #features
[news]: #newsletter-subscription-box
[syntax]: #syntax-highlighting
[latex]: #latex-math-blocks

[license]: LICENSE.md
[pro]: licenses/PRO.md
[docs]: docs/7.5.0/index.md

[kit]: https://github.com/qwtel/hydejack-starter-kit/archive/v7.5.0.zip
[src]: https://github.com/qwtel/hydejack
[gem]: https://rubygems.org/gems/jekyll-theme-hydejack
[buy]: https://app.simplegoods.co/i/AQTTVBOE

[gpss]: https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2Fqwtel.com%2Fhydejack%2F
[wiki]: https://github.com/qwtel/hydejack/blob/master/docs/7.5.0/index.md
[pdf]: https://github.com/qwtel/hydejack/releases/download/v7.5.0/Documentation._.Hydejack.pdf
[hy-push-state]: https://qwtel.com/hy-push-state/
[hy-drawer]: https://qwtel.com/hy-drawer/
[rouge]: http://rouge.jneen.net
[katex]: https://khan.github.io/KaTeX/
[tinyletter]: https://tinyletter.com/

*[FLIP]: First-Last-Invert-Play. A coding technique to achieve performant page transition animations.
