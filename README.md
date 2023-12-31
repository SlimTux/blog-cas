# blog-cas

Lightweight and minimal blog theme for the [Zola](https://www.getzola.org/)
static site generator.

Live demo is available here:
[https://blog.slimtux.xyz](https://blog.slimtux.xyz)

![](screen_index.png)

![](screen_post.png)

## Installation

[Theme documentation](https://www.getzola.org/documentation/themes/installing-and-using-themes/)

Clone this repository into your site's `themes` directory or add it as a
submodule:

```bash
# zola init "NAME"
$ git clone https://git.sr.ht/~savoy/tilde name
# sass [N]
$ zola serve
# Add as a submodule
$ git submodule add https://git.sr.ht/~savoy/tilde themes/tilde
```

## Configuration

This theme offers the following config options:

```toml
# The URL the site will be built for
base_url = "https://blog.slimtux.xyz"

# The site title and description; used in feeds by default.
title = "Cas's Blog"
description = "This blog was createad to fulfil some scholl's (IB CAS)mandatory stuff."

# The default language; used in feeds.
default_language = "en"

# Whether to automatically compile all Sass files in the sass directory
compile_sass = false

# Whether to build a search index to be used later on by a JavaScript library
build_search_index = false

# When set to "true", a feed is automatically generated.
generate_feed = true
# The filename to use for the feed. Used as the template filename, too.
# Defaults to "atom.xml", which has a built-in template that renders an Atom 1.0 feed.
# There is also a built-in template "rss.xml" that renders an RSS 2.0 feed.
# The default author for pages
author = "Slimtux"


# The taxonomies to be rendered for the site and their configuration of the default languages
# Example:
     taxonomies = [
       {name = "tags", feed = true}, # each tag will have its own feed
       {name = "tags"}, # you can have taxonomies with the same name in multiple languages
       {name = "categories", paginate_by = 5},  # 5 items per page for a term
       {name = "authors"}, # Basic definition: no feed or pagination
     ]

[markdown]
# Whether to do syntax highlighting
# Theme can be customised by setting the `highlight_theme` variable to a theme supported by Zola
highlight_code = true

# The theme to use for code highlighting.
# See below for list of allowed values.
#######################highlight_theme = "base16-ocean-dark"
highlight_theme = "dracula"

# When set to "true", emoji aliases translated to their corresponding
# Unicode emoji equivalent in the rendered Markdown files. (e.g.: :smile: => 😄)
render_emoji = true

# Whether smart punctuation is enabled (changing quotes, dashes, dots in their typographic form)
# For example, `...` into `…`, `"quote"` into `“curly”` etc
smart_punctuation = true

[extra]

homepage = "" # author homepage
subtitle = "" # blog subtitle
git_source = "" # blog source code
author = "" # author name
email = "" # author email
license = "" # blog license

# Put all your custom variables here
katex_enable = true
katex_auto_render = true
```
