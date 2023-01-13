
It's much easier to read it locally first before committing to the master branch:
- https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll

This is interesting. Seems like we can choose which branch
we'd like to publish from:
- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

When it comes to writing a post, you can add the following setting to update 
the date of the post:
- `last_modified_at: 2016-03-09T16:20:02-05:00`

Add this tag in the header section.

The header section looks like:
```buildoutcfg
---
// the 3 dashes at the top and bottom indicate the header section
---
```

