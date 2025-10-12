<!-- markdownlint-disable-next-line -->
<div align="center">

  <!-- markdownlint-disable-next-line -->
  # Personal Blog

  A minimal, responsive, and feature-rich Jekyll theme for technical writing.

  <!-- TODO: Change this -->
  [![CI](https://img.shields.io/github/actions/workflow/status/cotes2020/jekyll-theme-chirpy/ci.yml?logo=github)][ci]&nbsp;
  [![Codacy Badge](https://img.shields.io/codacy/grade/4e556876a3c54d5e8f2d2857c4f43894?logo=codacy)][codacy]&nbsp;
  [![GitHub license](https://img.shields.io/github/license/cotes2020/jekyll-theme-chirpy?color=goldenrod)][license]&nbsp;
  [![Gem Version](https://img.shields.io/gem/v/jekyll-theme-chirpy?&logo=RubyGems&logoColor=ghostwhite&label=gem&color=orange)][gem]&nbsp;
  [![Open in Dev Containers](https://img.shields.io/badge/Dev_Containers-Open-deepskyblue?logo=linuxcontainers)][open-container]

  <!-- TODO: Change this -->
  [**Live Demo** →][demo]

  <!-- TODO: Change this -->
  [![Devices Mockup](https://chirpy-img.netlify.app/commons/devices-mockup.png)][demo]

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
