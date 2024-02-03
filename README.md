# Загрузчики
  _______________________________________________________
"scripts": {
    "start": "webpack serve --mode development",
    "build": "webpack --mode production",
    "lint": "eslint .",
    "lint:fix": "eslint . --fix",
    "test": "jest",
    "coverage": "jest --coverage",
    "preshow:coverage": "npm run coverage",
    "show:coverage": "live-server coverage/lcov-report",
    "preshow:dist": "npm run build",
    "show:dist": "live-server dist"
  },
  _______________________________________________________

"devDependencies": {
    "@babel/cli": "^7.23.9",                    babel-loader @babel/preset-env @babel/cli @babel/core babel-preset-airbnb
    "@babel/core": "^7.23.9",
    "@babel/preset-env": "^7.23.9",
    "@types/jest": "^29.5.11",
    "babel-loader": "^9.1.3",
    "babel-preset-airbnb": "^5.0.0",
    "css-loader": "^6.9.1",
    "eslint": "^8.56.0",                        eslint eslint-config-airbnb-base eslint-plugin-jest
    "eslint-config-airbnb-base": "^15.0.0",
    "eslint-plugin-jest": "^27.6.3",
    "html-loader": "^5.0.0",
    "html-webpack-plugin": "^5.6.0",
    "jest": "^29.7.0",                          jest @types/jest
    "style-loader": "^3.3.4",
    "webpack": "^5.90.0",                       webpack webpack-cli webpack-dev-server
    "webpack-cli": "^5.1.4",
    "webpack-dev-server": "^4.15.1"
  },
  "dependencies": {
    "core-js": "^3.35.1"
  }