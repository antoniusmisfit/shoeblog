# shoeblog
Shoeblog is a tiny static HTML5 blogging engine written for Linux systems with a Busybox environment.

# Installation

You can simply drop the "shoeblog" shell script anywhere in your system's $PATH, preferably in /usr/local/bin.

Basic usage
-----------

To automatically generate an empty blog within the current directory, invoke `shoeblog -config` and edit the config file that will appear in vi. Change the "webroot" setting to either "."(for a local blog) or the web address where the blog will be hosted.

To create your first blog post, invoke `shoeblog -edit postname` and edit the entry in vim. See `shoeblog -help` for details on blog post format.

To delete a blog post, invoke `shoeblog -delete postname`, and shoeblog will delete the corresponding .raw files.

# HTMLwrap-bb

HTMLwrap-bb is a stripped down Busybox compatible version of HTMLwrap.sh(found [here](https://github.com/antoniusmisfit/omicron)).

TODO
----

* Emulate fmt command to properly format blog posts on index.html and format text files for HTMLwrap-bb.
