# Estándares de apps

**TV Azteca Digital**

## Índice

* [Objetivo](#objetivo)
* [Diseño](#diseño)
* [Desarrollo](#desarrollo)
* [Seguridad](#seguridad)
* [Métricas](#métricas)

## Objetivo: 

Este documento define las pautas elementales a ser consideradas al momento de diseñar, desarrollar e implementar toda aplicación móvil para TV Azteca, ya sea realizada por el equipo interno o por un proveedor, con el fin de ser publicadas en las tiendas de aplicaciones iOS y Android.

## **Diseño**

La UX (experiencia de usuario) debe ser útil para el usuario además de fácil de entender y usar. La identidad visual debe ser homogénea entre los diferentes sitios, secciones o proyectos.

Se debe tener en cuenta que una aplicación móvil es más costosa de desarrollar que un sitio web y es más dificil que un usuario la baje (en comparación a entrar a un sitio web). Por lo cual se debe evaluar con mayor rigurosidad si debe existir la aplicación o no. Por ejemplo en el caso de necesitar mostrar sólo información conviene hacer un sitio web, pero en el caso de tener que realizar una acción recurrente, es posible que convenga hacer una aplicación.

## **Desarrollo** 

* Las aplicaciones deben soportar las distintas resoluciones de los distintos tipos de dispositivos. 

* No embeber imágenes y videos como contenido estático que hagan que los instaladores sean más pesados.

* Toda aplicación contará con un backend propio.

* La lista de aplicaciones debe estar actualizada. Si la aplicación no está más en funcionamiento (o con soporte) hay que removerla de las tiendas.

* El código fuente de las aplicaciones deberá ser simple, fácil de comprender, escalable, flexible y deberá ser acompañado de la documentación necesaria para poder asegurar su continuidad soportando un futuro cambio de proveedor.

* Control de Versiones: 

    * **versión v 0.0.1**: Resolución de bugs de versiones actuales.

    * **versión v.0.1.0**: Nueva funcionalidad dentro de la versión actual.

    * **versión v.1.0.0**: Representan un cambio sustancial respecto de la funcionalidad o de la estética actual de la app. 

* Todas las aplicaciones con servicios para el usuario que tengan que tener registro de personas deben usar el sistema de login de Azteca contando con un identificador único (IM).

* Todo contenido que muestra la aplicación debe ser consumido mediante una API respetando los lineamientos del Estándar de API definida por el equipo de Arquitectura de Servicios Digitales.

* El desarrollo se realizará para que sea compatible con la última versión más estable del sistema operativo y contemplando las versiones previas que aún siguen siendo populares.  

## **Seguridad**

* Todas las URL que lanza una aplicación deben ser https.

* Solo se deben pedir al usuario los permisos mínimos y estrictamente los que son necesarios.

* Los datos de los usuarios usados en la registración deben ser guardados con seguridad.

* Se deben actualizar los frameworks de desarrollo para evitar vulnerabilidades de seguridad. 

## **Métricas**

* Las aplicaciones deben contar con Google Analytics e incorporar métricas provistos por la Coordinación de Análisis de Datos de Servicios Digitales. 

* Las aplicaciones deben incorporar registros de errores y fallas.

**Aplicación nativa en Android y iOS**

*Aplicaciones con código previamente implementado.*

En caso de poseer código de seguimiento se deberá brindar permisos de administración a una cuenta proporcionada únicamente para el fin de desarrollo. Asimismo se deberá modificar el mismo para que se adapte a los estandares propuestos.

## **Publicación**

* Las aplicaciones se subirán a las distintas tiendas de Servicios Digitales.

* Las aplicaciones las firmará Servicios Digitales con la firma y certificados propietaria. 

* Los células de proyecto que dispongan de sus propios proveedores deberán trabajar en un repositorio provisto por Servicios Digitales.

* Los identificadores de cada aplicación deben ser únicos para cada dispositivo y tener el siguiente formato: 

  com.azteca.azteca

* Los datos y las capturas de pantallas de las aplicaciones para ser publicadas deben ser provistas por cada célula de proyecto.

* Los datos de contacto, sitio, detalle, etc. de cada aplicación deben pertenecer a cada célula de proyecto y ser provistos para la carga en las tiendas.