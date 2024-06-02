---
Name: Ignitex
Codename: "@ignitex"
tags:
  - "#Package"
  - "#Terminal"
Branches:
  - Informática
  - Software
author: Alex Ríos
Encrypt: Base64
---
# IGNITEX

![Release](https://img.shields.io/badge/release-v2.0.5-blue?logo=github) ![Edition](https://img.shields.io/badge/edition-LTS-green) ![Main language](https://img.shields.io/badge/language-Shell-red?logo=shell) ![License](https://img.shields.io/badge/license-MIT-purple)

>[!IMPORTANT] IMPORTANTE
>Vea la demostración pública receptiva (demo) haciendo [clic aquí.](https://github.com/dev-alexrios/ignitex-demo)

## ℹ️ Descripción

Instale múltiples paquetes con rapidez y eficacia, sin convertir su pantalla en alguna especie de intento fallido de arte ASCII.

> [!CAUTION] SOPORTE
> El proyecto se diseñó para la distribución Debian y derivados.
>
>No obstante, esta versión cuenta con soporte para dispositivos Android que utilizan el emulador de terminal [Termux](https://f-droid.org/es/packages/com.termux) (basado en Debian).
>
>No se garantiza la compatibilidad con otros dispositivos y/o distribuciones.

## 🔽 Descarga

Clona el repositorio en tu máquina:

```sh
git clone https://github.com/dev-alexrios/ignitex.git
```

## ⚙️ Instalación

Ejecute el fichero `make.sh` pasando el argumento `-i` o `--install` para dar inicio a la instalación de la herramienta.

**Evento:** Se creará un enlace simbólico nombrado `ignitex` en la ruta `/usr/sbin`.

## ⚙️ Desinstalación

Ejecute el fichero `make.sh` pasando el argumento `-u` o `--uninstall` para dar inicio a la desinstalación de la herramienta.

**Evento:** Se eliminará el enlace simbólico `ignitex` ubicado en la ruta `/usr/sbin`.

## ➕ Instalar paquetes

…

## ➖ Desinstalar paquetes

…

Fichero: `default.list`

## 📦 Dependencias

Las dependencias mínimas son el conjunto de instrucciones `whoami`, `grep`, `git` y `dpkg`.

Verifique si los paquetes están instalados:

`<package_name> --version`

En caso de que no estén instalados, puede instalarlos así:

`apt install <package_name> -y`

## ❔️ Preguntas frecuentes

- [ ] …

## 🙌 Contribuyendo

Las contribuciones son las que hacen que nuestra comunidad de código abierto sea un lugar increíble para aprender, inspirar y crear. Cualquier contribución que hagas es **muy apreciado**.

> Comunícate conmigo a través del [**grupo dedicado** vía Telegram.](https://t.me/+EFIuJpLWkvphNTEx)

Si tiene una sugerencia que mejoraría esto, bifurque el repositorio y cree una solicitud de extracción. También puede simplemente abrir un problema con la etiqueta "mejora". ¡No olvides darle una estrella al proyecto! ¡Gracias de nuevo!

1. Fork el Proyecto
2. Crea tu Rama de Características (`git checkout -b feature/AmazingFeature`)
3. Cometer sus Cambios (`git commit -m 'Add some AmazingFeature'`)
4. Empujar a la Rama (`git push origin feature/AmazingFeature`)
5. Abra una Solicitud de extracción

## 🪙️ Donaciones

Por favor apoya este proyecto de código abierto y a mi persona mediante el servicio de Patreon.

## 📜 Licencia

> Distribuido bajo una licencia propia. Ver `LICENSE.md` para más información.

Verifique en nuestra [**licencia**](LICENSE.md) si el proyecto encaja en sus expectativas de uso.
