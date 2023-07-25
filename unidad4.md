# UNIDAD IV: BIOS – Disco Duro

## BIOS

### ¿Que es el BIOS?

La BIOS (Basic Input Output System) es un conjunto de programas que se encuentran en un chip en la placa base de una computadora. Se encarga de realizar un auto testeo de hardware inicial antes de ejecutar el sistema operativo, permite modificar opciones que se registrarán en la memoria CMOS y se encarga de la interfaz de bajo nivel entre el microprocesador y algunos periféricos.

### ¿Para qué sirve la BIOS en la PC?

La BIOS en la PC sirve para realizar un auto testeo de hardware inicial antes de ejecutar el sistema operativo, lo que permite detectar y solucionar problemas de hardware. También se encarga de la secuencia de arranque, es decir, en qué dispositivo de almacenamiento está el sistema operativo y cómo arrancar desde él. Además, permite identificar y configurar componentes de hardware como los discos duros, dispositivos de almacenamiento externo, el procesador o la memoria RAM. Desde la BIOS, se pueden modificar los parámetros de funcionamiento del procesador para desactivar núcleos, activar y desactivar HyperThreading, o modificar su velocidad para hacer Overclock.

### CMOS – Pila del CMOS

La CMOS (Complementary Metal Oxide Semiconductor) es un tipo de memoria que se utiliza para guardar los datos básicos de hardware y de configuración, como la información sobre los discos duros, la fecha y la hora. Para que esa información se mantenga, es preciso que la CMOS siempre tenga corriente eléctrica.

La pila del CMOS es una pequeña batería ubicada en la placa base que proporciona energía a la CMOS cuando el ordenador está apagado y/o desenchufado. La pila del CMOS es necesaria para mantener la información almacenada en la CMOS, como la fecha y la hora, cuando la computadora está apagada. Si la pila del CMOS se agota, la información almacenada en la CMOS se perderá y la computadora puede tener problemas para arrancar.

### Programas del BIOS

El BIOS (Basic Input Output System) es un conjunto de programas que se encuentran en un chip en la placa base de una computadora.

Hay tres programas en este chip BIOS:

1. POST (Power On-Self Test): conjunto de instrucciones para llevar a cabo un auto testeo de hardware inicial (teclado, video, procesador, memoria, etc.) antes de comenzar a ejecutar el Sistema Operativo.

2. CMOS SETUP: mediante este programa es factible modificar las opciones que luego se registrarán en la memoria CMOS, como ser la fecha y hora, activar/desactivar componentes integrados, cambiar el orden de unidades de inicio del sistema, contraseña de acceso, etc.

3. BIOS (Basic Input Output System): se encarga de la interfaz de bajo nivel entre el microprocesador y algunos periféricos (Input/Output). Recupera, y después ejecuta, las instrucciones del MBR (Master Boot Record), registradas en un disco rígido, para lanzar las instrucciones del sistema operativo.

### BIOS: Arranque y activacion del S.O.

El arranque de una computadora actual tiene dos fases: la fase de arranque del hardware (POST) y la fase de arranque del SO (BIOS).

Durante la fase de arranque del hardware, el BIOS realiza un auto testeo de hardware inicial (POST) para detectar y solucionar problemas de hardware. El POST verifica que los componentes de hardware, como el teclado, el video, el procesador y la memoria, estén funcionando correctamente antes de comenzar a ejecutar el sistema operativo.

Una vez que el POST ha finalizado, el BIOS carga en memoria el sistema operativo (SO) desde el dispositivo de almacenamiento que se ha configurado como el dispositivo de arranque. El BIOS recupera, y después ejecuta, las instrucciones del MBR (Master Boot Record), registradas en un disco rígido, para lanzar las instrucciones del sistema operativo.

El MBR es un programa encargado de leer la tabla de particiones y ceder el control al sector de arranque de la partición activa. El sector de arranque es el primer sector de la partición activa y contiene el código necesario para cargar el sistema operativo.

## La UEFI como evolución del BIOS

La UEFI (Unified Extensible Firmware Interface) es una tecnología que ha evolucionado a partir del BIOS (Basic Input Output System) y que se utiliza para arrancar el sistema operativo y controlar el hardware de la computadora.

A diferencia del BIOS, que es un conjunto de programas que se encuentran en un chip en la placa base de una computadora, la UEFI es un firmware que se ejecuta en modo de 32 o 64 bits y se encuentra en una memoria flash en la placa base.

La UEFI ofrece varias ventajas sobre el BIOS, como una interfaz gráfica de usuario más avanzada, soporte para discos duros de más de 2 TB, arranque más rápido, soporte para dispositivos de almacenamiento externos, y una mayor seguridad.

Además, la UEFI es más flexible y extensible que el BIOS, lo que significa que los fabricantes de hardware pueden agregar nuevas características y funcionalidades a la UEFI sin tener que reemplazar todo el firmware.

### Caracteristicas de BIOS y UEFI

Características del BIOS:

- Es un conjunto de programas que se encuentran en un chip en la placa base de una computadora.

- Se ejecuta en modo de 16 bits.

- Tiene una interfaz de usuario basada en texto que se controla mediante el teclado.

- Es compatible con la mayoría de los sistemas operativos y hardware.

- Es fácil de usar y configurar.

- Es estable y confiable.

- Es un estándar de la industria.

Características de la UEFI:

- Es un firmware que se ejecuta en modo de 32 o 64 bits y se encuentra en una memoria flash en la placa base.

- Tiene una interfaz gráfica de usuario avanzada que se controla mediante el teclado y el ratón.

- Soporta discos duros de más de 2 TB.

- El arranque es más rápido que con el BIOS.

- Tiene soporte para dispositivos de almacenamiento externos.

- Tiene una funcionalidad de seguridad avanzada, como Secure Boot.

- Es más flexible y extensible que el BIOS, lo que significa que los fabricantes de hardware pueden agregar nuevas características y funcionalidades a la UEFI sin tener que reemplazar todo el firmware.

- No es compatible con algunos sistemas operativos y hardware antiguos.

## Disco Duro

### Particiones

Particiones son divisiones lógicas de un disco duro que permiten organizar datos y cada partición puede tener un sistema de archivos distinto. Hay tres tipos de particiones: primarias, lógicas y extendidas . La configuración de la tabla de particiones y la estructura física y lógica del disco duro son importantes para entender las particiones.

- Particiones primarias: son las particiones principales del disco duro y se utilizan para instalar sistemas operativos y almacenar archivos de datos. Cada disco duro debe tener al menos una partición primaria para ser utilizable .

- Particiones lógicas: son divisiones lógicas de una partición extendida y se utilizan para organizar datos dentro de una partición. Las particiones lógicas no existen por sí mismas, sino que se definen dentro de una partición extendida .
- Particiones extendidas: son particiones especiales que se utilizan para crear particiones lógicas. Las particiones extendidas no pueden contener datos directamente, pero pueden contener una o más particiones lógicas .

### ¿Que cantidad de Particiones puede tener un Disco Duro?

La cantidad de particiones que puede tener un disco duro depende de la configuración asignada a la tabla de particiones del disco duro. La tabla de particiones se almacena en un espacio reservado al principio del disco duro y sirve para gestionar las particiones existentes en el disco duro. Hay dos tecnologías para configurar la tabla de particiones: MBR (Master Boot Record) y GPT (Tabla de particiones GUID). La tecnología MBR, que es la más antigua, permite crear hasta cuatro particiones primarias o tres particiones primarias y una partición extendida. La tecnología GPT, que es la sucesora del MBR, permite crear hasta 128 particiones primarias.

### Caracteristicas MBR Y GPT

MBR (Master Boot Record):
- Es la tecnología más antigua para configurar la tabla de particiones.
- Permite crear hasta cuatro particiones primarias o tres particiones primarias y una partición extendida.
- No es compatible con discos duros de más de 2 TB.
- Es leído y ejecutado por la BIOS al encenderse la PC .

GPT (Tabla de particiones GUID):
- Es la tecnología sucesora del MBR.
- Permite crear hasta 128 particiones primarias.
- Es compatible con discos duros de más de 2 TB.
- Tiene una mayor tolerancia a errores y una mayor protección de datos.
- Es leído y ejecutado por la UEFI al encenderse la PC .

### DISCO DURO - HDD (Estructura Física del Disco Duro, Cluster)

La estructura física del disco duro se compone de platos (discos) magnéticos que giran a alta velocidad y cabezales de lectura/escritura que se mueven sobre los discos para leer o escribir datos. Los datos se almacenan en pistas circulares en los discos, y cada pista se divide en sectores. Un sector es la unidad básica de almacenamiento en un disco duro y típicamente tiene un tamaño de 512 bytes o 4 KB. Los sectores se agrupan en bloques llamados clústeres, que son la unidad básica de asignación de espacio en un disco duro. El tamaño de un clúster depende del tamaño del disco duro y del sistema de archivos utilizado, pero típicamente es de 4 KB o más. El tamaño de clúster más común es de 4 KB, lo que significa que cada archivo ocupa al menos un clúster, incluso si es más pequeño que 4 KB .

### Formateo Físico de un disco duro

El formateo físico o de bajo nivel de un disco duro es un proceso que divide los platos del disco duro en sus componentes físicos básicos, como pistas, sectores y cilindros. Este tipo de formateo se realiza en la fábrica durante la fabricación del disco duro y no es necesario realizarlo en condiciones normales de uso. El formateo físico de un disco duro se utiliza principalmente para reparar sectores defectuosos en el disco duro o para eliminar completamente todos los datos del disco duro. Sin embargo, este proceso es muy complejo y puede dañar permanentemente el disco duro si se realiza incorrectamente. Por lo tanto, no se recomienda realizar el formateo físico de un disco duro a menos que sea absolutamente necesario y se tenga experiencia en la realización de este proceso .

### Formateo Lógico de una Partición del disco duro

El formateo lógico o de alto nivel de una partición del disco duro es un proceso que se aplica sobre las particiones del disco duro, es decir, sobre los discos o unidades lógicas. Durante el formateo lógico se crea una estructura lógica en la partición, la cual consiste principalmente en la división del disco en cuatro zonas: sector de arranque, tabla de localización de archivos (FAT), directorio raíz y espacio de datos para el usuario. El objetivo de esta división es la organización lógica de los datos dentro del disco de forma que puedan ser leídos y grabados. Cada área del disco tiene una misión especial y un tamaño variable según la capacidad del disco. El sector de arranque de la partición (el primero de la partición) contiene información relativa a la misma. Si la partición tiene instalado un sistema operativo, este sector se encarga de arrancarlo. El formateo lógico es necesario para poder utilizar una partición del disco duro y se realiza mediante el sistema operativo o un software especializado .

## Sistema de archivos

El sistema de archivos es una estructura que necesita el sistema operativo para gestionar la información del disco. Es una especie de índice que informa sobre la posición de cada archivo en el disco (posición del clúster). Por lo tanto, el sistema de archivos se basa en la administración de clúster, la unidad de disco más pequeña que el sistema operativo puede administrar. El sistema de archivos desempeña tres funciones principales: control del espacio disponible y asignado, mantenimiento de directorios y nombres de archivos, y control del lugar donde las distintas porciones de cada archivo se encuentran físicamente almacenadas en el disco. El sistema de archivos es esencial para el correcto funcionamiento del sistema operativo y de las aplicaciones que se ejecutan en él, ya que permite acceder a los archivos de manera rápida y eficiente .

### Tipos de Sistemas de Archivos

Hoy en día existen varios sistemas de archivos en uso. Algunos de los sistemas de archivos más comunes son:
- Tabla de Asignación de Archivos (FAT) o FAT16 (W9x, NT, Me)
- Tabla de Asignación de Archivos 32 (FAT32) (W98,NT, Me, XP)
- Sistema de Archivos de Nueva Tecnología (NTFS) (NT, 2000,XP, W8, w10)
- Sistema de Archivos de Alto Rendimiento (HPFS)
- Linux Ext2 o EXT3
- UNIX

Cada uno de estos sistemas de archivos tiene sus propias características y ventajas, y se utilizan en diferentes sistemas operativos y dispositivos de almacenamiento. Es importante conocer los diferentes tipos de sistemas de archivos para poder elegir el más adecuado para cada situación .
