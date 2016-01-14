# Staticus
A static status page, designed to be blazingly fast and quick enough to update. Running on GitHub pages!

### Installation

```bash
# clone or download the repo
$ bundle install && jekyll serve
```

### Usage

To update the system status page (homepage), just create a new post in `_posts/`.

Staticus uses a couple custom frontmatter fields:
- `system` denotes the top-level message displayed on the homepage. (e.g. _Systems down_)
- `action` denotes the type of status message. (_error_ or _warning_ or _resolve_)

Example frontmatter:

```
---
layout: post
title: First bad things happening
date: 2016-01-01 11:11
system: Systems are down
action: error
---
```
