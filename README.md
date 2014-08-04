# Lynx - Ghost Theme

Lynx is my personal [Ghost](http://github.com/tryghost/ghost/)-Theme.  
It's built upon the default Ghost-Theme [Casper](https://github.com/TryGhost/Casper).

![](http://blog.wnx.ch/content/images/2014/Mar/Bildschirmfoto_2014_03_16_um_14_49_17.png)

## Features

- DISQUS Support
- Google Analytics
- Font Awesome Support
- Header & Footer Navigation
- SASS (incl. [Burbon](http://bourbon.io))

## Installation
**Please note, you have to restart your Ghost Installation to see your changes!**

### Disqus
Go to `post.hbs` and replace `var disqus_shortname = 'wnxch';` with your own Disqus-Shortname.

### Google Analytics
Open `default.hbs` and insert your Google-Analytics Snippet near `<!-- Google Analytics -->`

### Navigation
Open `partials/footer-nav.hbs` and `partials/header-nav.hbs`. Just add more anchor-tags. **Notice: On mobile, your header navigation will be fucked up if you add too much links. (Will be fixed in future release).**

### Favicon
Place your custom favicon under `assets/favicon.ico` or edit in `default.hbs`.

## Contribution
If you find a bug or you have a feature request, please create an issue.


## Roadmap

- Navigation out of static pages
- Add Gruntfile for easier development


## Copyright & License

Copyright (C) 2014 - Released under the MIT License.
