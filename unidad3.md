# HARDWARE

## Placa madre

La placa madre es el elemento principal de toda PC, junto con el microprocesador. La placa madre funciona como una placa "materna" que toma la forma de un gran circuito impreso con conectores para tarjetas de expansión, módulos de memoria, el procesador, etc.

## Chipset

Coordina el intercambio de toda la información que circula por los buses. El chipset está básicamente conformado por dos chips: el Puente Norte (northbridge) y el Puente Sur (southbridge).

El Puente Norte se encarga del bus del sistema y se comunica directamente con el procesador, mientras que el Puente Sur se encarga del bus de expansión y se comunica con todos los demás dispositivos conectados a la motherboard.

Toda motherboard está construida alrededor de un determinado tipo de chipset y todo chipset está diseñado para funcionar con un determinado procesador. Por lo tanto, es importante elegir una motherboard y un chipset adecuados para garantizar un rendimiento óptimo del sistema.

## Bus de conexión

El bus de conexión es un conjunto de líneas eléctricas que conectan los diferentes componentes de una computadora, permitiendo la transferencia de datos entre ellos.

### Clasificación del bus según los dispositivos que conecta

Bus interno: se caracteriza por estar integrado dentro del microprocesador y su función es la de transferir información entre los distintos componentes del mismo, es decir entre registros, cache L1 , L2 , unidades de ejecución, etc..

Bus externo: se encarga de transportar datos/direcciones desde y hacia el CPU (también se lo conoce como BUS FRONTAL, o bus de sistema), permite la conexión entre la CPU y el chipset.

### Clasificación del bus según la información que transporta

#### Bus de DATOS

El bus de datos es responsable de transferir datos entre la CPU, la memoria, el almacenamiento y otros dispositivos. El bus de datos está formado por una serie de cables que conectan los diferentes dispositivos.

#### Bus de DIRECCIONES

Un bus de direcciones es una línea o conjunto de líneas que se utilizan para transferir direcciones de memoria entre la CPU y otros dispositivos. El bus de direcciones es unidireccional, lo que significa que solo puede transferir direcciones de memoria de la CPU a otros dispositivos. El bus de direcciones es generalmente paralelo, lo que significa que contiene varias líneas, una para cada bit de la dirección de memoria. El número de líneas en el bus de direcciones determina el tamaño máximo de la memoria que puede direccionar la CPU.

#### Bus de CONTROL

Un bus de control es un conjunto de líneas que se utilizan para transferir señales de control entre la CPU y otros dispositivos. Las señales de control se utilizan para coordinar las operaciones de la CPU y los dispositivos, y para garantizar que los dispositivos accedan a la memoria y a otros recursos de manera segura y eficiente.

## Memoria

La memoria es un componente esencial en cualquier sistema informático, ya que almacena temporalmente los datos y las instrucciones necesarias para que el procesador pueda realizar su trabajo.

Las memorias se pueden clasificar de varias maneras, pero las clasificaciones más comunes son:

•	Por tecnología: Las memorias se pueden clasificar por la tecnología que utilizan para almacenar datos. Algunas de las tecnologías de memoria más comunes incluyen DRAM, SRAM, EEPROM, flash y SSD.

•	Por velocidad: Las memorias se pueden clasificar por su velocidad de acceso a los datos. Algunas de las memorias más rápidas incluyen la memoria de acceso aleatorio (RAM), la memoria de acceso aleatorio dinámico (DRAM) y la memoria de acceso aleatorio estática (SRAM).

•	Por capacidad: Las memorias se pueden clasificar por su capacidad para almacenar datos. Algunas de las memorias más grandes incluyen los discos duros, los discos SSD y las cintas magnéticas.

•	Por volatilidad: Las memorias se pueden clasificar por su volatilidad, que es su capacidad para conservar los datos cuando se desconecta la energía. Las memorias volátiles, como la RAM, pierden los datos cuando se desconecta la energía. Las memorias no volátiles, como los discos duros y las cintas magnéticas, conservan los datos incluso cuando se desconecta la energía.

A continuación, se describen algunas de las memorias más comunes:

•	RAM: La RAM, o memoria de acceso aleatorio, es un tipo de memoria que se utiliza para almacenar los datos que está utilizando actualmente la CPU. La RAM es volátil, lo que significa que pierde los datos cuando se desconecta la energía.

•	ROM: La ROM, o memoria de solo lectura, es un tipo de memoria que se utiliza para almacenar datos que no necesitan ser modificados con frecuencia. La ROM es no volátil, lo que significa que conserva los datos incluso cuando se desconecta la energía.

•	EEPROM: La EEPROM, o memoria de solo lectura programable y borrable eléctricamente, es un tipo de memoria que se puede programar y borrar eléctricamente. La EEPROM se utiliza para almacenar datos que necesitan ser modificados con frecuencia, pero no con tanta frecuencia como la RAM.

•	Flash: La memoria flash es un tipo de memoria que se utiliza para almacenar datos en dispositivos portátiles, como memorias USB, reproductores de MP3 y cámaras digitales. La memoria flash es no volátil y tiene una alta capacidad de almacenamiento.

•	SSD: El SSD, o disco de estado sólido, es un tipo de almacenamiento de datos que utiliza memoria flash para almacenar datos. Los SSD son más rápidos que los discos duros tradicionales y tienen una mayor resistencia al daño físico.

## Microprocesador

Un microprocesador es el componente central de un ordenador. Se encarga de ejecutar las instrucciones de los programas y controlar el funcionamiento del resto del ordenador. Los microprocesadores están formados por millones de transistores, que son pequeños interruptores que pueden estar abiertos o cerrados. La forma en que se conectan los transistores determina las instrucciones que puede ejecutar el microprocesador.

Las partes del procesador son:

Unidad de control: La unidad de control es responsable de coordinar las operaciones del procesador. Se encarga de leer las instrucciones de la memoria y de ejecutarlas.

Unidad aritmético-lógica (ALU): La ALU es responsable de realizar las operaciones aritméticas y lógicas. Se encarga de sumar, restar, multiplicar, dividir, comparar, etc.

Registros: Los registros son pequeñas memorias que se utilizan para almacenar datos. Se utilizan para almacenar las instrucciones que se están ejecutando, los datos que se están procesando y los resultados de las operaciones.

Cache: La caché es una memoria de alta velocidad que se utiliza para almacenar las instrucciones y los datos más utilizados. Se utiliza para acelerar el acceso a estos datos.

Bus: El bus es un conjunto de líneas que conectan el procesador con otros componentes de la computadora. Se utiliza para transferir datos entre el procesador y otros componentes.

La evolución de los procesadores multinúcleo ha ido de la mano con el desarrollo de nuevos buses del sistema y placas base. A medida que los procesadores se han vuelto más complejos, han requerido buses del sistema y placas base más rápidas y eficientes.

Los primeros procesadores multinúcleo tenían solo dos o cuatro núcleos. Estos núcleos podían ejecutar diferentes hilos de código al mismo tiempo, lo que mejoraba el rendimiento de las aplicaciones que podían aprovechar la multitarea. Sin embargo, los buses del sistema y las placas base de la época no podían seguir el ritmo de los procesadores multinúcleo. Como resultado, los procesadores a menudo se ralentizaban debido al cuello de botella del bus del sistema.

Con el tiempo, los buses del sistema y las placas base se han vuelto más rápidos y eficientes. Esto ha permitido que los procesadores multinúcleo se ejecuten a su máxima velocidad sin sufrir cuellos de botella. Como resultado, los procesadores multinúcleo se han vuelto cada vez más populares, y ahora se encuentran en una amplia gama de dispositivos, desde computadoras de escritorio hasta teléfonos inteligentes.

A medida que la tecnología de los procesadores continúa evolucionando, se espera que los procesadores multinúcleo se vuelvan aún más poderosos. Esto requerirá el desarrollo de nuevos buses del sistema y placas base que puedan seguir el ritmo de los procesadores multinúcleo.

Aquí hay algunos ejemplos de cómo la evolución de los procesadores multinúcleo ha impactado en el diseño de buses del sistema y placas base:

* El uso de buses del sistema de mayor ancho de banda. Esto permite que los procesadores transmitan datos al bus del sistema más rápido.

* El uso de placas base con más ranuras de memoria. Esto permite que los procesadores accedan a más memoria, lo que puede mejorar el rendimiento de las aplicaciones que requieren mucha memoria.

* El uso de placas base con más carriles PCI Express. Esto permite que los procesadores se comuniquen con otros dispositivos más rápido.
