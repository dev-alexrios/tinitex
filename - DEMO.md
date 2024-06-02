---
Date & Time: 2022-01-07T04:03:00
Finished: 
Name: Ignitex Demo
Codename: ignitex-demo
author: Alex Ríos
Branches:
  - Informática
  - Software
tags:
  - Terminal
Encrypt: Dot
OS:
  - Debian
---
# ⭐😎 IGNITEX DEMO

![Release](https://img.shields.io/badge/release-v0.1.3-blue?logo=github) ![Edition](https://img.shields.io/badge/edition-Demo-green) ![Main language](https://img.shields.io/badge/language-Shell-red?logo=shell) ![License](https://img.shields.io/badge/license-Undefined-purple)

Instale múltiples paquetes con rapidez y eficacia, sin convertir su pantalla en alguna especie de intento fallido de arte ASCII.

> [!IMPORTANT] IMPORTANTE
> Software con funciones limitadas
> Vea el modelo "comercial" haciendo [clic aquí.](https://github.com/dev-alexrios/ignitex)

## ℹ️ Descripción

Instale su colección favorita de paquetes en un instante.

Seleccione una colección y ejecuta la aplicación sobre ésta. Un par de segundos después y listo; a disfrutar. 😉

* Crear y compatir tu colección de paquetes.
* Instalar la colección favorita de tus amigos.
* Descargar una colección dedicada; videojuegos, lenguajes, informática forense, etcétera.

>Instale múltiples paquetes con rapidez y eficacia, sin convertir su pantalla en alguna especie de intento fallido de arte ASCII.

## ℹ️ Descripción general 

- Características
- Descarga
- Uso
	- `-i` / `--install` · Instalar paquetes
	- `-u` / `--uninstall` · Desinstalar paquetes
	- `-l` / `--log` · Registro (del software)
	- `-a` / `--about` · Sobre (el software)
	- `-U` / `--update` · Actualizar (el software)
	- `-V` / `--verborse` · Modo verboso
	- `-v` / `--version` · Versión
	- `-h` / `--help` · Ayuda

## 🔎️ Características

* Versión: 2.0.5 (LTS) --> 2.1.0 (Experimental) 
* Distribución: Debian
* Edición: `Termux` y `Linux`
* Modelo: Ilimitado / Limitado (Demo)
* Personalizable: Sí
* Portable: Sí

> [!CAUTION] PLATAFORMAS
> La compatibilidad del proyecto dependerá en gran medida de su SO, ya que el software fue pensado y diseñado para distribuciones basadas en Debian. Por lo tanto, no se asegura un correcto funcionamiento fuera de esta regla.

---

## 🔽 Descarga

¡Clona el repositorio en tu máquina!

```bash
# Clona el repositorio (proyecto) en tu máquina.
git clone https://github.com/dev-alexrios/ignitex.git
# Entra en el directorio del proyecto.
cd ./ignitex-demo
```

> [!IMPORTANT] Permiso de ejecución
> Conceda permiso de ejecución al fichero `make.sh` con `chmod +x ./make.sh` desde el «superusuario».

---

### ⚙️ Instalación

Ejecuta el fichero `make.sh` pasando el argumento `-i` o `--install` para iniciar la instalación del proyecto.

```bash
./make.sh --install
```

**Evento:** Se creará un enlace simbólico nombrado `ignitex` en la ruta `/usr/sbin`.

---

### ⚙️ Desinstalación

Ejecuta el fichero `make.sh` pasando el argumento `-u` o `--uninstall` para iniciar la desinstalación del proyecto.

```bash
./make.sh --uninstall
```

**Evento:** Se eliminará el enlace simbólico `ignitex` ubicado en la ruta `/usr/sbin`.

---

## Uso

### `-v` / `--version`

- Retorna: `<string>`

Mostrará por la salida estándar el número de versión de la herramienta.

```
--- Esp.
Versión: 0.0.2 (DEMO)
--- Ing.
Version: 0.0.2 (DEMO)
```

### `-h` / `--help`

- Retorna: `<string>`

Despliega la ayuda para usuario.

```
Sintaxis:
	ignitex [options] [/path/to/packages.list]
Version:
	0.0.2 (DEMO)
```

### `-e` / `--edit`

- Evento: `<open_file>`

Agregue el nombre del paquete, más una etiqueta, en el fichero abierto.

La estructura es `paquete|etiqueta`.

```
figlet|Filett
chafa|chafa
cmatrix|CMATRIZ
```

> Fichero: `default.list`

### `-i` / `--install`

- Fichero: Recibe un fichero que, en esencia, es la lista de paquetes a instalar.
- Evento: `<read_file>`
- Proceso: `<process_file>|…`
- Retorna: `<string>`

De forma predeterminada inicia la instalación de todos los paquetes que están alojados en el fichero `default.list`.

Opcionalmente, puede pasar la ruta de otro fichero con la extensión `.list`.

### `-u` / `--uninstall`

- Fichero: Recibe un fichero que, en esencia, es la lista de paquetes a desinstalar.
- Evento: `<read_file>`
- Proceso: `<process_file>|…`
- Retorna: `<string>`

De forma predeterminada inicia la desinstalación de todos los paquetes que están alojados en el fichero `default.list`.

Opcionalmente, puede pasar la ruta de otro fichero con la extensión `.list`.

> [!TIP] NOTA
> Para ambos casos (instalación y desinstalación) le recomendamos crear un directorio nombrado `collections` en la ruta raíz del proyecto. Dicho directorio podrá ser reutilizado en futuras versiones del software, ya que se es consciente de su **posible** existencia.

## 📦 Dependencias

Las dependencias mínimas son el conjunto de instrucciones `whoami`, `grep`, `git` y `dpkg`.

Verifique si los paquetes están instalados:

`<package_name> --version`

En caso de que no estén instalados, puede instalarlos así:

`apt install <package_name> -y`

## 🙌 Colaboración

Comunícate conmigo a través del [**grupo dedicado** vía Telegram.](https://t.me/+EFIuJpLWkvphNTEx)

## 🪙️ Donaciones

Por favor apoya este mini-proyecto de código abierto y a mi persona mediante el servicio de Patreon.

## Preguntas frecuentes

…

## 📜 Licencia

Verifique en nuestra [**licencia**](LICENSE.md) si el proyecto encaja en sus expectativas de uso.

* 2022-2024 © Alex Ríos
* Todos los derechos reservados.
