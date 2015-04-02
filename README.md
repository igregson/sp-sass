> Simplicity is the ultimate sophistication.  
> ~ Leonardo Da Vinci

## SP-Sass

A module starting point for Sass. A wired-up file and directory structure with the essentials (reset, base typography, and other generics) for quickly starting new projects. 

Essentially a simple yet effective home-grown Sass boilerplate.

## Reasoning

- Organization
- Directory structure
- Base styles
- Speedy start with minimal bloat (animation and syntax highlihghting directories are the only potential "bloated" aspects, though they're not imported by default)

## Usage  

- Clone: `gti clone git@github.com:igregson/sp-sass.git`
- All files are imported into `main.scss`. Rename if you'd like
- Compile and enjoy ([autoprefixer](https://github.com/postcss/autoprefixer) necessary)

## Notes

- Supports Libsass and Ruby Sass
- Most files are in `.sass` syntax (personal preference) but some in `.scss` as a workaround to issues I've experienced with some compilers
- Syntax highlighting directory are for [Highlight.js](https://highlightjs.org/) - comment/uncomment to toggle 
- However you compile, it's important to use Autoprefixer ([Prepos](https://prepros.io/) is a free compiler GUI with autoprefixer support)
