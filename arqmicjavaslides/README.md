# Arquitectura de Microservicios con Java

## Retos para desarrollar aplicaciones escalables

## Arquitectura de Software

- Es un conjunto de estructuras necesarias
- Elmentos de software


## Arquitectura Monolithic: ventajas

- Fácil de desarrollar
  - El objetivo de las herramientas de desarrollo y los IDEs a ctuales es respaldar el desarrollo de aplicaciones  monolíticas.
- Fácil de implementar
   - en el caso de Java simplemente necesita implementar el archivo WAR)
 - Fácil de escalar
   - se puede escalar la aplicación ejecutando varias copias de la aplicación detrás de un balanceador de carga.

## Arquitectura Monolítica: Base de datos

![Texto alternativo](/img/erp_model.png)

## Arquitectura Monolítica: Estructura

![Texto alternativo](/img/estructura_monolithic.png)

## Arquitectura Monolítica: Proyecto

![Texto alternativo](/img/estructura_java_mono.png)

## Arquitectura Monolítica: Proyecto

![Texto alternativo](/img/demomonolithic.gif)


## Arquitectura de Microservicios

Los microservicios, también conocidos como arquitectura de microservicios, son un estilo arquitectónico que estructura una aplicación como una colección de servicios que son

- Altamente mantenible y comprobable
- Débilmente acoplado
- Desplegable independientemente
- Organizado en torno a las capacidades comerciales
- Propiedad de un pequeño equipo

## Microservicios

- Conjunto de prácticas
- Incremantar la velicidad
- Soluciones escalables
- No es a fin a una tecnología en particular



 > Es un enfoque para desarrollar una sola aplicación como un conjunto de pequeños servicios, cada uno ejecutándose en su propio proceso y comunicándose con mecanismos ligeros, a menudo una API de recursos HTTP. 
 
 > Estos servicios se basan en capacidades comerciales y se pueden implementar de forma independiente 
 
 > Pueden estar escritos en diferentes lenguajes de programación y utilizar diferentes tecnologías de almacenamiento de datos.

 _James Lewis y Martin Fowler_

 ## Ejemplo completo de arquitectura

 ![Texto alternativo](/img/eShopOnContainers-architecture.png)

Referencia: https://github.com/dotnet-architecture/eShopOnContainers

## Frameworks Java para Microservicios



 ## Algunas ideas

 - Seleccionar la arquitectura adecuada
 - Iniciar con una arquitectura Monolítica
 - Preparar el código para poder separarlo
 - 