slush-fis
==============

> A [slush](http://slushjs.github.io) generator for FIS

## Installation

Install `slush-fis` globally:

```bash
npm install -g slush-fis
```

Remember to install `slush` globally as well, if you haven't already:

```bash
npm install -g slush
```

## Usage

Create a new folder for your project:

```bash
mkdir my-fis-app
```

Run the generator from within the new folder:

```bash
cd my-fis-app

slush fis
```

The project structure with the Todo list example included will look like this:

```
my-fis-app/
├── .bowerrc
├── .csslintrc
├── .editorconfig
├── .gitignore
├── .jshintrc
├── bower.json
├── gulpfile.js                             # See "Gulpfile" below
├── karma.conf.js
├── README.md
├── package.json
└── src
    └── app
        ├── index.html
        ├── css
        │   └── base.css / index.css / layout.css / modules.css / page.css
        ├── less
        │   └── base.less / index.less / layout.less / modules.less / page.less
        ├── sass
        │   └── base.scss / index.scss / layout.scss / modules.scss /page.scss
        ├── stylus
        │   └── base.styl / index.styl / layout.styl / modules.styl /page.styl
        ├── index.js
        ├── assets
        │   └──
        └──

```

## License

MIT
