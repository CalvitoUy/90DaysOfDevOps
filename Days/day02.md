---
title: '#90DaysOfDevOps - Responsabilidades de un Ingeniero DevOps - Día 2'
published: false
description: 90DaysOfDevOps - Responsibilities of a DevOps Engineer
tags: 'devops, 90daysofdevops, learning'
cover_image: null
canonical_url: null
id: 1048699
date: '2022-04-23T21:15:34Z'
---
## Responsabilidades del un Ingeniero DevOps 

Con suerte, usted está entrando aquí después de revisar los recursos del [Día 1 de #90DaysOfDevOps] (day01.md)

Se mencionó brevemente en la primera publicación, pero ahora debemos profundizar en este concepto y comprender que hay dos partes principales al crear una aplicación. Tenemos la parte de **Desarrollo** donde los desarrolladores de software programan la aplicación y la prueban. Luego tenemos la parte de **Operaciones** donde la aplicación se implementa y mantiene en un servidor.

## DevOps es el vínculo entre los dos mundos

Para familiarizarnos con DevOps o las tareas que llevaría a cabo un ingeniero de DevOps, debemos comprender las herramientas, el proceso y la descripción general de estos y cómo se combinan.

¡Todo comienza con la aplicación! Verá en todo momento que se trata de la aplicación cuando se trata de DevOps.

Los desarrolladores crearán una aplicación, esto se puede hacer combiando muchas tecnología diferentes, dejemos eso a la imaginación por ahora a medida que nos adentremos en esto más adelante lo hiremos aclarando. Esto también puede involucrar muchos lenguajes de programación diferentes, herramientas de compilación, repositorio de código, etc.

Como ingeniero de DevOps, no estará programando la aplicación, pero tener una buena comprensión de los conceptos de cómo trabaja un desarrollador y los sistemas, herramientas y procesos que utilizan es clave para el éxito.

En un nivel muy alto, necesitará saber cómo está configurada la aplicación para hablar con todos sus servicios requeridos o servicios de datos y luego también especificar un requisito de cómo esto puede o debe probarse.

La aplicación deberá implementarse en algún lugar, mantengamos las cosas simples en general aquí y hagamos de esto un servidor, no importa dónde, sino un servidor. Luego, se espera que el cliente o el usuario final acceda a esto, según la aplicación que se haya creado.

Este servidor debe ejecutarse en algún lugar, en las instalaciones de la empresa, en una nube pública, sin servidor (Ok, he ido demasiado lejos, no cubriremos la tecnología sin servidor, pero es una opción y cada vez más empresas se están dirigiendo hacia esta dirección) Alguien necesita crear y configurar estos servidores y prepárelos para que se ejecute la aplicación. Ahora, este elemento podría llegar a usted como ingeniero de DevOps para implementar y configurar estos servidores.

Estos servidores tendrán que ejecutar un sistema operativo y, en términos generales, será Linux, pero tenemos una sección completa o una semana en la que cubrimos algunos de los conocimientos básicos que debe obtener aquí. 

También es probable que necesitemos comunicarnos con otros servicios en nuestra red o entorno, por lo que también debemos tener ese nivel de conocimiento sobre las redes y la configuración, esto podría, hasta cierto punto, estar a cargo del ingeniero DevOps. Nuevamente, cubriremos esto con más detalle en una sección dedicada que habla de todo lo relacionado con DNS, DHCP, equilibrio de carga, etc. 

## Aprendiz de todos los oficios, maestro de nada

Sin embargo, diré en este punto que no necesita ser un especialista en redes o infraestructura, necesita un conocimiento básico de cómo hacer que las cosas funcionen y se comuniquen entre sí, muy parecido a tener un conocimiento básico de un lenguaje de programación, pero no es necesario ser un desarrollador. Sin embargo, es posible que ingrese a esto como especialista en un área y esa es una excelente base para adaptarse a otras áreas.

Lo más probable es que tampoco se haga cargo de la administración de estos servidores o de la aplicación a diario.

Hemos estado hablando de servidores, pero lo más probable es que su aplicación se desarrolle para ejecutarse como contenedores, que todavía se ejecutan en un servidor en su mayor parte, pero también necesitará comprender no solo la virtualización, la infraestructura de la nube como servicio (IaaS). ) pero también la contenerización. El enfoque en estos 90 días se centrará más en los contenedores.

## Descripción General

Por un lado, tenemos a nuestros desarrolladores creando nuevas características y funcionalidades (así como correcciones de errores) para la aplicación.

Por otro lado, tenemos algún tipo de entorno, infraestructura o servidores que están configurados y administrados para ejecutar esta aplicación y comunicarse con todos sus servicios requeridos.

La gran pregunta es ¿cómo incorporamos esas características y correcciones de errores a nuestra producción y la ponemos a disposición de los usuarios finales?

¿Cómo lanzamos la nueva versión de la aplicación? Esta es una de las tareas principales para un ingeniero de DevOps, y lo importante aquí no es solo descubrir cómo hacer esto una vez, sino que debemos hacerlo de manera continua y automatizada, de manera eficiente, ¡lo que también debe incluir pruebas!

Aquí es donde vamos a terminar este día de aprendizaje, esperemos que esto haya sido útil. En los próximos días profundizaremos un poco más en algunas áreas más de DevOps y luego entraremos en las secciones que profundizan en las herramientas y los procesos y los beneficios de estos.

## Recursos 

Siempre estoy abierto a agregar recursos adicionales a estos archivos Léame, ya que están aquí como una herramienta de aprendizaje.

Mi consejo es que mire todos los recursos y, con suerte, también haya aprendido algo del texto y las explicaciones anteriores.
- [What is DevOps? - TechWorld with Nana](https://www.youtube.com/watch?v=0yWAtQ6wYNM)
- [What is DevOps? - GitHub YouTube](https://www.youtube.com/watch?v=kBV8gPVZNEE)
- [What is DevOps? - IBM YouTube](https://www.youtube.com/watch?v=UbtB4sMaaNM)
- [What is DevOps? - AWS ](https://aws.amazon.com/devops/what-is-devops/)
- [What is DevOps? - Microsoft](https://docs.microsoft.com/en-us/devops/what-is-devops)

Si llegaste hasta aquí, sabrás si aquí es donde quieres estar o no. Nos vemos el [Día 3](day03.md).
