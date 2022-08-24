---
title: '#90DaysOfDevOps - Plan > Code > Build > Testing > Release > Deploy > Operate > Monitor > - Day 5'
published: false
description: 90DaysOfDevOps - Plan > Code > Build > Testing > Release > Deploy > Operate > Monitor >
tags: "devops, 90daysofdevops, learning"
cover_image: null
canonical_url: null
id: 1048830
date: '2022-04-26T10:12:40Z'
---
## Plan > Code > Build > Testing > Release > Deploy > Operate > Monitor > 

Hoy nos vamos a centrar en los pasos individuales de principio a fin y el ciclo continuo de una aplicación en un mundo DevOps. 

![DevOps](Images/Day5_DevOps8.png)

### Plan:

Todo comienza con el proceso de planificación, aquí es donde el equipo de desarrollo se reúne y determina qué características y correcciones de errores implementarán en su próximo sprint. Como ingeniero de DevOps esta es una oportunidad para involucrarse y aprender qué tipo de cosas se le presentarán en las que debe involucrarse y también influir en sus decisiones o su camino y ayudarlos a trabajar con la infraestructura que ha construido o guiarlos hacia algo que funcionará mejor para ellos y, por lo tanto, una cosa clave para señalar aquí es que los desarrolladores o el equipo de ingeniería de software es su cliente como ingeniero DevOps, por lo que esta es su oportunidad de trabajar con su cliente antes de que tome un mal camino.

### Code:

Ahora, una vez que termine la sesión de planificación, comenzarán a escribir el código. Es posible que participe o no en esta etapa. Uno de los lugares en los que puede involucrarse, siempre que estén escribiendo código, es en ayudarlos a comprender mejor la infraestructura, de modo que si saben qué servicios están disponibles y cuál es la mejor forma de hablar con esos servicios, lo harán y luego una vez que hayan terminado fusionarán ese código en el repositorio de mejor forma.

### Build:

Aquí es donde iniciaremos el primero de nuestros procesos de automatización, tomaremos su código y lo construiremos dependiendo del lenguaje que estén usando, puede interpretarlos o compilarlo o podría estar creando una imagen docker a partir de ese código, de cualquier manera vamos a pasar por ese proceso usando nuestro pipeline CI/CD

## Testing:

Una vez que lo hayamos construido, vamos a ejecutar algunas pruebas en él. Ahora, el equipo de desarrollo generalmente escribe la prueba. Es posible que tenga alguna información sobre qué pruebas se escriben, pero necesitamos ejecutar esas pruebas y las pruebas son una forma para intentar y minimizar la introducción de problemas/errores al ambiente de producción, no lo garantiza, pero nos acercaremos lo más posible a una garantía de que uno no introduce nuevos errores y dos no rompe cosas que solían funcionar

## Release:

Una vez que pasen las pruebas, haremos el proceso de lanzamiento y, dependiendo nuevamente del tipo de aplicación en la que esté trabajando, esto puede no ser necesario. Usted sabe que el código puede vivir en el repositorio de GitHub o en el repositorio de git o dondequiera que viva, pero puede ser el proceso de tomar su código compilado o la imagen de Docker que ha creado y colocarlo en un registro o un repositorio donde está accesible por sus servidores de producción para el proceso de implementación.

## Deploy:

Es lo que hacemos a continuación porque la implementación es como el juego final de todo esto porque las implementaciones cuando ponemos el código en producción y no es hasta que lo hacemos que nuestra empresa realmente se da cuenta del valor de todo el esfuerzo y el trabajo duro, que usted y el equipo de ingeniería de software han puesto en este producto hasta este momento. 

## Operate:

Una vez que esté implementado, vamos a operarlo y esto puede implicar recibir llamadas de sus clientes que están molestos porque el sitio o aplicación funciona lentamente y debe averiguar por qué, posiblemente deba crear un escalado automático que aumente la cantidad de servidores disponibles durante los períodos de mayor actividad y disminuya la cantidad de servidores durante los períodos de menor actividad, de cualquier manera, todas son métricas operativas. Otra cosa operativa que debe hacer es incluir comentarios desde producción a su equipo de operaciones, para informarle sobre los eventos clave que ocurrieron en producción, como eventos claves de la implementación, retroceder un paso en la implementación, entre otros datos relevantes. Esto puede automatizarse o no según su entorno, el objetivo es automatizarlo siempre cuando sea posible hay algunos entornos en los que posiblemente necesite realizar algunos pasos antes de estar listo para esto, pero idealmente desea implementar automatización como parte de su proceso de implementación, pero si lo está haciendo, podría ser una buena idea incluir en sus pasos operativos algún tipo de notificación para que su equipo de operaciones sepa que se ha producido una implementación.

## Monitor:

Todas las partes anteriores conducen al paso final, se requiere tener monitoreo, especialmente entorno a problemas operativos, por ejemplo, resolución de problemas de escalado automático. Algunas de las cosas para las que podría crear un monitoreo son la utilización de la memoria, la utilización del espacio en disco de la CPU, API’s, el tiempo de respuesta, la rapidez con la que responde ese punto final y una gran parte de eso también son registros. Los registros brindan a los desarrolladores la capacidad de ver lo que sucede sin tener que acceder a los sistemas de producción.

## Rince & Repeat: 

Una vez que esté en su lugar, regrese directamente al principio a la etapa de planificación y vuelva a pasar por todo el proceso.

## Continuous:

Muchas herramientas nos ayudan a lograr el proceso continuo anterior, todo este código y el objetivo final de estar completamente automatizado, la infraestructura en la nube o cualquier entorno a menudo se describe como Integración continua/Entrega continua/Implementación continua o “CI/CD” para abreviar. Pasaremos una semana entera en CI/CD más adelante en los 90 días con algunos ejemplos y tutoriales para comprender los fundamentos.

### Continuous Delivery:

Continuous Delivery = Plan > Code > Build > Test 

### Continuous Integration:

Este es efectivamente el resultado de las fases de entrega continua más el resultado de la fase de lanzamiento. Este es el caso tanto para el fracaso como para el éxito, pero esto se retroalimenta en la entrega continua o se traslada a la implementación continua.

Continuous Integration = Plan > Code > Build > Test > Release 

### Continuous Deployment: 

Si tiene una versión exitosa de su integración continua, pase a la implementación continua, que incluye las siguientes fases

La versión de CI es correcta = Implementación continua = Implementar > Operar > Supervisar

Puede ver estas tres nociones continuas anteriores como la simple colección de fases del ciclo de vida de DevOps.

Esto último fue un resumen para mí del día 3, pero creo que en realidad me aclara las cosas.

### Recursos:

- [DevOps for Developers – Software or DevOps Engineer?](https://www.youtube.com/watch?v=a0-uE3rOyeU)
- [Techworld with Nana -DevOps Roadmap 2022 - How to become a DevOps Engineer? What is DevOps? ](https://www.youtube.com/watch?v=9pZ2xmsSDdo&t=125s)
- [How to become a DevOps Engineer in 2021 - DevOps Roadmap](https://www.youtube.com/watch?v=5pxbp6FyTfk)

If you made it this far then you will know if this is where you want to be or not. 

See you on [Day 6](day06.md). 
