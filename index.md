---
layout: default
title: Home
---

Meet [Purity][purity], a clean, blazing-fast, highly configurable theme for
[Jekyll][jekyll].

Why [Purity][purity]?

<div class='pure-g'>
  <div class='pure-u-1 pure-u-sm-1-3 text-align-right-small'>
    {% include utils/font-awesome-stack.html below_text='<b>JS</b>' above='fa-ban site-color-faded-accent' %} No JavaScript
  </div>
  <div class='pure-u-1 pure-u-sm-1-3 text-align-center'>
    {% include utils/font-awesome-stack.html reverse=true below='fa-circle-thin' above='fa-css3' %} 100% Pure CSS
  </div>
  <div class='pure-u-1 pure-u-sm-1-3 text-align-left-small'>
    {% include utils/font-awesome-stack.html reverse=true below='fa-circle site-color-faded-hyperlink' above='fa-bolt fa-inverse' %} Super-light!
  </div>
</div>

Still not convinced:

- Solid, feature-rich CSS stack:
  - [normalize.css][normalize] base
  - [Pure][pure]'s grid system
  - Awesomified by [FontAwesome][fontawesome]
  - CSS-only tooltips, like [this](){: .tooltip data-tooltip='This is super-cool!'}.
  - Oh, and [Purity][purity]'s CSS is 100% [SASS][sass]y
- Configurable to the core: ([`_config.yml`][config_yml])
  - Toggle header, footer, sidebar
  - Flip sidebar just by tweaking one key
  - Navigation menu using absolute/relative links
  - User-specified fonts pulled from [Google Fonts][google-fonts]
- Mobile-friendly responsive design
- No third-party Jekyll plugins
  - Push directly to [GitHub Pages][github-pages]

[config_yml]: https://github.com/SaswatPadhi/purity-jekyll-theme/blob/master/_config.yml
[fontawesome]: http://fontawesome.io/
[github-pages]: https://pages.github.com/
[google-fonts]: https://www.google.com/fonts
[jekyll]: https://jekyllrb.com/
[normalize]: https://necolas.github.io/normalize.css/
[purity]: {{ site.url }}
[pure]: http://purecss.io/
[sass]: http://sass-lang.com/
