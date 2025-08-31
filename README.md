Práctica 1: Control de Barra LED con Página Móvil y Raspberry Pi Pico

📌 Descripción General
El proyecto consiste en el diseño de una página móvil en HTML/JavaScript que permite seleccionar diferentes patrones de animación, los cuales son enviados a un Raspberry Pi Pico configurado con MicroPython para controlar una barra de LED.
La comunicación se establece a través de red Wi-Fi, donde el Pico recibe la opción seleccionada y ejecuta el patrón correspondiente en los LEDs.

🚀 Etapas del Proyecto

1.-Diseño de la interfaz móvil
Crear una página con menú de 9 opciones.
Incorporar un teclado matricial para interacción
Implementar envío de datos al Pico mediante Fetch/AJAX

2.-Configuración del microcontrolador
Preparar Raspberry Pi Pico con MicroPython.
Conectar el dispositivo a la red Wi-Fi con SSID y contraseña.
Asignar dirección IP y puerto para comunicación.

3.-Programación en el Pico
Implementar servidor para recibir las selecciones.
Definir las secuencias de LEDs asociadas a cada opción.

4.-Pruebas del sistema
Subir código al Pico.  
Verificar que cada opción activa la animación LED correcta.
