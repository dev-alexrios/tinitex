# 🤴 Jerarquía y Estructura 🏗️

[[PKG-IU README/README|↩️ Regresar a la página principal]]

La jerarquía y estructura del fichero de configuración se distribuye de la siguiente manera:

- Nivel cero (Gestores):
- `ladder|platform|manager`
- Nivel uno (Paquetes):
- `ladder|classify|package|label`

- La jerarquía se expresa mediante la escalera.
- La estructura se expresa mediante el resto de los elementos.

### Escalera (ladder)

Sirve para distinguir los gestores de paquetes de los paquetes en sí. Para ello existen los selectores `0` y `1`, correspondientemente.

#### Nivel cero

Reservado para los selectores `platform` y `manager`, que corresponden al tipo de plataforma (sistema operativo) y gestores de paquetes.

#### Nivel uno

Reservado para los selectores `classify`, `package` y `label`; tipo de clasificación del paquete, nombre del paquete (nombre único reservado en el gestor de paquetes) y, etiqueta que se mostrará en la salida estándar.

### Plataforma (platform)

Los indicadores para plataformas sirven para distinguir los paquetes válidos para las mismas. Actualmente cuenta con los siguientes:

- `gnulinux`: Sólo para Distribuciones GNU/Linux
- `android`: Sólo para Termux (Android)
- `*`: Para cualquier SO
