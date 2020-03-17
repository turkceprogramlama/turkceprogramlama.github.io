---
layout: post
title: "1. Markdown is better than writing HTML"
date: 2016-11-05
---

This page is created using markdown style. It is more intuitive than writing HTML tags. This is better choice for creating a page and modification. Let's have a see some examples:

## Big Title
#### Small Title

### Type of Emphasis

Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~

### Listing

* First ordered list item
* Another item
    * Unordered sub-list. 
* Actual numbers don't matter, just that it's a number
    * Ordered sub-list
        * Sub sub list
            * and more...
* And another item.

### Code Highlighting

```javascript
    var s = "JavaScript syntax highlighting";
    alert(s);
```


{% highlight ruby linenos %}
 def foo
   puts 'foo'
 end
{% endhighlight %}

{% highlight python linenos %}
 s = "Python syntax highlighting"
 print s
{% endhighlight %}

{% highlight html linenos%}
 No language indicated, so no syntax highlighting. 
 But let's throw in a <b>tag</b>.
{% endhighlight %}
 

### Tables

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
{:.mbtablestyle}

### Qutoas
> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote. 


To have more information about writing in markdown style, please have a visit to [this page](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

