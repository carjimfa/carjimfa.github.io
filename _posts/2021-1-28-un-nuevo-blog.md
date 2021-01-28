---
layout: post
title: Un nuevo blog
---

Entiendo que otro blog sobre un programador blanco cis no es lo que necesitaba el mundo, pero sí que es lo que necesitaba este programador blanco cis afincado en este momento en Valencia.

Me he montado este blog con un fork de Jekyll y aprovechando las github pages, que parece ser la manera más sencilla de publicar contenido sin tener que pasar por Wordpress, Ghost o similares.

El proceso ha sido sencillo como pocos aunque he tenido algún problema por el hecho de tener múltiples cuentas de GitHub en el mismo ordenador.

### El tutorial para montar todo esto

He seguido un tutorial de una web de la que he dudado por el nombre (HowChoo) pero que me ha servido mil así que os lo dejo por [aquí](https://howchoo.com/git/how-to-blog-in-markdown-using-github-and-jekyll-now#fork-jekyll-now-and-rename-the-repository-yourgithubusernamegithubio). También he tenido que añadir una maravillosa segunda cuenta de GitHub, y de nuevo lo he hecho con un tutorial majo que he sacado de [aquí](https://code.tutsplus.com/tutorials/quick-tip-how-to-work-with-github-and-multiple-accounts--net-22574). Por supuesto, he tenido movidas extra, en principio un error que me daba al hacer `push` a `master` que ha sido por una chorrada que no encontraba en ningún sitio.

El error en cuestión era este:

```bash
% git push origin master                                                   
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@         WARNING: UNPROTECTED PRIVATE KEY FILE!          @
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
Permissions 0644 for '/.../id_rsa_COMPANY' are too open.
It is required that your private key files are NOT accessible by others.
This private key will be ignored.
Load key "/Users/carlosjimenez/.ssh/id_rsa_COMPANY": bad permissions
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
%
```

Y al final arreglarlo ha sido tan simple como un `chmod 0600 ~/.ssh/id_rsa_COMPANY`. 
Bueno, si tenéis una cuenta de [Github](http://github.com) y queréis montar un blog o web personal fácil, rápido y sencilla (Y GRATIS), esta es la manera más simple posible, de verdad.

Una de las cosas que creo que he decidido y no sé si he hecho bien es crear contenido en castellano y no en inglés. Creo que es importante que la información sea accesible para todos, pero no puedo estar traduciendo todos los posts que escribo así que creo que voy a pasar del lenguaje de Shakespeare y adoptar el lenguaje de Amaia Montero y continuar en castellano. 

Nada más por aquí,

Sed malos colegas

![alt text](https://www.elheraldo.hn/csp/mediapool/sites/dt.common.streams.StreamServer.cls?STREAMOID=8GswCJQRzAP0IOKWcK8UPs$daE2N3K4ZzOUsqbU5sYvqnrAE2Each_wwTPVKgvFK6FB40xiOfUoExWL3M40tfzssyZqpeG_J0TFo7ZhRaDiHC9oxmioMlYVJD0A$3RbIiibgT65kY_CSDiCiUzvHvODrHApbd6ry6YGl5GGOZrs-&CONTENTTYPE=image/jpeg "Diva")

