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

- Clone files into style directory, named as you wish (such as `sass` or `styles`)
- All files are compiled into one file (via the `main.scss` global import file). Rename this if you'd like.
- Compile
- Link `main.css` (or whatever you compile it to) in your markup

## Notes

- I prefer .sass syntax
- `@import` directives haven't been working with Gulp sass (which I often use), so
  relevant files are in .scss
- Use with Libsass or Ruby Sass
- The syntax skins are for Highlight.js. Comment/uncomment to toggle
- Refactors that can hopefully be considered improvements to happen frequently
