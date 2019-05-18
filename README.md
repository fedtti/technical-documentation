# Technical Documentation • freeCodeCamp

Responsive Web Design Projects

## Installing

You don’t need to install this project at all, if you just want to have a look at [the online preview](https://codepen.io/fedtti/full/NJMjVN).

### Requirements

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)
- [Gulp](https://gulpjs.com/)

Gulp CLI is required to run the live preview _and/or_ to start the development environment.

```
npm i -g gulp-cli
git co https://github.com/fedtti/technical-documentation.git
cd tribute-page/
npm i
gulp --serve
```

Please, notice that `fsevents` only works on macOS: it doesn’t break any dependency – despite the given error – on other platforms.

## Contributing

Being a freeCodeCamp project, you have some limits: see [the official guidelines](https://learn.freecodecamp.org/responsive-web-design/responsive-web-design-projects/build-a-technical-documentation-page/) to know more.

### Requirements

- [Gulp](https://gulpjs.com/)
- [Sass](https://sass-lang.com/)
- Autoprefixer
- CleanCSS
- [BrowserSync](https://browsersync.io/)

```
npm i -g gulp-cli
git co https://github.com/fedtti/technical-documentation.git
cd tribute-page/
npm i -D browser-sync gulp-autoprefixer gulp-clean-css gulp-rename gulp-sass
gulp --serve
```

Feel free to submit pull requests since I’ve already completed the learning path.

## License

© 2019 **[Federico Moretti](https://federicomoretti.it/)**. All rights reserved. Released under [a MIT license](/LICENSE).
