# help-divide-es

La ayuda de [divide](https://github.com/divengine/divide), el IDE de plantillas Div para la terminal, en español.

El contenido está en la [wiki](https://github.com/divengine/help-divide-es/wiki) de este repositorio. Es una traducción de la [wiki de divide](https://github.com/divengine/divide/wiki), y divide la incorpora como libro de ayuda cuando su interfaz está en español:

```sh
tools/sync_book.py divide <clon de help-divide-es.wiki> --language es
```

## Cómo traducir

- **Los nombres de las páginas no se traducen.** `Other-Files.md` se sigue llamando así; dentro, el título (`# Otros archivos`) y el texto van en español. divide busca las páginas por su nombre (la ayuda de F1, los enlaces entre páginas, el índice), y así funcionan igual en todos los idiomas.
- En los enlaces se traduce el texto, no la página: `[[Otros archivos|Other Files]]`.
- Una página que aún no está traducida se muestra en inglés: se puede traducir poco a poco.
- Las imágenes son las de la wiki original, mientras no haya capturas de la interfaz en español.
