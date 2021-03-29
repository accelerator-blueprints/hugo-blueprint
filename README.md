# Hugo Blueprint

[![](https://img.shields.io/github/workflow/status/accelerator-blueprints/hugo-blueprint/master)](https://github.com/accelerator-blueprints/hugo-blueprint/actions?query=is%3Acompleted)
[![](https://img.shields.io/github/workflow/status/accelerator-blueprints/hugo-blueprint/check-markdown-links/master)](https://github.com/accelerator-blueprints/hugo-blueprint/actions?query=is%3Acompleted)

![Repository Size](https://img.shields.io/github/repo-size/accelerator-blueprints/hugo-blueprint)
![Lines of Codes](https://img.shields.io/tokei/lines/github/accelerator-blueprints/hugo-blueprint)

## Start new Site

```sh
hugo new site site
cd site
git submodule add --depth 1 https://github.com/reuixiy/hugo-theme-meme.git themes/meme
```

1. Download a theme into the same-named folder.
   Choose a theme from https://themes.gohugo.io/ or
   create your own with the "hugo new theme <THEMENAME>" command.
2. Perhaps you want to add some content. You can add single files
   with "hugo new <SECTIONNAME>/<FILENAME>.<FORMAT>".
3. Start the built-in live server via "hugo server".

## Themes

- [Themes](https://themes.gohugo.io/)
