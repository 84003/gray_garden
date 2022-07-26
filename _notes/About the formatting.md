---
title: 
tag: 🌳
category: Configuration
---

##### Metadata

Each entry title is followed by metadata (if not null), taken from the [Jekyll front matter](https://jekyllrb.com/docs/front-matter/):

- Status: 🌱 or 🌿 or 🌳
- Updated: Month Day Year
- Category: Subject, specific topic, content type.

**Status**

- 🌱 (seedling) means the entry has just been added and is in its early stage of development.
- 🌿 (budding) means entry has been selected for development and is being outlined and drafted.
- 🌳 (evergreen) means entry (metadata, internal links, the content, and structure) is well-developed.

The idea is that status of the entires will function as tags, enabling a grouping mechanism to get an overview and filter those that still need to be developed from those that are complete.

**Updated**

By incorporating a [time stamp plugin](https://github.com/gjtorikian/jekyll-last-modified-at), each entry automatically indicates when it has last been updated. 

**Category**

The order of the categories have meaning: the first is the overarching subject to which the entry belongs, the second (optional) is the subcategory, and third describes the content type (essay, summary, definition, and so on).

*Note: The `status` and `category`  only work as clickable tags in Obsidian, not yet on this website.*

##### Links

Backlinks are listed in the `Mentioned in:` panel on the right (or, if a small screen size, at the bottom).

[[About the formatting|This is what an internal link looks like]] and [[this is an internal link to an entry that has not yet been created]].

["This is a direct quote with a source link"]() and [this is paraphrased content with a source link](), and

> [this is a block quote with a source link.]()