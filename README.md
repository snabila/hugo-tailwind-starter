# Hugo Tailwind Simple Starter Theme

A simple starter Hugo theme build with Tailwind CSS.

## Get started

### Installation

```sh
hugo new site new-site

cd new-site

git clone https://github.com/snabila/hugo-tailwind-starter themes/hugo-tailwind-starter

# To use the theme, you can specify the theme in the config file or copy the layouts folder into you project's
echo "theme = \"hugo-tailwind-starter\"" >> config.toml

# Run Hugo
hugo server -D

# Watch CSS classes
cd themes/hugo-tailwind-starter
npm run watch
```

### Guides

Some links that may be helpful

- [Hugo quick start](https://gohugo.io/getting-started/quick-start/), if you're new to Hugo.
- [Menus](https://gohugo.io/content-management/menus/). Used for the navigation link.
