# ArquitecturaSFV-P1

# Evaluación Práctica - Ingeniería de Software V

## Información del Estudiante
- **Nombre:** Luis Manuel Rojas Correa
- **Código:** A0039989
- **Fecha:** Aug 6 2025

## Resumen de la Solución
A simple docker file was written in order to run a node js app
that uses express: simple server with an json response.



## Dockerfile

In order to correctly use node the image node:18-alpine
was included (this image has all the dependencies and requirements to
run any node application). Then the working direction of the app was
set, as also the json package copied in order to include any config
information of the app. Then the RUN command was specified, telling that 
once the docker image is settiing up it will need to run the command npm install, and finally the service was exposed in the port 3000. 


## Script de Automatización




## Principios DevOps Aplicados
1. [Principio 1]
2. [Principio 2]
3. [Principio 3]

## Captura de Pantalla
[Incluye al menos una captura de pantalla que muestre tu aplicación funcionando en el contenedor]

## Mejoras Futuras
[Describe al menos 3 mejoras que podrían implementarse en el futuro]

## Instrucciones para Ejecutar
[Instrucciones paso a paso para ejecutar tu solución]
