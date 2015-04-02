> Simplicity is the ultimate sophistication.  
> ~ Leonardo Da Vinci

## SP-Sass

A module starting point for Sass that I often use when starting projects. Essentially
a home-grown Sass boilerplate, however basic it may be. 

## Reasoning

- Organization
- Directory structure
- Base styles
- Minimal bloat

## Usage  

- Clone repo, rename `sp-sass` to fit your liking (perhaps to `sass` or `styles`)
- All files are imported into `main.scss`. Rename this if you'd like
- Compile (using [autoprefixer](https://github.com/postcss/autoprefixer)) and enjoy

## Notes

- Works with Libsass and Ruby Sass
- I prefer `.sass` syntax but some files are in `.scss` as a workaround to issues I've experienced with some compilers
- Syntax files are for [Highlight.js](https://highlightjs.org/) - comment/uncomment to toggle 
- However you compile, it's important to use Autoprefixer ([Prepos](https://prepros.io/) is a free compiler GUI with autoprefixer support)
