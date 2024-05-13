# Git Dad

## Jekyll

[Jekyll Docs](https://jekyllrb.com/docs/)

### Installation

Follow the instructions in the [Jekyll Docs](https://jekyllrb.com/docs/installation/) to complete the installation of
the basic environment including Ruby and RubyGems

After cloning repo run:

```console
$ gem install jekyll bundler
$ bundle
```

### Usage

Run site locally:

```console
$ jekyll serve
```

With livereload:

```console
$ jekyll serve -l
```

Build:

```console
$ jekyll build
```

## Chirpy

Jekyll theme used for site

### Links

[Chirpy Gem Repo](https://github.com/cotes2020/jekyll-theme-chirpy/)

[Live Demo](https://cotes2020.github.io/chirpy-demo/)

[Chirpy Starter Repo](https://github.com/cotes2020/chirpy-starter)



### Upgrading

Currently using version **7.0.0**

Can check version with:

```console
$ bundle info jekyll-theme-chirpy
```

Current available Chirpy version: ![Gem Version](https://img.shields.io/gem/v/jekyll-theme-chirpy)

To upgrade change the version in `Gemfile` and then run:

```console
$ bundle install
```

Jekyll can only read files in the folders `_data`, `_layouts`, `_includes`, `_sass` and `assets`, as well as a small part of options of the `_config.yml` file from the theme's gem.

To fully use all the features of **Chirpy**, you need to copy the other critical files from the theme's gem to your
Jekyll site. The following is a list of targets:

```shell
.
├── _config.yml
├── _plugins
├── _tabs
└── index.html
```

To find the location of the theme's files to copy these from run:

```console
$ bundle info --path jekyll-theme-chirpy
```
