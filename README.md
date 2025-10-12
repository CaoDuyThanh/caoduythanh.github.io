<!-- markdownlint-disable-next-line -->
<div align="center">

  <!-- markdownlint-disable-next-line -->
  # Personal Blog

  A minimal, responsive, and feature-rich Jekyll personal blog of a little bear :)

  <!-- TODO: Change this -->
  [**Live Demo**](https://caoduythanh.github.io/)

  <!-- TODO: Change this -->
  ![](/assets/img/profile/screenshot.png)

</div>

## Prerequisite
- Ruby 3.4+

## Add your new articles?

### Sidebar

If you want your page is attached to the sidebar (like CV page), put it in the `_tabs` folder.

### New article in collection

If you want to create a new article, put it in folder `_posts`. The article has this format `<year>-<month>-<date>-<title>.md`. It will create a nice timeline using the datetime information.

## How to build?

To build the static site using Jekyll, you need to install bundle, dependencies

```bash
$ bundle config set --local path 'vendor/bundle'
$ bundle install
```

Then build Jekyll and start the site

```bash
bundle exec jekyll build
bundle exec jekyll serve --watch
```
