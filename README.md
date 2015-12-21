ŠKAS Webstránka
==========

Oficiálna webová stránka ŠKAS FMFI UK.

## Požiadavky ##

* [Jekyll](http://jekyllrb.com/docs/installation/)
* `ruby-i18n` package (potrebný kvôli internalization pluginu)
* [nodejs](http://nodejs.org/)

## Inštalácia ##

1. Stiahni zdrojové súbory:

  ``` bash
  $ git clone https://github.com/fmfi-skas/webstranka.git skas-webstranka
  $ cd skas-webstranka
  $ git submodule init
  $ git submodule update
  $ npm install
  $ node_modules/.bin/bower install
  $ node_modules/.bin/grunt build
  ```

2. Spusti `jekyll build` na vygenerovanie statických HTML stránok.
3. Nasmeruj web server na `_site` adresár.

## Licencia

Zdrojové kódy: MIT License

Obsah: [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/)

