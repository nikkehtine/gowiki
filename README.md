# gowiki

[Article](https://go.dev/doc/articles/wiki/)

## Checklist

- [x] Store templates in `templates/` and page data in `data/`.
- [ ] Add a handler to make the web root redirect to `/view/FrontPage`.
- [ ] Spruce up the page templates by making them valid HTML and adding some CSS rules.
- [ ] Implement inter-page linking by converting instances of `[PageName]` to `<a href="/view/PageName">PageName</a>`.
      (hint: you could use `regexp.ReplaceAllFunc` to do this)
- [ ] Split `wiki.go` into multiple files for maintainability
