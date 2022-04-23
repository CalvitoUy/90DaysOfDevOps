---
title: '#90DaysOfDevOps - Application Focused - Day 3'
published: false
description: 90DaysOfDevOps - Application Focused
tags: "devops, 90daysofdevops, learning"
cover_image: null
canonical_url: null
id: 1048825
date: '2022-04-23T10:12:40Z'
---
## Ciclo de Vida de DevOps - Centrado en la Aplicación

A medida que avancemos durante las próximas semanas, nos encontraremos al 100 % con estos títulos (Desarrollo continuo, Pruebas, Implementación, Supervisión) una y otra vez. Si se dirige hacia el rol de Ingeniero DevOps, entonces la repetitivilidad será algo común, pero mejorando constantemente para mantener las cosas interesantes.

En esta hora vamos a echar un vistazo a la vista de alto nivel de la aplicación de principio a fin y luego daremos la vuelta nuevamente como un bucle constante.

### Desarrollo
Tomemos un ejemplo completamente nuevo de una aplicación, para empezar no tenemos nada creado, tal vez como desarrollador deba hablar con su cliente o usuario final sobre los requisitos y proponer algún tipo de plan o requisitos para su aplicación. Luego necesitamos crear a partir de los requisitos nuestra nueva aplicación.

En lo que respecta a las herramientas en esta etapa, no hay ningún requisito real aparte de elegir su IDE y el lenguaje de programación que desea usar para escribir su aplicación.

Como ingeniero de DevOps, recuerde que probablemente no sea usted quien cree este plan o codifique la aplicación para el usuario final, este será un desarrollador experto.

Pero tampoco le vendría mal poder leer parte del código para que pueda tomar las mejores decisiones de infraestructura para su aplicación.

Anteriormente mencionamos que esta aplicación se puede escribir en cualquier lenguaje. Es importante que esto se mantenga usando un sistema de control de versiones, esto es algo que también cubriremos en detalle más adelante y, en particular, nos sumergiremos en **Git**.

También es probable que no haya un solo desarrollador trabajando en este proyecto, aunque este podría ser el caso, pero aun así las mejores prácticas requerirían un repositorio de código para almacenar y colaborar en el código, esto podría ser privado o público y podría estar alojado o implementado de forma privada, en términos generales, **GitHub o GitLab** se usan como repositorio de código. Una vez más, los cubriremos como parte de nuestra sección sobre **Git** más adelante.

### Pruebas
En esta etapa tenemos nuestros requisitos y tenemos nuestra aplicación en desarrollo. Pero debemos asegurarnos de que estamos probando nuestro código en los diferentes entornos que tenemos disponibles o específicamente en el lenguaje de programación elegido.

Esta fase permite al equipo de control de calidad realizar pruebas en busca de errores con más frecuencia, veremos que se utilizan contenedores para simular el entorno de prueba, lo que en general puede mejorar los gastos generales de infraestructura física o en la nube.

Es probable que esta fase también se automatice como parte de la siguiente área, que es la Integración Continua **(CI)**.

La capacidad de automatizar estas pruebas frente a 10, 100 o incluso 1000 ingenieros de control de calidad que tienen que hacer esto manualmente habla por sí sola, estos ingenieros pueden concentrarse en otra cosa para asegurarse de que se está moviendo más rápido y desarrollando más funciones en lugar de probar errores y software. que tiende a ser el retraso en la mayoría de las versiones de software tradicionales que utilizan una metodología de cascada.

### Integración

Es muy importante que la integración se encuentre en la mitad del ciclo de vida de DevOps. Es la práctica en la que los desarrolladores requieren realizar cambios en el código fuente con mayor frecuencia. Esto podría ser sobre una base diaria o semanal.

Con cada confirmación, su aplicación puede pasar por las fases de prueba automatizadas y esto permite la detección temprana de problemas o errores antes de la siguiente fase.

Ahora, en esta etapa, podría estar diciendo "pero no creamos aplicaciones, las compramos listas para usar de un proveedor de software". No se preocupe, muchas empresas hacen esto y continuarán haciéndolo y será el proveedor de software el que se concentra en las 3 fases anteriores, pero es posible que desee adoptar la fase final, ya que esto permitirá implementaciones más rápidas y eficientes de sus implementaciones listas para usar.

También sugeriría que tener este conocimiento es muy importante, ya que podría comprar software estándar hoy, pero ¿qué pasa mañana o más adelante... el próximo trabajo tal vez?

### Despliegue
Ok, tenemos nuestra aplicación construida y probada contra los requisitos de nuestro usuario final y ahora debemos seguir adelante e implementar esta aplicación en producción para que nuestros usuarios finales la consuman.

Esta es la etapa en la que el código se implementa en los servidores de producción, ahora aquí es donde las cosas se ponen extremadamente interesantes y es donde profundizaremos en los proximos 86 dias. Porque diferentes aplicaciones requieren posiblemente diferentes hardware o configuraciones. Aquí es donde **Administración de configuración de aplicaciones** e **Infraestructura como código** podrían desempeñar un papel clave en su ciclo de vida de DevOps. Puede ser que su aplicación esté **en contenedores** pero también disponible para ejecutarse en una máquina virtual. Lo que también nos lleva a plataformas como **Kubernetes** que estarían organizando esos contenedores y asegurándose de que tenga el estado deseado disponible para sus usuarios finales.

Todos estos temas audaces los profundizaremos en las próximas semanas para obtener un mejor conocimiento básico de lo que son y cuándo usarlos.

### Vigilancia

Las cosas se están moviendo rápido aquí y tenemos nuestra aplicación que estamos actualizando continuamente con nuevas características y funcionalidades y tenemos nuestras pruebas para asegurarnos de que no se encuentren gremlins. Tenemos la aplicación ejecutándose en nuestro entorno que puede mantener la configuración y el rendimiento requeridos.

Pero ahora debemos asegurarnos de que nuestros usuarios finales obtengan la experiencia que necesitan. Aquí debemos asegurarnos de que nuestro rendimiento de la aplicación se monitoree continuamente, esta fase permitirá a sus desarrolladores tomar mejores decisiones sobre las mejoras de la aplicación en futuras versiones para servir mejor a los usuarios finales.

Esta sección también es donde vamos a capturar esa rueda de comentarios sobre las funciones que se han implementado y cómo les gustaría a los usuarios finales mejorarlas.

La confiabilidad también es un factor clave aquí, al final del día queremos que nuestra aplicación esté disponible todo el tiempo que sea necesario. Esto luego se presta a otras áreas de **observabilidad, seguridad y administración de datos** que deben monitorearse continuamente y la retroalimentación siempre se puede usar para mejorar, actualizar y lanzar la aplicación de manera continua.

Algunos aportes de la comunidad aquí específicamente [@_ediri](https://twitter.com/_ediri) también mencionaron que parte de este proceso continuo debería involucrar a los equipos de FinOps. Las aplicaciones y los datos se ejecutan y almacenan en algún lugar en el que debe monitorear esto continuamente para asegurarse de que si las cosas cambian desde el punto de vista de los recursos, sus costos no están causando un problema financiero importante en sus facturas de la nube.

El título de ingeniero de DevOps no debería ser el objetivo para nadie porque, en realidad, cualquier posición debería adoptar los procesos de DevOps y la cultura que se explica aquí. DevOps debe usarse en muchos puestos diferentes, como ingeniero/arquitecto nativo de la nube, administrador de virtualización, arquitecto/ingeniero de la nube, administrador de infraestructura. Esto es por nombrar algunos, pero la razón para usar DevOps Engineer arriba fue realmente para resaltar el alcance o el proceso utilizado por cualquiera de los puestos anteriores y más.

## Recursos 

Siempre estoy abierto a agregar recursos adicionales a estos archivos Léame, ya que están aquí como una herramienta de aprendizaje.

Mi consejo es que mire todos los recursos y, con suerte, también haya aprendido algo del texto y las explicaciones anteriores.

- [Continuous Development](https://www.youtube.com/watch?v=UnjwVYAN7Ns) También agregaré que esto se enfoca en la fabricación, pero la cultura Lean se puede seguir de cerca con DevOps. 
- [Continuous Testing - IBM YouTube](https://www.youtube.com/watch?v=RYQbmjLgubM)
- [Continuous Integration - IBM YouTube](https://www.youtube.com/watch?v=1er2cjUq1UI)
- [Continuous Monitoring](https://www.youtube.com/watch?v=Zu53QQuYqJ0)
- [The Remote Flow](https://www.notion.so/The-Remote-Flow-d90982e77a144f4f990c135f115f41c6)
- [FinOps Foundation - What is FinOps](https://www.finops.org/introduction/what-is-finops/)
- [**NOT FREE** The Phoenix Project: A Novel About IT, DevOps, and Helping Your Business Win](https://www.amazon.co.uk/Phoenix-Project-DevOps-Helping-Business-ebook/dp/B00AZRBLHO)

Si llegaste hasta aquí, sabrás si aquí es donde quieres estar o no. Nos vemos el [Day 4](day04.md).  
