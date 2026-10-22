# STNC — CD Visualizer

Visualizador interactivo de un mockup de CD. Presenta el disco flotando sobre un fondo oscuro con luces y colores animados; el movimiento del cursor o del dedo inclina el disco y desplaza el foco de luz.

## Cómo usarlo

Abre `stnc-cd-visualizer_2.html` en un navegador moderno. No requiere instalación, servidor, conexión a Internet ni dependencias externas.

- Mueve el cursor sobre la página para inclinar el CD y desplazar la luz.
- En dispositivos táctiles, arrastra el dedo para controlar el mismo efecto.
- Si el sistema tiene activada la opción de reducir movimiento, las animaciones decorativas se desactivan.

## Contenido del proyecto

- `stnc-cd-visualizer_2.html`: página completa con estilos y JavaScript integrados. La imagen del CD está incluida en el propio archivo.
- `CD_STNC_MOCKUP.jpg` y `CD_STNC_MOCKUP.psd`: archivos del mockup disponibles en el repositorio; la página utiliza la imagen incrustada y no depende de ellos para mostrarse.

## Tecnologías

HTML, CSS y JavaScript sin bibliotecas ni herramientas de compilación. El fondo, la iluminación, la flotación y las sombras se generan mediante CSS; JavaScript suaviza la respuesta al puntero y aplica la inclinación 3D.
