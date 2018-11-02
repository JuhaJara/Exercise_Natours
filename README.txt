npm init
npm install node-sass --save-dev

npm uninstall

npm run compile:sass

"scripts": {
    "compile:sass": "node-sass sass/main.scss css/style.css -w"
  },