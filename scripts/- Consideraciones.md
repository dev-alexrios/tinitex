
> [!NOTE] CONSIDERACIONES
> 1. Clasificar el software puede ser tedioso para el cliente común.

---

## Requisitos

Debe tener **Git** para descargar el proyecto.

Instale Git ingresando en su terminal lo siguiente:

```bash
apt install git -y
```

## Uso

**Instalar paquetes**

Ejecute el fichero `ignitex.sh` para instalar todos los paquetes listados.

Ejecute el fichero `ignitex.sh` con `./ignitex.sh` una vez haya otorgado los permisos de superusuario con `chmod +x ./ignitex.sh` para instalar todos los paquetes listados.

## Soporte

> [!CAUTION] ⛔ SOPORTE ⛔
>La compatibilidad del proyecto dependerá en gran medida de su SO, ya que el software fue pensado y diseñado para distribuciones derivadas de Debian. Por lo que no se asegura un correcto funcionamiento fuera de esta regla.

---

## Consideraciones

* Agregar "dependencias(`git`, `id`, ~~`whoami`~~)" (detallitos) en la zona FAQ
* `favorite.list`

----

Aquí veremos la disponibilidad de los paquetes y requisitos del sistema o aplicación, según la plataforma en la que se encuentre.

## Recomendación

**Termux en Android**

- Termux: API

### 2. Instale la aplicación Termux: API

Descargue [Termux: API](https://f-droid.org/es/packages/com.termux.api/). No olvide instalarlo.

**GNU/Linux (Debian)**

Ninguno

**Todos lo sistemas (Debian)**

- Git

### Plataformas

* Android (via Termux) 
* GNU/Linux 👨‍💻

## Acciones

Le presentamos las distintas acciones que pude realizar con Ignitex.

#### 🐚️ `-i, --install [<filepath>]`

Primero agregue los nombres de los paquetes aquí.

Archivo: `pkg.list`
```txt
termux-api|API de Termux
repositorio x11|Repositorio X11
figlet|Filett
chafa|chafa
cmatrix|CMATRIZ
```
>Muestra

Nomenclatura: `nombre|etiqueta`

Luego pase el argumento `-i|--install` y espere.

#### 🐚️ `-u, --uninstall [<filepath>]`

Opcionalmente, puede desinstalar todos los paquetes.

Simplemente pase el argumento `-u[--uninstall]` y espere.

Nota: Se desinstalan los mismos paquetes alojados en el archivo de configuración `pkg.list`.

#### 🐚️ `-l, --log`

Puede establecer que su configuración actual sea la configuración predeterminada.

---

## ⚙️ Instalación

Ejecute el fichero `make.sh` pasando el argumento `-i` o `--install`. Se iniciará la instalación de la herramienta.

Esto creará un enlace simbólico nombrado `ignitex` en la ruta `/usr/sbin`.

## ⚙️ Desinstalación

Ejecute el fichero `make.sh` pasando el argumento `-u` o `--uninstall`. Se iniciará la desinstalación de la herramienta.

Esto eliminará el enlace simbólico `ignitex` ubicado en la ruta `/usr/sbin`.

## 📓 Uso

### `-v|--version`

Mostrará por la salida estándar el número de versión de la herramienta. Además, agregará la arquitectura en la que está trabajando.

```
--- Esp.
Versión: 0.0.2 (DEMO)
Trabajando desde: i386
--- Ing.
Version: 0.0.2 (DEMO)
Working from: i386
```

### `-h|--help`

Despliega la ayuda para usuario.

```
Sintaxis:
	ignitex [options] [/path/to/packages.list]
Version:
	0.0.2
```

### `-e|--edit`

Agregue el nombre del paquete, más una etiqueta, en el fichero abierto.
La "sintaxis" es `nombre|etiqueta`.

```
figlet|Filett
chafa|chafa
cmatrix|CMATRIZ
```

> Fichero: `default.list`

### `-i|--install [packages.list]`

De forma predeterminada inicia la instalación de todos los paquetes que están alojados en el fichero `default.list`.

Opcionalmente, puede pasar la ruta de otro fichero con la extensión `.list`.

### `-u|--uninstall [packages.list]`

De forma predeterminada inicia la desinstalación de todos los paquetes que están alojados en el fichero `default.list`.

Opcionalmente, puede pasar la ruta de otro fichero con la extensión `.list`.

---

# ⭐😎 Ignitex

Instale su colección favorita de paquetes en un instante.

1. Ejecute el programa indicando que se realizará una instalación
2. Seleccione la colección de su elección
3. Aguarde un par de segundos y listo; a disfrutar 😉

Las ventajas que ofrece Ignitex son:

* Crear y compartir tu colección de paquetes
* Instalar la colección favorita de tus amigos, compañeros (kits)
* Descargar una colección dedicada a vídeojuegos, lenguajes, informática forense, etcétera

## Uso

A continuación se explica con sencillez las opciones y su uso.

### `-i` / `--install` <file_path>

Utilice la bandera `--install` para instalar los paquetes de una lista. Tome en cuenta que si no pasa como argumento la ruta de un fichero `collection.list` se usará el predeterminado.

`ignitex --install`

Si lo desea, cargue una colección diferente a la predeterminada, para esto ingrese la ruta del fichero.

`ignitex --install [file.list]`


### `-u` / `--uninstall` <file_path>

Utilice la bandera `--uninstall` para desinstalar los paquetes de una lista. Tome en cuenta que si no pasa como argumento la ruta de un fichero `collection.list` se usará el predeterminado.

`ignitex --uninstall`

Si lo desea, cargue una colección diferente a la predeterminada, para esto ingrese la ruta del fichero.

`ignitex --uninstall [file.list]`

### `-v` / `--version`

Conozca la versión actual del software. Útil en caso de que desee comprobar si tiene instalada la última versión.

~~Colección predeterminada de Ignitex. Puede editar el archivo o asignar~~
