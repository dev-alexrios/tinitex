## Uso

[[PKG-IU README/README|↩️ Regresar a la página principal]]

Escriba una lista con el nombre y la etiqueta de cada software.

La nomenclatura que debe utilizar para crear el listado es `<nombre>|<etiqueta>`.
Puede tomar la siguiente imagen como referencia.

---

Instale, actualice, verifique o desinstale una lista de programas preseleccionados por usted.

Sin procesos extra, es tal cual y cómo se describe arriba.

Escribe una lista con el nombre y etiqueta de cada software que desee y listo. Ahora sólo queda ejecutar.

### `-i` / `--install` <file_path> argumento

Utilice la bandera `--install` para instalar los paquetes de una lista. Tome en cuenta que si no pasa como argumento la ruta de un fichero `collection.list` se usará el predeterminado.

`ignitex --install`

Si lo desea, cargue una colección diferente a la predeterminada, para esto ingrese la ruta del fichero.

`ignitex --install [file.list]`

### `-u` / `--uninstall` <file_path> argumento

Utilice la bandera `--uninstall` para desinstalar los paquetes de una lista. Tome en cuenta que si no pasa como argumento la ruta de un fichero `collection.list` se usará el predeterminado.

`ignitex --uninstall`

Si lo desea, cargue una colección diferente a la predeterminada, para esto ingrese la ruta del fichero.

`ignitex --uninstall [file.list]`

### `-e` / `--edit` argumento

...

### `-v` / `--version` argumento

Al pasar este argumento, podrá ver la versión actual de Ignitex. Esto es útil en caso de que desee comprobar si tiene instalada la última versión.

### `--update` argumento

...
