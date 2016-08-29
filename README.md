GitHub-style preview stylesheet for [Markdown Edit](http://markdownedit.com/). The stylesheet is based on [sindresorhus/github-markdown-css](https://github.com/sindresorhus/github-markdown-css).

**To use it**:

1. In Markdown Edit, click *Settings* > *HTML Tempalte* (F8)
2. Copy the content of `user_template.html` there
3. Enjoy!

Steps to **re-compile the template**:

1. Get the default MDE template
2. Take the [`github-markdown.css`](https://github.com/sindresorhus/github-markdown-css/blob/gh-pages/github-markdown.css) file from the `sindresorhus/github-markdown-css` project
3. Replace `.markdown-body` with `#content`
4. Insert into MDE template

A bit of **history**:

- This GitHub style started as a [Gist](https://gist.github.com/borekb/57bc575e38db2c99f1b5).
- Then, Mike Ward (the author of Markdown Edit) adopted it as a "native" style between Nov 2015 and August 2016, see [mike-ward/Markdown-Edit#56](https://github.com/mike-ward/Markdown-Edit/issues/56).
- Then it has been removed in [1.30](https://github.com/mike-ward/Markdown-Edit/releases/tag/v1.30) which is when I've created this repo and updated the stylesheet to reflect the new native-fonts GitHub.