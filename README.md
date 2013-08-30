Webstranka
==========

Oficiálna webová stránka ŠKAS FMFI UK

## Požiadavky ##

* [Jekyll](http://jekyllrb.com/docs/installation/)
* `ruby-i18n` package (potrebný kvôli internalization pluginu)

## Inštalácia ##

1. Stiahni zdrojové súbory:

  ``` bash
  $ git clone <repository_url>
  $ git submodule init
  $ git submodule update && git submodule update
  ```

2. Spusti `jekyll build` na vygenerovanie statických HTML stránok.
3. Nasmeruj web server na `_site` adresár.
