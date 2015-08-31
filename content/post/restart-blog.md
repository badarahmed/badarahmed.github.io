+++
categories = []
date = "2015-08-30T14:51:04-07:00"
description = ""
keywords = []
title = "Restart blogging with Hugo"

+++

Starting new blog again! I've attempted to write a bit before with a [Jekyll](http://jekyllrb.com/) & [Ghost](https://ghost.org/) setup.


Starting over again with **[Hugo](http://gohugo.io)**; a Go based static blogging platform. Love the speed & simplicity compared to Jekyll.
Nice work by [@spf13](https://twitter.com/spf13).

Now if I can get myself to start writing regularly! 😏


## Hugo Quickstart

The Hugo quickstart ⚡ guide at http://gohugo.io/overview/quickstart/ covers it well.

For Mac OSX `brew` makes the install a breeze.

```
brew install gohugo
```

That's it! No dependencies to manage, no `rake`, no managing versions of `ruby` or `node`. Hugo is a static binary! That's as sweet as a wrapped piece of sugar candy! 🍬

For a glimpse this is all it took to get a hugo blog up & running locally:
```
# Bootstrap Hugo Blog
$ hugo new site /path/to/site
```

```
# Add new Page
$ hugo new about.md
```

```
# Get all the themes to play with!
$ git clone --recursive https://github.com/spf13/hugoThemes themes
```

```
# Run Hugo Server
$ hugo server --theme=hyde --buildDrafts
```

Add `--watch` flag to to `hugo server` and you get a fast live-reloading page that reacts to each file save on content. Pretty sweet! 😍

Offcourse you don't need to use `hugo server`. Its great for local dev. Could be used for prod if you want to host your blog on your own server or VPS. For simpler options go with Github Pages or S3. I'm going with Github Pages for the moment for free blog hosting! 💵

## Downsides with Hugo

I've mostly talked about the positives of Hugo here. One downside of Hugo compared to more mature blog platforms is the lack of themes. The curated list of themes at https://github.com/spf13/hugoThemes are a bit lacking in design. Will take a better look at them but at first glance neither of them look well polished.

The good news is that there is a sizable community of Hugo users/fans. So this should not be an impediment for long. Or you can port some existing Jekyll theme of choice to Hugo, which doesn't seem too bad but a significant time investment for sure.


-- [Badar Ahmed](/about/)

<hr/>

{{< figure src="/media/hugo.png" link="http://gohugo.io" title="Hugo: Go based Static Site Generator" >}}
