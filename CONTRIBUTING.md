## Contributor License Agreement
By contributing you agree to the [LICENSE](https://github.com/simonebrunozzi/open-guide-to-learning-tech-geek-nerdy-stuff/blob/master/LICENSE) of this repository.

## Contributor Code of Conduct
By contributing you agree to respect the [Code of Conduct](https://github.com/simonebrunozzi/open-guide-to-learning-tech-geek-nerdy-stuff/blob/master/CODE-OF-CONDUCT.md) of this repository.

## Information on how to contribute
We prefer free material, although there might be non-free material that is so good that we still want to include it in here.

The principles behind adding a new link (or a new category) are the following:

1. You can propose a new category if it belongs to the same tech/geek/nerd stuff.

2. You can propose a new "link", by actually simply adding


```
[$succint_description]($link)
```

Example:

```
[Video games and AI](http://togelius.blogspot.com/2016/01/why-video-games-are-essential-for.html)
```

If your link points to a discussion, which then points to the actual resource, such as in the case of a Hacker News discussion, you can simply write:

```
[$succint_description]($link-to-resource) ([HN discussion]($link-to-discussion))
```

Example:

```
[Berkeley AI Materials](http://ai.berkeley.edu/project_overview.html) ([HN discussion](https://news.ycombinator.com/item?id=10929985))
```

If you want to specify the file format (e.g. PDF), you can add it after the `$succint_description`.

## Editing/formatting Guidelines
- We typically don't like files hosted on "temporary" locations, e.g. google drive, dropbox, mega, etc.
- We always prefer a `https` link over a `http` one -- as long as they are on the same domain and serve the same content
- On root domains, strip the trailing slash: use `http://example.com` instead of `http://example.com/`
- Always prefer the shortest link: `http://example.com/dir/` is better than `http://example.com/dir/index.html`
- Do not include URL shortener links
- Most files are `.md` files. Try to learn [Markdown](https://guides.github.com/features/mastering-markdown/) to be a more effective contributor.
