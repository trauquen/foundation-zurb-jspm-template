# Foundation Zurb Template with jspm 

[![devDependency Status](https://david-dm.org/zurb/foundation-zurb-template/dev-status.svg)](https://david-dm.org/zurb/foundation-zurb-template#info=devDependencies)

Base on Foundation-sites 6.3, just replace bower with jspm, then you can write JavaScript with ES6 export/import too.

## Installation

To use this template, your computer needs:

- [NodeJS](https://nodejs.org/en/) (0.12 or greater)
- [Git](https://git-scm.com/)

## Setup

To manually set up the template, first download it with Git:

```bash
git clone https://github.com/trauquen/foundation-zurb-jspm-template.git projectname
```

Then open the folder in your command line, and install the needed dependencies:

```bash
cd projectname
npm install
jspm install
```

Finally, run `npm start` to run Gulp. Your finished site will be created in a folder called `dist`, viewable at this URL:

```
http://localhost:8000
```

To create compressed, production-ready assets, run `npm run build`.
