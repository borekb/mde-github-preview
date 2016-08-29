GitHub-style preview stylesheet for [Markdown Edit](http://markdownedit.com/). The stylesheet is based on [sindresorhus/github-markdown-css](https://github.com/sindresorhus/github-markdown-css).

To use it:

1. In Markdown Edit, click *Settings* > *HTML Tempalte* (F8)
2. Copy the content of `user_template.html` there
3. Enjoy!

Steps to re-compile the template:

1. Get the default MDE template
2. Take the [`github-markdown.css`](https://github.com/sindresorhus/github-markdown-css/blob/gh-pages/github-markdown.css) file from the `sindresorhus/github-markdown-css` project
3. Replace `.markdown-body` with `#content`
4. Insert into MDE template