# vue-jade-editor
[![Build Status](https://travis-ci.org/zxdong262/vue-jade-editor.svg?branch=master)](https://travis-ci.org/zxdong262/vue-jade-editor)

online jade(pug) editor plugin for vue.js

## demo & doc
visit <a href='http://html5beta.com/apps/vue-jade-editor.html'>http://html5beta.com/apps/vue-jade-editor.html</a>

## get
```bash
bower install vue-jade-editor
```

or

```bash
npm install vue-jade-editor
```

## features
- auto indent(backspace enter)
- indent can be customized
- auto close for quote, single quote, bracket, left parenthesis
- smart tab: tab selection or single line
- untab keyboard shortcuts: ctrl + [
- tab keyboard shortcuts: ctrl + ] or just tab
- keyboard shortcuts for i and b
- content can be modifed by vm.$broadcast('je-insert-content', htmlToInsert)
- auto increase textarea height

## test & build
```bash
git clone https://github.com/zxdong262/vue-jade-editor.git
cd vue-jade-editor
npm install
bower install
gulp test

#build
gulp build

```

## License
MIT