# hardbrick-harpia (solución)

![hardbrick-harpia](https://image.ibb.co/dCAgi8/31961133_2064776407069436_6641616660643971072_n.jpg?raw=true)

> **Nota:** éste proceso es bajo tu responsabilidad, no me hago cargo de nada (no hay de que preocuparse, funciona!)

El Hardbrick es ocasionado principalmente cuando se apaga durante una actualización de firmware, el teléfono se queda a medio proceso y sin un sistema operativo completo, por lo tanto no enciende.

La solución está aqui, **lee todo antes de, para que entiendas que se va a hacer**, vamos a reinstalar un bootloader no original y bloqueado (éste no se puede desbloquear con el metodo de motorola que conocemos), posteriormente vamos a instalar un firmware especifico con unos comandos especificos, descargaremos todo junto para eviatar cualquier duda. Tardará al arrancar pero finalmente lo hará!
> **Nota:** si solo estás en modo bootloader y quieres un firmware ve al paso 3
# Instrucciones
## 1.- Preparar la pc (windows 7 - 10)
- Descargar y descomprimir [Qualcommdrv.zip](google.com), y abrir posteriormente la carpeta que necesite su sistema operativo 32 o 64 bits. Instala el ejecutable dpinst64.exe ó dpinst32.exe
> La neta quien usa 32bits en pleno 2018 xd

- Descargar e instalar los [drivers de motorola](http://www.motorola.com/getmdmwin)

## 2.- Instalar el nuevo bootloader
- Descomprimimos el  [blankflash.zip](https://drive.google.com/open?id=1l7hhsjeT4MDUQQLGNr6Ti4TA4_xnl5Ip)  y dejará varios archivos, entre ellos, **blankflash.bat**, conectamos el celular a la PC con el USB y damos doble clic sobre blankflash.bat
> Si no detecta correctamente, desconectar el celular e intentar nuevamente conectar el celular y abrir blankflash.bat (por lo menos la pc tiene que hacer un ruido de que lo reconoce)
> Si aun no lo reconoce manten presionado el boton de power hasta que escuches el sonido de cuando lo conectas a la pc, abre varias veces el blankflash.bat si es necesario

## 3.- Instalar el firmware específico
> Una vez reconocido el moto g4 play ya tendremos instalado el bootloader no original y ahora vamos a acceder al modo bootloader de manera normal (power y vol- al mismo tiempo 3 segundos)
- Descargamos la [carpeta maestra](google.com) con todo lo necesario, incluye el firmware especifico para que funcione, los comandos especificos y el plataform-tools
- Finalmente solo ejecutamos el archivo **flash rom stock.bat**, dar enter al final del proceso para que se reincie y listo, tendría que estar iniciando en la rom stock (éste reincio tarda mas que el normal, sean pacientes)
### Dudas por twitter [@luisrcdev](https://twitter.com/luisrcdev)
Genial! [Y si me disparas un café? <3](https://paypal.me/luisrcdev)
