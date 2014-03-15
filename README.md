SKAS Webstranka
==========

Oficiálna webová stránka ŠKAS FMFI UK.

## Požiadavky ##

* [Jekyll](http://jekyllrb.com/docs/installation/)
* `ruby-i18n` package (potrebný kvôli internalization pluginu)

## Inštalácia ##

1. Stiahni zdrojové súbory:

  ``` bash
  $ git clone https://github.com/fmfi-skas/webstranka.git skas-webstranka
  $ cd skas-webstranka
  $ git submodule init
  $ git submodule update
  ```

2. Spusti `jekyll build` na vygenerovanie statických HTML stránok.
3. Nasmeruj web server na `_site` adresár.
