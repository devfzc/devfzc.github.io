---
title: About
permalink: /about/
---

This blog is demo blog for [Kiko Plus](https://github.com/AWEEKJ/Kiko-plus)

This theme is inspired by [Kiko](http://github.com/gfjaru/Kiko) theme, powered by [Jekyll](http://jekyllrb.com), hosted on [Github Pages](https://pages.github.com).

## Configuration

All configuration is done via `_config.yml` file which you will find in your main repo folder. Change this `<something>` to yours.

- Change this to your blog name.

```yml
name: <blog-name>
```

- Change this to your domain. **NOTE**- if running locally change this to `url: "https://localhost:4000"`.

```yml
url: "https://<your-name>.github.io"
```

- Change this to your branch name where _gh-pages_ resides. !NOTE apply only if you used __Method 2__ for installation.

```yml
baseurl: "/<branch-name>"
```

- These configuration in `author:` is for links to icons in footer. Modify `_includes/footer.html` to add more link icons.

```yml
author:
  name:             your-name
  facebook:         your-id
  twitter:          your-id
  github:           your-id
  linkedin:         your-id
  medium:           your-id
  tumblr:           your-id
  email:            your-id@your-email.com
```

- Change this to your Google Analytic ID.

```yml
google-analytics:
  id:               your-id
```

- Change this to your Disqus ID.

```yml
disqus:
  id:               your-id
```

## Rakefile Usage

```bash
$ rake post title="A Title" [date="2015-08-16"] [tags=[tag1,tag2]]
$ rake draft title="A Title" [date="2015-08-16"] [tags=[tag1,tag2]]
$ rake preview
```

## License

This theme is released under MIT License.
