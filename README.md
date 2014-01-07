# Taunt

A fork of [Heckle][1], which is a minimal [Jekyll][2] clone in node.js.

## Why?

> I like the approach to managing a site taken by Jekyll. A lot.

> I don't like Ruby, and I don't like strict logic-less templates.
Jekyll is Ruby with Liquid as the templating engine.

> Heckle is JavaScript with Mold (programmable template extravaganza) as
the templating engine.

## Why Taunt?
1. Because it is a synonym for Heckle. 
2. I had difficulties using [Octopress][4] and [Jekyll][2] for various reasons, all
of which have nothing to do with the quality of these tools but more with
my personal workflow and inability/unwillingness to learn Ruby to deal 
with issues that arose. So I ended up looking for something similar written
in Javascript which is how I got to Heckle. I think there are a few things
that could be improved, such as supporting blogs with multiple languages and
I will work on them as time permits.

## Setup

> Don't use Heckle at this point if you want something stable and
finished. It's a work in progress, and may be radically changed or
pitilessly abandoned at any time.

> If that didn't scare you off, you should be able to get dependencies
with `npm install`.

> When the dependencies have been installed, you should be able to
change to the directory that contains your blog files, and run...

>    nodejs /path/to/heckle/heckle.js

> It parses a `_config.yml` and treats `_posts`, `_layouts`, and
`_includes` dirs much like [Jekyll][2]. Your templates should be in
[Mold][3] syntax and read `$arg` rather than `post` or `page` to get
context information.

[1]: https://github.com/marijnh/heckle
[2]: http://jekyllrb.com/
[3]: http://marijnhaverbeke.nl/mold/
[4]: http://octopress.org/