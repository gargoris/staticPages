---
title: Sabores Linux y algunos comentarios sobre ellos
date: 2017-11-06 13:09:37
---

### ¿Qué es un sabor?
Un sabor[^1] de Linux es un paquete compuesto por el núcleo de Linux (kernel, en argot, que es lo que realmente es Linux) junto con una serie de aplicaciones para generar nuevo software (sistemas de compilación y generación de ejecutables), software para la configuración y arranque y aplicaciones ya generadas, compatibles entre cualesquiera sabores de Linux que compartan arquitectura (32 bits, 64 bits, arm, etc).

Aparte de algunas líneas generales, como por ejemplo el proceso de arranque del sistema Linux que es casi común o con pocas opciones, cada organización que desarrolla una distribución Linux elige, por ejemplo, el formato de empaquetado de aplicaciones para instalación y el sistema para el inventario general del software instalado, algunas aplicaciones específicas para la configuración (normalmente en modo gráfico), algún escritorio (window manager) que reciba los mayores esfuerzos de la organización para la integración del mismo en la distribución, etc.

Junto con la arquitectura de la distribución, cada organización también decide cuál será el protocolo de actualización de las aplicaciones que provee, variando desde las muy conservadoras, como Debian, que genera una versión cada dos años, tras haber probado exhaustivamente todo el producto, hasta las denominadas distribuciones _rolling-release_, en las que casi en el mismo día que los desarrolladores originales de una aplicación liberan una nueva versión, esta se pone a disposición de los usuarios de la distribución.




[^1]: Sabor es el término que en los primeros tiempos se usaba para lo que ahora se denomina distribución, si bien no son lo mismo. Un sabor implica decisiones arquitecturales básicas y una distribución era, inicialmente, una selección de aplicaciones sobre un sabor que alguna casa de software recopilaba y, normalmente, distribuía en CD o DVD.