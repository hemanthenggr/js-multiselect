# js-multiselect [![NPM](https://img.shields.io/npm/v/react-select.svg)](https://www.npmjs.com/package/js-multiselect)

A Light weight javascript based multi selet without any dependencies.

Inspired from [VanillaSelectBox](https://vorotina.github.io/vanilla-select/)

## Installation
With [NPM](https://www.npmjs.com/package/js-multiselect):
```zsh
npm install js-multiselect --save
```

## Setup	
```css
  @import 'js-multiselect/multiselect';
```
```js
  let multiSelect = new multiselect("#demo", {
      maxHeight: 200,
      search: true,
      placeHolder: "Select your questions",
      selectAll: "Check All",
      clearAll: "Clear All"
  });
```

## License
MIT License
