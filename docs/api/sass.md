---
title: Sass
layout: docs
permalink: docs/api/sass/
group: "api"
---

### Sass

Jekyllize utilizes scss for it's css, which jekyll will automatically convert and minify. All the styles related to materialize and this theme get put into main.css (generated from main.scss). In order to change the color scheme of this theme simply change these sass vars.

{% highlight sass %}

$primary : $indigo;
$accent: $pink;

{% endhighlight %}

The available colors can be found [here](http://materializecss.com/color.html), although `$black` and `$white` can't be used

#### Modifying main.scss