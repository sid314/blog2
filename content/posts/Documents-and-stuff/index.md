+++
title = "Documents and Stuff"
date = "2025-03-02T23:36:27+05:30"
author = ""
authorTwitter = "" #do not include @
cover = ""
coverCaption = ""
tags = ["FOSS", "Terminal"]
keywords = []
description = ""
showFullContent = false
readingTime = true
hideComments = false
color = "" #color from the theme settings
+++

## Nerdy Ways to Write Documents and Stuff

This article presents some interesting ways
to prepare notes, documents , presentations
etc.

### But why tho?

Cuz its fun , and besides you'll look cool (not a guarantee).

### The simplest of the bunch: Markdown

If you just want to write text and don't need any complex formatting,
then Markdown is the best tool for the job ( ok, I know
about Org mode but that's a story for another day).

You dont need a fancy editor to start writing markdown, although one
that also renders markdown is a nice to have. Neovim, by its own is a good
option , but it can become a fantastic option with a few plugins.

{{< figure src="a.png" alt="Screenshot of a markdown file with ideas for this blog opened in neovim" position="center" style="border-radius: 12px;" caption="Ideas for this blog" >}}

I use [Lazyvim](https://www.lazyvim.org/)
with the [Markview](https://github.com/OXY2DEV/markview.nvim) plugin to
write my notes and this blog.

### Never deal with Word again: LaTeX

Word processors can be a real pain to use if you need complex formatting. You just
tried to resize a picture and your precarious alignment which you already
poured hours into gets messed up. That's where LaTeX comes in.
You can prepare reallly complicated documents by writing all of it in plain text.

And while that in itself is quite nerdy, you can take it to the next level by
using Neovim (again) to write your documents. Once again I will be using
my Neovim config, this time with [TeXpresso](https://github.com/let-def/texpresso)
which also comes with a [plugin](https://github.com/let-def/texpresso.vim).

{{< figure src="b.png" alt="Screenshot of a LaTeX file with chemistry text opened in neovim and rendered LaTeX window besides it" position="center" style="border-radius: 12px;" caption="Did I mention it updates as you write?" >}}

### What about presentations?: Presenterm

This one surprised me too. Why? Because [Presenterm](https://github.com/mfontanini/presenterm/)
allows you to display presentations
from your terminal. You simply write your presentations in a markdown file and present them.
So simple,yet so powerful. It also has tons of features LaTeX support
, code running, themes and a lot more.
Here is a very brief demo of what you can do with this tool
and some old-fashioned markdown.

{{< figure src="presenterm.gif" alt="GIF of a presenterm slideshow" position="center" style="border-radius: 12px;">}}

#### Some shoutouts to other presentation stuff

- [Pysentation](https://github.com/mimseyedi/pysentation)
- [Slides](https://github.com/maaslalani/slides)
- [Spiel](https://github.com/JoshKarpel/spiel)

## Conclusion

There is some stuff I could not include in this post
so there probably will be a part 2 to this post.

### Shoutouts

Some resources I used to find these tools

- [Terminal Trove](https://terminaltrove.com/)
- [r/Commandline](https://www.reddit.com/r/commandline/)
- [r/LaTeX](https://www.reddit.com/r/LaTeX/)
