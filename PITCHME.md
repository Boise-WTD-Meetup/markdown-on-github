# Getting started with ![Markdown](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/100px-Markdown-mark.svg.png) & ![GitHub](https://upload.wikimedia.org/wikipedia/commons/thumb/9/91/Octicons-mark-github.svg/100px-Octicons-mark-github.svg.png)
##### 2017-09-26 Boise WriteTheDocs Meetup
##### Bryan Davis <bd808@bd808.com>

---

What is Markdown?
-----------------

> Markdown is a lightweight markup language with plain text formatting syntax.
> It is designed so that it can be converted to HTML and many other formats
> using a tool by the same name.
>
> <small>— ["Markdown"](https://en.wikipedia.org/w/index.php?title=Markdown&oldid=801461295) Wikipedia: The Free Encyclopedia. Wikimedia Foundation, Inc. 19 September 2017. Web. 23 September 2017.</small>

---

A short primer
--------------

---

Text
----

Paragraphs are just plain text in your source document.
You can use newlines to hard wrap the source for easier reading.

If you need a `<br>` in the output,  
end the source line with 2 or more spaces
*or* just use a literal `<br>` in the source.

Note:
You can mix in raw HTML markup at any time with most Markdown translators. The
HTML allowed may be limited depending on the translator. This is especially
true when Markdown is being used as a way to input rich text in websites.

---

Headings
------

```
H1 Heading
==========

H2 Heading
----------

# H1 Heading
## H2 Heading
### H3 Heading
#### H4 Heading
##### H5 Heading
###### H6 Heading
```

---

Emphasis, links, & images
-------------------------

* _italic_ - `_italic_` or `*italic*`
* **bold** - `**bold**` or `__bold__`
* `code` - `` `code` ``
* [link](https://example.com/) - ``[link](url to link to)``
* ![Unicorns!](https://upload.wikimedia.org/wikipedia/commons/thumb/5/55/Emoji_u1f984.svg/32px-Emoji_u1f984.svg.png) - `![alt text](url of image)`

---

Lists
-----

Unordered lists use `*`, `+`, or `-` as list markers:
```
* item 1
* item 2
* item 3
```

Ordered lists use numbers followed by periods:
```
1. item 1
2. item 2
3. item 3
```

Note:
The actual number used does not matter, but common convention is to use
numbering that makes the source document easily readable.

---

Standards
---------

* [Markdown 1.0.1](https://daringfireball.net/projects/markdown/)
* [CommonMark](http://commonmark.org/)
* [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/#GitHub-flavored-markdown)

---

Markdown & GitHub
-----------------

* [Gists](https://gist.github.com/)
* Comments on Issues and Pull Requests
* Files with `.md` or `.markdown` extensions
* [GitHub Pages](https://pages.github.com/)

---

Static site generators
----------------------

* [Jekyll](https://github.com/jekyll/jekyll)
* [Pelican](http://docs.getpelican.com/en/stable/)
* [Hugo](http://gohugo.io/)
* [Many more...](https://www.staticgen.com/)

---


Credits
-------

* Except where otherwise noted - Copyright (c) 2017 Bryan Davis and contributors, [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/)
* [Markdown mark](https://github.com/dcurtis/markdown-mark) - Copyright (c) 2017 Dustin Curtis, [CC0](https://github.com/dcurtis/markdown-mark/blob/f2e4b0b14b2ebb0465d88e8a26c9d65de89190a3/LICENSE)
* [GitHub logo](https://github.com/primer/octicons) - (c) 2012-2016 GitHub, Inc., [SIL OFL 1.1](http://scripts.sil.org/OFL)
* [Unicorn face emoji](https://github.com/googlei18n/noto-emoji/blob/f2a4f72/svg/emoji_u1f984.svg) - (c) 2017 Google Inc., [Apache2](https://github.com/googlei18n/noto-emoji/blob/f7abf9645ce10d923fb5e8bccf62e0ffae47b999/LICENSE)
* [GitPitch](https://gitpitch.com/) - Copyright (c) 2016 David Russell,
  [MIT License](https://github.com/gitpitch/gitpitch/blob/7c4efa5ab0fa5808d81000d3f167a811586b2685/LICENSE.txt)
