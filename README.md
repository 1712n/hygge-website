# Hygge Website

Hygge Workbook hosted at [hygge.work](https://hygge.work/). Generated with [Hugo](https://gohugo.io/) and [Minimo theme](https://github.com/MunifTanjim/minimo).

## Setup

Check `.devcontainer.json`.

## FAQ

### I want to add content

First is important to understand [Hugo content structure](https://gohugobrasil.netlify.app/content-management/organization/).

- New posts and pages go on `content/`
- Assets like images can go on `static` or `assets`. Files at the first are served as-is and at the latter are for using Hugo [image processing](https://gohugo.io/content-management/image-processing/) features.
- But preferably use [page bundles](https://gohugo.io/content-management/page-bundles/) as it's the best way to organize and work with resources in Hugo. A page bundle is basically grouping the content and resources of page under the same folder at `content`. Check this [example](https://github.com/1712n/inca-website/tree/main/content/intelligence/pig-butchering)

### I want to modify the site

Don't touch `themes/minimo`. If you want to customize the theme do so via overrides on the project dir as those have [precedence over themes](https://gohugo.io/hugo-modules/theme-components/).
