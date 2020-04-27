# Plantilla de Apunte

[![GitHub issues](https://img.shields.io/github/issues/rgormcl/Plantilla-de-Apunte)](https://github.com/rgormcl/Plantilla-de-Apunte/issues)
[![GitHub forks](https://img.shields.io/github/forks/rgormcl/Plantilla-de-Apunte)](https://github.com/rgormcl/Plantilla-de-Apunte/network)
[![GitHub stars](https://img.shields.io/github/stars/rgormcl/Plantilla-de-Apunte)](https://github.com/rgormcl/Plantilla-de-Apunte/stargazers)
[![GitHub license](https://img.shields.io/github/license/rgormcl/Plantilla-de-Apunte)](https://github.com/rgormcl/Plantilla-de-Apunte/blob/master/LICENSE)
[![Version](https://img.shields.io/badge/version-2.3-green)](https://github.com/rgormcl/Plantilla-de-Apunte/releases)

Una plantilla desarrollada en LaTeX para tus apuntes de clases o ramos.

## Features

1. Bloques para estructurar el documento: "Alerta", "Definición", "Ejemplo" y "Info":  

    ```tex
    \begin{exampleblock}{Bloque}
        Aquí van tus ejemplos
    \end{exampleblock}
    ```

2. Índices para cada uno de los bloques, tablas, figuras y listings (bloques con código fuente).

3. Soporte para añadir bloques sin índice:  

    ```tex
    \begin{exampleblock*}{Este bloque no tiene indice}
        Efectivamente.
    \end{exampleblock*}
    ```

4. Soporte para añadir bloques de código fuente dentro del documento de manera ordenada y limpia utilizando `listings`.

5. Sangría e indentación del texto y títulos mejorada.

6. Algunos comandos utiles (por ejemplo `\separation` que entrega una separación vertical de 2mm).  

7. Separación del cuerpo del documento, archivos externos y lógica de la plantilla.

8. Código fuente de la plantilla escrito de manera limpia y ordenada.

## Demostración y Ejemplos

La plantilla viene con información y textos de ejemplo para mostrar la utilización de sus características, aprovéchalas para inspirarte, modificarlas, eliminarlas, copiarlas y pegarlas por doquier.

Una demostración disponible de la plantilla se encuentra en el binario (`.pdf`).

## Compilación del Proyecto

- El proyecto es compilado en `Ubuntu` utilizando `TeX Live`.
- Utilizo `VSCode` como editor de texto.

## Errores

Si encuentras un error en la plantilla no dudes en publicar un `issue`.  
