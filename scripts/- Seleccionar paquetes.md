# ⭐😎 Tinitex

[[Preset Termux|Regresar a la página principal]]

## Seleccionar paquetes

Para crear o editar una colección de paquetes debe tener en cuenta las pautas siguientes:

### Sintaxis

> [!NOTE] NOTAS
> 1. Rectifique el nombre de cada paquete; asegúrese que esté bien escrito.
> 2. Verifique que el paquete existe en el administrador de paquetes elegido.
> 3. Adicione al final del fichero de colección una nueva línea vacía.

```
level|selector|manager
level|name|label
```

- **`ladder`**
	- **`0`:** Indica que es encabezado.
	- **`1`:** Indica que es cuerpo.
- **`platform`**
	- **`android`:** Específica los paquetes para Android.
	- **`gnulinux`:** Específica los paquetes para GNU/Linux.
	- **`*`:** Selecciona todos los paquetes.
- **`manager`**
	- **`apt`:** Utiliza el administrador de paquetes apt de Debian.
	- 🧪 **`npm`:** Utiliza el administrador de paquetes npm de Node.js.
	- 🧪 **`pip`:** Utiliza el administrador de paquetes pip de Python.
- **`classify`:** Específica la clasificación del paquete.
- **`package`:** Específica el nombre del paquete.
- **`label`:** Específica la etiqueta del paquete.


> [!IMPORTANT] ÍCONOS
> 🧪 -> Experimental

### Ejemplos

Si desea indicar en su fichero de colección que una determinada lista de paquetes pertenece al campo Android, GNU/Linux o General (todo lo anterior), siga las indicaciones siguientes:

#### Caso 1 - General

Indicar que la instalación se realice en cualquier caso.

```
?|*|?
?|?|?
```

#### Caso 2 - Termux

Indicar que la instalación se realice en Termux.

```
?|termux|?
?|?|?
```

#### Caso 3 - Linux

Indicar que la instalación se realice en Linux.

```
?|linux|?
?|?|?
```

### Todo en uno

Aquí puede apreciar un ejemplo claro de como crear una colección que cumpla con las normas sintácticas y a su vez definir una lista de paquetes para cada administración de paquetes. Esto incluye una lista que utiliza el selector general `*`.

```
0|termux|apt
1|netcat-openbsd|NetCat Open BSD

0|linux|apt
1|netcat-traditional|NetCat Traditional

0|*|apt
1|neofetch|NeoFetch
```
