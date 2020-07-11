---
layout: post
title: "Test Post"
author: almatins
categories: daily personal
tags: daily note
date: 2020-07-10 10:07:22
---

<p class="text-xl font-bold">Why Jekyll?</p>

I love simple things, fast loading, easy to write and etc. That's why I choose Jekyll for my blog. I use markdown on my daily basis, so, it feels like I just write my daily notes here.

## H1 Header

_bold_

**bold**

```js
function(stat) {
    console.log(stat);
}
```

This is a demo of all styled elements in Jekyll Now.

[View the markdown used to create this post](https://raw.githubusercontent.com/barryclark/www.jekyllnow.com/gh-pages/_posts/2014-6-19-Markdown-Style-Guide.md).

This is a paragraph, it's surrounded by whitespace. Next up are some headers, they're heavily influenced by GitHub's markdown style.

## Header 2 (H1 is reserved for post titles)

### Header 3

#### Header 4

A link to [Jekyll Now](http://github.com/barryclark/jekyll-now/). A big ass literal link <http://github.com/barryclark/jekyll-now/>

An image, located within /images

![an image alt text]({{ site.baseurl }}/images/jekyll-logo.png "an image title")

- A bulletted list

* alternative syntax 1

- alternative syntax 2
  - an indented list item

1. An
2. ordered
3. list

Inline markup styles:

- _italics_
- **bold**
- `code()`

> Blockquote
>
> > Nested Blockquote

Syntax highlighting can be used by wrapping your code in a liquid tag like so:

{{ "{% highlight javascript " }}%}  
/_ Some pointless Javascript _/
var rawr = ["r", "a", "w", "r"];
{{ "{% endhighlight " }}%}

creates...

{% highlight javascript %}
/_ Some pointless Javascript _/
var rawr = ["r", "a", "w", "r"];
{% endhighlight %}

Use two trailing spaces  
on the right  
to create linebreak tags
