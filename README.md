This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

Below you will find some information on how to perform common tasks.<br>
You can find the most recent version of this guide [here](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md).

## Folder Structure

```
map-app/
  README.md
  node_modules/
  package.json
  public/
    index.html
    map.js
    sample_merged_1.csv
    style.css
    favicon.ico
  src/
    App.css
    App.js
    App.test.js
    index.css
    index.js
    logo.svg
```

For the project to build, **these files must exist with exact filenames**:

* `public/index.html` is the page template;
* `src/index.js` is the JavaScript entry point.


## How to compile
*  `git clone https://github.com/jesusveca/map-app-ReactJS.git`
*  `cd map-app/map-app/`
*  `npm install` install node-modules

## How to run
*  `npm start`
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## How to deploy to github pages
*  `npm run build`
*  add to "package.json" `"homepage": "http://jesusveca.github.io/map-app",`
*  add to "package.json" inside of script `"predeploy": "npm run build",` and  `"deploy": "gh-pages -d build"`
*  `npm install --save-dev gh-pages`
*  `npm run deploy`
Open [https://jesusveca.github.io/map-app/#](https://jesusveca.github.io/map-app/#) to view it in the browser.
