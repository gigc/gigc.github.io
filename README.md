# gigc.github.io [![Build Status](https://travis-ci.org/gigc/gigc.github.io.svg?branch=master)](https://travis-ci.org/gigc/gigc.github.io)

Repositorio de la página web de [GIGC](http://gigc.github.io/).

### Puesta en marcha (Debian / Ubuntu)

Esta es una web contruida con [Jekyll](http://jekyllrb.com) y alojada en [GitHub Pages](http://pages.github.com). Para poder levantar el sitio primero verifique los [requerimientos](http://jekyllrb.com/docs/installation/#requirements) de Jekyll. Se utilizo para el diseño de la web el [template](https://github.com/jglovier/jekyll-new) por defecto de Jekyll y iconos de [Iconfinder](https://www.iconfinder.com/iconsets/social-network-9).

Vamos a necesitar tener instalado primero [Ruby](https://www.ruby-lang.org/) y luego intalar la gema de Jekyll.

```bash
$ sudo apt-get install ruby-full
$ gem install jekyll
# Puede que en el medio tenga algunos problemas de permisos en algunas carpetas
# En la web hay varias formas de como arreglar esos detalle :P
```
Siguiendo estos pasos vamos a poder copiar el repositorio a la computadora y construir / levantar el sitio:

```bash
$ git clone https://github.com/gigc/gigc.github.io.git
$ cd gigc.github.io
$ jekyll serve
~/tgc-utn.github.io $ jekyll serve
# => Listo solo hay que entrar a http://localhost:4000
```

### Edición
Completar esta sección :laughing:

[Jekyll](http://jekyllrb.com/) soporta por defecto las siguientes tecnologías:
* [kramdown](http://kramdown.gettalong.org/)
* [SASS](http://sass-lang.com/)
* [CoffeScript](http://coffeescript.org/)

Algunas cosas que pueden ayudar
* [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
* [Markdown editor](http://dillinger.io/)
