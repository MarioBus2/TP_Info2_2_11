# Trábajo Práctico de Informática 2 (2° 11)

## Control de estacionamiento

### Memoria descriptiva

El sistema repesenta un control de estacionamiento, cual tiene el siguiente funcionamiento:

* La barrera se tiene que levantar si hay un coche en la entrada y acciona el botón en la entrada o alguien en el interior acciona el botón.

* La luz roja **R1** se enciende si alguien quiere salir.

* La luz verde **V1** se enciende si hay alguien fuera y nadie dentro.

* La luz roja **R2** se enciende si alguien quiere fuera que quiera entrar.

* La luz verde **V2** se enciende si hay alguien dentro y nadie afuera.

* Si hay dos coches (en la entrada y el interior) y accionan el botón a la vez, las luces deben indicar que la preferencia en para el coche que sale, levantandose la barrera.


Entradas:

* **a** - Detector de coche en la entrada.

* **b** - Botón de apertura fuera del garaje.

* **c** - Detector de coche que quiera salir.

* **d** - Botón de apertura dentro del garaje.


Salidas:

* **M**: Motor de la barrera.

* **R1**, **V1**: Luces roja y verde de la entrada del garaje.

* **R2**, **V2**: Luces roja y verde del interior del garaje.

