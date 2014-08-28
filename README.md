# XPDES Consortium Website

To add to this site please contact Elsa (gonsie) to request membership in the [XPDES Group](http://github.com/xpdes).

# How to add to the site

Each new page should be written in [Markdown Format](http://daringfireball.net/projects/markdown/) (specifically [GitHub Flavor](https://help.github.com/articles/github-flavored-markdown)).
Each page should begin with [Jekyll Frontmatter](http://jekyllrb.com/docs/frontmatter/) of the form

```
---
layout: sometypeoflayout
title: 'Title for the titlebar'
tag: sometag
---
```

## Adding your biography

Make your copy of the template file [people/template.md](https://github.com/XPDES/XPDES.github.io/blob/master/people/template.md).
Then, be sure to update the following:

- The file name should correlate your name
- Biographies are stored in the people folder.
- Denote your associated organization by adding a tag to your front matter.
  - Currently processed tags are `llnl`, `uiuc`, `gatech`, and `rpi`
- Adding your photo
  - It should be stored in the image folder
  - You will have to update the hard link to the photo 

## Adding a dated post (aka Announcement)

- Use `layout: post` in your frontmatter.
- Put your file is in the _posts directory
- Your filename must match the format `YEAR-MONTH-DAY-title.md` (see [Jekyll Posts](http://jekyllrb.com/docs/posts/))

## Adding a new page to the sidebar

- Use `layout: page` in your frontmatter
- Put your file in the top level of the directory
- *TODO: add details about creating a new category of pages*
