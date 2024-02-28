# Template para PIPs de la UNCo

Este es un template genérico para PIPs de la UNCo.

Este template incluye la carátula de la PIP en _title.tex_.

Carpetas:

- _chapters_: Contiene un archivo _.tex_ por capítulo.
- _imgs_: Carpeta de imagenes de la PIP.

## Nuevo capitulo

Para crear un capitulo nuevo, crea un archivo _.tex_ en _chapters_, luego en index.tex agrega la sentencia:

```tex
\include{chapters/tu-capitulo.tex}
```

Luego escribí tu capítulo en _tu-capitulo.tex_ recorta empezar con la sentencia:

```tex
\chapter{Nombre de tu capitulo}
```

Para que este sea correctamente renderizado en él _.pdf_ final.

## Referencias

Para el manejo de referencias es recomendable utilizar bibtex más alguna herramienta como [Zotero](https://zotero.org).
