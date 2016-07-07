---
title: "Jekyll Themes"
headline: "Jekyll Themes"
excerpt: "Open source Jekyll themes for getting you started with hosting a blog on GitHub Pages for free."
modified: 2016-04-15T12:14:45-04:00
image: 
  feature: jekyll-themes-feature.jpg
  thumb: jekyll-themes-thumb-250x250.png
  teaser: jekyll-themes-teaser.png
tags: [Jekyll, web development, open source, GitHub]
work: "Design &amp; Development"
comments: true
---

As I continue to hack away at the design of Made Mistakes and improve on things, I try to release simplified Jekyll starters and themes after each major site revision. Should make development easier for those who sift through [my main repository](https://github.com/mmistakes/made-mistakes-jekyll) trying to strip out the cruft and site specific content to make it their own.

{% include toc.html %}

Below are all of the Jekyll starters I've open sourced thus far. Each "theme" contains all of the `_layouts`, `_includes`, Sass/CSS, JavaScript, and other sample files needed to build a site or blog. There are a lot of similarities between how they work and the file organization --- which should make switching and updating between them easier.

## Setup

The basic setup for each of my theme's is roughly the same:

  1. Fork the Jekyll theme repository you'd like to use.
  2. Clone the repository you just forked and rename it appropriately[^github-pages].
  3. [Install Bundler](http://bundler.io) `gem install bundler` and run `bundle install` to install all dependencies (Jekyll, [Jekyll-Sitemap](https://github.com/jekyll/jekyll-sitemap), [Octopress](https://github.com/octopress/octopress), etc)
  4. Update `_config.yml`, navigation data files (found in `_data`), and replace sample posts and pages with your own.

[^github-pages]: [Follow these steps](http://jekyllrb.com/docs/github-pages/) if you're going to host your site on GitHub Pages to get the repo name and branches setup correctly.

For more specifics, review each themes' documentation by clicking on the **Theme Setup** buttons below.

## Minimal Mistakes

<figure>
  {% picture minimal-mistakes-3-feature.jpg alt="Minimal Mistakes Jekyll theme" %}
  <figcaption>A minimal design to let your content shine.</figcaption>
</figure>

A flexible two-column Jekyll theme with a minimalistic aesthetic.

  - 100% Compatible with GitHub Pages
  - Several layout options (single, archive, splash pages)
  - SEO optimized with support for [Twitter Cards](https://dev.twitter.com/cards/overview) and [Open Graph](http://ogp.me/) data
  - Optional header images, sidebars, table of contents, galleries, related posts, breadcrumb links, and more.
  - Optional comments ([Disqus](https://disqus.com/), [Facebook](https://developers.facebook.com/docs/plugins/comments), Google+, and custom)
  - Optional analytics ([Google Analytics](https://www.google.com/analytics/) and custom)

<div markdown="0">
  <a href="https://github.com/mmistakes/minimal-mistakes/archive/master.zip" class="btn btn--info">Download</a>
  <a href="https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/" class="btn">Setup Guide</a>
  <a href="https://mmistakes.github.io/minimal-mistakes" class="btn">Demo</a>
</div>

## Skinny Bones

<figure>
	{% picture skinny-bones-preview-feature.jpg alt="Skinny Bones Jekyll theme" %}
	<figcaption>Includes a fun off canvas menu</figcaption> 
</figure>

A Jekyll starter used to build the latest incarnation of Made Mistakes.

  * Minimal design meant to be hacked up and customized
  * Built-in support for Sass and data files (requires Jekyll 2.x)
  * Off canvas menu
  * Tile based archives
  * Optional table of contents, share links, Disqus comments modules, and more
  * Plugin free. 100% compatible with GitHub Pages.

<div markdown="0">
	<a href="https://github.com/mmistakes/skinny-bones-jekyll/archive/master.zip" class="btn btn--info">Download</a>
	<a href="https://mmistakes.github.io/skinny-bones-jekyll/getting-started/" class="btn">Setup Guide</a>
  <a href="https://mmistakes.github.io/skinny-bones-jekyll/" class="btn">Demo</a>
</div>

## So Simple

<figure>
	{% picture so-simple-theme-feature-2015.jpg alt="So Simple feature image" %}
	<figcaption>Large images and site logo if that's your thing</figcaption>
</figure>

A simple and clean responsive Jekyll theme for words and large photographs.

  * Minimal design
  * Simple search (searches by post title)
  * Built-in support for Sass and data files (requires Jekyll 2.x)
  * Plugin free. 100% compatible with GitHub Pages.

<div markdown="0">
	<a href="https://github.com/mmistakes/so-simple-theme/archive/master.zip" class="btn btn--info">Download</a>
	<a href="https://mmistakes.github.io/so-simple-theme/theme-setup/" class="btn">Setup Guide</a>
  <a href="https://mmistakes.github.io/so-simple-theme" class="btn">Demo</a>
</div>

## HPSTR

<figure>
	{% picture hpstr-preview-feature-2015.jpg alt="HPSTR feature image" %}
	<figcaption>A traditional blog approach with a modern style</figcaption>
</figure>

A responsive Jekyll blog theme designed to give your site a modern and somewhat cliché feel.

  * Modern, subtle design
  * Animated main menu
  * Built-in support for Sass and data files (requires Jekyll 2.x)
  * Plugin free. 100% compatible with GitHub Pages.

<div markdown="0">
	<a href="https://github.com/mmistakes/hpstr-jekyll-theme/archive/master.zip" class="btn btn--info">Download</a>
	<a href="https://mmistakes.github.io/hpstr-jekyll-theme/theme-setup/" class="btn">Setup Guide</a>
  <a href="https://mmistakes.github.io/hpstr-jekyll-theme/" class="btn">Demo</a>
</div>

## License

These themes are free and open source software, distributed under the [MIT License]({{ site.url }}/LICENSE). Feel free to modify them to suit your needs.
