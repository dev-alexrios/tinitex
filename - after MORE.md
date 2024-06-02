---
Codename: Ignitex
---
## NOTAS DEL DESARROLLADOR

> [!NOTE] NOTAS DEL DESARROLLADOR 1
> Lee el fichero x con `($(echo $line | sed 's/\|/& /g'))` para interpretar cada línea como un dato tipo tupla.
> Se definen los nombres de variables `ladder`; nivel de la línea en nuestra escalera imaginaria (también sirve para ignorar líneas), `name`; nombre único del paquete dentro del administrador de paquetes (apt, pkg, etc.), `label`; Etiqueta que identifica el paquete en la salida estándar (asignada por el usuario), `tag`; clasificación del paquete (computer forensics, games, languages, etc. \[Se aprecia en la salida estándar\]).
> Discutir modelo con o sin íconos. 😬
> Versión y (…?)
> Cortafuegos: Tipos de SO válidos (para los que se desarrolló el software).
> Si pasa el argumento `#:store/hacking.list` Ignitex buscará el fichero solicitado desde la ruta en la que reside el proyecto. Esto es así porque se reemplaza `#:` por (ejemplo) `/home/username/path/to/ignitex/collections/store/hacking.list`.
> Nuevas exxpresiones de versionado: `v3.0.0` o `v3.0.2`


> [!IMPORTANT] NOTAS DEL DESARROLLADOR 2
> 🔷 Con `dpkg --print-architecture` identifica los paquetes válidos para el SO.
> 🔷 Ignore las líneas iniciadas con `#` mejorará el rendimiento.
> 🔷 Utilice la metodología **KISS**.
> 🔷 *Refactoring* al código del proyecto (siga buenas prácticas).
> 🔷 Con `npm view nodemon &> /dev/null && echo "$?"` averigüe si el paquete dado está instalado.

---

## CHECKSUM

| SHA256 | File |
|:------:|:----:|
| 3cc4ef1e42e9140cd56fa9ea021f5ae88dc342883e82a79a7e6d8c4a276ef127 | ./pkg.list |
| e647360d2c1bd61654a41e692cd372cec3a1a8a7cf61817312bfc5b539f2cbaa | ./pkg.sh |

---

- `/` Tree Map
- assets/
	+ mind_map.pdf
	+ icon.png
	+ icon.svg
- components/
	+ animation.sh
	+ notice.sh
	+ platform.sh
	+ store.sh
	+ system.sh
	+ uninstall.sh
- models/
- store/
	+ games.list
	+ computer_forensics.list
	+ languages.list
- process.log
- managers.conf
- engine.sh
- ignitex.sh
- index.sh
- make.sh

---

## ⭐😎 Select Packages

Los tipos de **sistemas operativos** que manejamos son:

- Android: `android`
- GNU/Linux: `gnulinux`
- Todos los anteriores: `*`

Los gestores de 

## Revisión

```bash
pkg install pciutils # 💢😔 Creo que el teléfono debe estar rooteado
pkg install xdg-utils # ❗ XDG Utils
pkg install glib-bin # ❗ GIO
# Solamente si el dispositivo está rooteado
# START - Formateo
pkg install blk-utils # ⭐
pkg install ntfs-3g # ⭐
pkg install e2fsprogs # ⭐
pkg install dosfstools # ⭐
pkg install mtd-utils
# END - Formateo
pkg install tsu # 💢 Simular superusuario
pkg install proot # ⭐❓ Instalar Distros
```

## Author

```bash
# 'APT' FOR ALL DEVICES
#| STANDARD
#| BETTER AND MORE
#| DEVELOPMENTS
#| HACKING
# 'APT' ONLY FOR ANDROID
# STANDARD
# LANGUAGES
# 'APT' ONLY FOR GNU/LINUX
# STANDARD
# 'NPM' FOR ALL DEVICES
# 'NPM' ONLY FOR ANDROID
# 'PIP' FOR ALL DEVICES
# 'PIP' ONLY FOR GNU/LINUX
```
