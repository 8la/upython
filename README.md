# upython

## Herramientas de terminal

### Linux

* picocom
* minicom

#### Usando *picocom*

```bash
picocom /dev/ttyUSB0 -b 115200
```
* <kbd>Control</kbd>-<kbd>a</kbd> <kbd>Control</kbd>-<kbd>x</kbd> SALIR
* <kbd>Control</kbd>-<kbd>a</kbd> <kbd>Control</kbd>-<kbd>c</kbd> LOCAL ECHO
* <kbd>Control</kbd>-<kbd>d</kbd> NODEMCU SOFT REBOOT



### MacOS

Para conectarnos a la placa, usaremos _coolTerm_.

### CoolTerm

Para descargar CoolTerm Puede hacerse desde el siguiente [enlace](http://freeware.the-meiers.org/CoolTermMac.zip)

Una vez descargado e instalado, se configurará el puerto a utilizar; pulsando en el botón _Options_.

![opcionesCoolTerm](imagenes/optioncoolTerm.png)

Una vez configurado el puerto (con el que nos aparece en nuestro MAC) y configurado el baudrate a _115200_. Pulsaremos OK y al botón _connect_. Apareciendo el promt de Python.

![coolTerm](imagenes/coolTerm.png)
### Windows


## Pinout del NodeMCU

![alt text](https://docs.bsfrance.fr/documentation/10663_NODEMCU_V3_CH340/Pinout.png "Esquema de pines para la NodeMCU")
