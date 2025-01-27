![Lectura de recibos con Inteligencia Artificial](/images/cover.png)

<h1 align="center">Lectura de recibos con Inteligencia Artificial</h1>

<p align="center">
  Lector de recibos usando la API de Google Cloud Vision.
</p>

## Tabla de contenidos

- [Introducción](#introduction)
- [Funciones](#features)
- [Retroalimentación](#feedback)
- [Contribuidores](#contributors)
- [Proceso de construcción](#build-process)
- [Contacto](#acknowledgments)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Introducción

Lector de recibos o vóuchers de las principales entidades bancarias del Ecuador. El sistema reconoce el tipo de recibo, valida campos específicos como el número de control, el valor del recibo, el destinatario, útil para validar pagos en diferentes sistemas.

**Código válido para implementar en el servicio de Google Cloud Function.**

<p align="center">
  <img src = "https://raw.githubusercontent.com/edwin06111998/reconocer_recibos_AWS/main/imagenes/recibo.png" width=500>
  <img src = "https://raw.githubusercontent.com/edwin06111998/reconocer_recibos_AWS/main/imagenes/respuesta.png" width=500>
</p>

## Funciones

Estas son algunas de las características del lector de recibos:

* Identifica características claves de los recibos.
* Identifica el tipo de recibo.
* Obtiene el valor del recibo, número de control, destinatario.
* Se puede reprogramar para identificar otras características claves.
* Lee imágenes de cualquier formato y resolución.
* Capaz de leer imágenes volteadas.
* Puede procesar múltiples transacciones simultáneamente en cola.

<p align="center">
  <img src = "https://raw.githubusercontent.com/edwin06111998/reconocer_recibos_AWS/main/imagenes/seleccionar_pago.png" width=300>
  &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp
  <img src = "https://raw.githubusercontent.com/edwin06111998/reconocer_recibos_AWS/main/imagenes/pago%3Fexito.png" width=300>
</p>

## Retroalimentación

Siéntete libre de comentarme tu experiencia utilizando este sistema, puedes escribir al siguiente correo: edwin06111998@gmail.com.

## Contribuidores

Este proyecto ha sido desarrollado por (Edwin Veloz).

## Proceso de construcción

- Clona o descarga el repositorio
- Crea una función en Google Cloud Functions.
- Asígnale 512MB de memoria RAM, un tiempo de espera de 60 segundos, los demás campos por defecto.
- Completa el archivo APIKey.json con los datos de tu servicio Cloud Vision de Google.
- Sube el código como archivo comprimido a la función de Google Cloud.
- En la pestaña de "activador" podrás extraer la URL HTTPS para obtener respuesta de la función.
- Ahora estarás listo para leer recibos.

## Contacto

- LinkedIn: www.linkedin.com/in/edwin-veloz-2153a9137
- Correo: edwin06111998@gmail.com
