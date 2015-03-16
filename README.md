> Simplicity is the ultimate sophistication.  
> ~ Leonardo Da Vinci

## SP-Sass

A generic starting point for Sass that I often use when starting projects. Essentially
a home-grown Sass boilerplate, however basic it may be. 

## Reasoning

- Organization
- Directory structure
- Base styles
- Minimal bloat

## Usage  

- Clone repo, rename `sp-sass` to fit your liking (perhaps to `sass` or `styles`)
- All files are imported into `main.scss`. Rename this if you'd like.
- Compile (using [autoprefixer](https://github.com/postcss/autoprefixer))
- Use generated css :)

## Notes

- I prefer .sass syntax
- `@import` directives haven't been working with Gulp sass (which I often use), so
  relevant files are in .scss
- Use with Libsass or Ruby Sass
- The syntax skins are for Highlight.js. Comment/uncomment to toggle
- However you compile, use autoprefixer.
- Refactors that can hopefully be considered improvements to happen frequently
