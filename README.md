View this project on [CADLAB.io](https://cadlab.io/project/30199). 

# Projecte retrovisors 

>**Autors: Biel Yáñez, Ivan López** 
>**Versió: Esquemático 2.0**

----------

## Objectiu

>PCB per controlar els retrovisors


## Diagrama de blocs


### Descripció/funcionalitat de cada bloc

  Alimentació: donar els voltatjes de alimentació regulats
  CAN: habilitar el canal CAN para comunicarse con otros 
  Sensor: detectar objetos en el angulo muerto del coche
  Drivers Motor: controlar los motores bidireccionales a partir de las señales del controlador
  MICRO: Recibir señales de los sensores y emitir las señales correspondientes a los drivers
  Finalcarrera: detectar cuando los retrovisores llegan a su límite axial
  Botonera: conjunto de botones para que el usuario interactue con el sistema
  Programador: entrada del PIC para poder programar el microcotrolador
-----------

## Requisits / Especificacions

  * Alimentació; 12V, despues del buck 5V, regulada 3.3V
  * Microcontrolador PIC32MX250F128D
  * ...

-----------

## Components

| Descripci&#243; | Ref | Package |Datasheet | Prove&#239;dor | Preu | Unitats |
| --- | --- | --- | --- | ---| --- | --- |
| Microcontrolador | PIC32MX250F128D | TQFP-44 |[Datasheet](https://www.mouser.es/datasheet/2/268/PIC18F27_47_57Q83_Preliminary_Data_Sheet_40002265B-2887591.pdf) | [Mouser](https://www.mouser.es/c/?q=PIC18F27Q83-I%2FSO)| 2,17&euro;| 1x |
| XTAL-Ressonador | CSTCR7M99G53-R0 | SMD |[Datasheet](https://www.mouser.es/datasheet/2/281/p16e-522700.pdf) | [Mouser](https://www.mouser.es/ProductDetail/Murata-Electronics/CSTCR7M99G53-R0?qs=Zd9RUO93%2Fo7cnwzsujIkpA%3D%3D)  | 0,27&euro; | 1x |

-----------

## Software

### Eines:

  * KiCad 9.0 o superior
  * 

### Configuraci&#243; :

  * 

### Funcionalitats:

  * Posicionar los cristales y bolegar los retrovisores
  * Detectar y avisar de los objetos en el angulo muerto
  * Hacer que los retrovisores no se empañen.

-----------


## Historial de canvis

| Data | Autor     | Branch | Versi&#243; | Descripci&#243; |
| --- | --- | --- | --- | --- |
|  11/03/2026 | Ivan López | Master | initial commit | Primera diagrama de bloques i seleccion de componentes |
|  18/03/2023 | Biel Yáñez | Editor | he añadido todo | primera version de esquematico y segunda versión del diagrama de bloques| 
|  25/03/2023 | Biel Yáñez | Editor | cambio en los drivers y conexiones al pic | segunda versión de esquematico| 