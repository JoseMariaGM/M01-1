**MBR**

**Master Boot Record** conocido como registro de arranque maestro, és el primer registro del disco duro, el cual contiene un programa ejecutable y una tabla donde estan definidas las particiones del disco duro, donde se emplea para el arranque del sistema operativo.

**¿Estructura del MBR?**

El MBR se refiere al sector de arranque de **512 bytes**

**Código Máquina** és el gestor de arranque, és un lenguaje compuesto por un conjunto de instrucciones.

Ocupa **446 bytes**

**Tabla de particiones** és donde se almacena toda la información básica sobre la partición:
1. Si es arrancable o no
2. Formato
3. Tamaño
4. Sector de Inicio

Ocupa **64 bytes**, conteniendo 4 registros de 16 bytes.

**Firma de unidad arrancable** ocupa **2 bytes** y esta basado en el sistema hexadecimal.

Parte | Peso
----------------- | -------------------
Gestor de arranque| 446 bytes
Tabla de particiones | 64 bytes 
Firma de la unidad | 2 bytes



