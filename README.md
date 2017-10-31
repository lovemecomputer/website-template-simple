# website-template-simple

simple repository of starter website files 🌱🌸

## includes:

- basic files
  - `index.html`
  - `main.js`
  - `main-initial-compile.css`
    <br>(if not using Sass, rename this file to `main.css` and work from there)
- `styles` directory for `.scss` files
- normalize.css
- jQuery (commented out by default in `index.html`)
- html viewport config
- simple `.gitignore` that excludes many OS files
- simple `.surgeignore` file, good for a reference of what you ignore when deploying.


## notes

### units

`<html>` is set to `0.625rem` (10px equivalent) <br>`<body>` font size is set to `1.6rem` (16px equivalent)

Thus,
```
1rem == 10px
.1rem == 1px
```

Use these scaling-friendly `rem` units wherever possible :)


### Sass
from the project root, run this command:

```
sass --watch styles/main.scss:main.css
```

- [installing Sass](http://sass-lang.com/install)
- [more Sass usage info](http://sass-lang.com/guide)
