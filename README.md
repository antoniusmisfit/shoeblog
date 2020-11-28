# shoeblog
Shoeblog is a tiny static HTML5 blogging engine written in bash.

# Installation

You can simply drop the "shoeblog" shell script anywhere in your system's $PATH, preferably in /usr/local/bin.

# Features

Shoeblog features simple configuration, zero dependencies other than Busybox or bash, output suitable for text-based web browsers, and social media sharing for posts, CSS themes, command output capture to blog posts, and import of plain text files into blog posts.

Basic usage
-----------

To automatically generate an empty blog within the current directory, invoke `shoeblog -config` and enter the configuration settings at the prompts.

To create your first blog post, invoke `shoeblog -edit postname` and edit the entry in vi. See `shoeblog -help` for details on blog post format.

To delete a blog post, invoke `shoeblog -delete postname`, and shoeblog will update the blog accordingly.

# HTMLwrap-bb

HTMLwrap-bb is a stripped down Busybox compatible version of HTMLwrap.sh(found [here](https://github.com/antoniusmisfit/omicron)).
