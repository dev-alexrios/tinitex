> [!CAUTION] Plataformas
> La compatibilidad del proyecto dependerá en gran medida de su SO, ya que el software fue pensado y diseñado para distribuciones derivadas de Debian. Por lo que no se asegura un correcto funcionamiento fuera de esta regla.

## Instalar paquetes

- Nivel `0`
	- Para: Administradores de paquetes
	- Lógica: Escalera, nombre, dispositivo
	- Representación: `ladder|name|device`
- Nivel `1`
	- Para: Paquetes
	- Lógica: Escalera, nombre, etiqueta, clase
	- Representación: `ladder|name|tag|class`

```
# ALL DEVICES (DEBIAN)
0|*|apt
1|nmap|NMap|Hacking
1|htop|HTop|Monitoring
1|chafa|Chafa|Image

# ONLY GNU/LINUX (DEBIAN)
0|gnulinux|apt
1|netcat-traditional|NetCat Tradicional|Red

# ONLY ANDROID (TERMUX)
0|android|apt
1|netcat-openbsd|NetCat OpenBSD|Red
```

Fichero: `default.list`

###### Indicadores de estado

Estado del método o función:

* 👨‍💻 En desarrollo
* 🧑‍🔧 En mantenimiento
* 🧑‍🏭 Por añadir

