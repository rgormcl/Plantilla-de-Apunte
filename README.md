# Plantilla de Apunte

[![GitHub issues](https://img.shields.io/github/issues/rgormcl/Plantilla-de-Apunte)](https://github.com/rgormcl/Plantilla-de-Apunte/issues)
[![GitHub forks](https://img.shields.io/github/forks/rgormcl/Plantilla-de-Apunte)](https://github.com/rgormcl/Plantilla-de-Apunte/network)
[![GitHub stars](https://img.shields.io/github/stars/rgormcl/Plantilla-de-Apunte)](https://github.com/rgormcl/Plantilla-de-Apunte/stargazers)
[![GitHub license](https://img.shields.io/github/license/rgormcl/Plantilla-de-Apunte)](https://github.com/rgormcl/Plantilla-de-Apunte/blob/master/LICENSE)
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/rgormcl/Plantilla-de-Apunte)](https://github.com/rgormcl/Plantilla-de-Apunte/releases)

Una plantilla desarrollada en LaTeX para tus apuntes de clases o ramos.

## Features

1. Bloques para estructurar el documento: "Alerta", "Definición", "Ejemplo" y "Info":  

    ```tex
    \begin{exampleblock}{Bloque}
        Aquí van tus ejemplos.
    \end{exampleblock}
    ```

    ![InfoBlock Example](https://raw.githubusercontent.com/rgormcl/Plantilla-de-Apunte/master/images/ExampleBlock.png)

2. Índices para cada uno de los bloques, tablas, figuras y listings (bloques con código fuente).

3. Soporte para añadir bloques sin índice:  

    ```tex
    \begin{infoblock*}{Este bloque no tiene índice}
        Efectivamente.
    \end{infoblock*}
    ```

    ![InfoBlock* Example](https://raw.githubusercontent.com/rgormcl/Plantilla-de-Apunte/master/images/InfoBlockW.png)

4. Soporte para añadir bloques de código fuente dentro del documento de manera ordenada y limpia utilizando `listings`.

    ```tex
    \begin{lstlisting}[language=Java, caption={Hola Mundo en Java™}]
    public class Example{
        public static void main(String[] args){
            System.out.println("Hola Mundo");
        }
    }
    ```

    ![Listings Example](https://raw.githubusercontent.com/rgormcl/Plantilla-de-Apunte/master/images/Listings.png)

5. Sangría e indentación del texto y títulos mejorada.

6. Algunos comandos utiles (por ejemplo `\separation` que entrega una separación vertical de 2mm).  

7. Separación del cuerpo del documento, archivos externos y lógica de la plantilla.

8. Código fuente de la plantilla escrito de manera limpia y ordenada.

## Descarga

Ultima versión de la plantilla:

- Para descargar [haz clic aquí](https://github.com/rgormcl/Plantilla-de-Apunte/releases/latest/download/Plantilla-Apunte.zip).

Versiones anteriores:

- Para ver la lista [haz clic aquí](https://github.com/rgormcl/Plantilla-de-Apunte/releases/).
  
## Demostración y Ejemplos

La plantilla viene con información y textos de ejemplo para mostrar la utilización de sus características, aprovéchalas para inspirarte, modificarlas, eliminarlas, copiarlas y pegarlas por doquier.

Una demostración disponible de la plantilla se encuentra en el binario ([`examples/Plantilla de Apunte.pdf`](https://github.com/rgormcl/Plantilla-de-Apunte/raw/master/examples/Plantilla%20de%20Apunte.pdf)).

## Compilación del Proyecto

### Prerrequisitos

- Para compilar necesitas tener instalada una versión de TeX:

  - Recomiendo [Tex Live](https://www.tug.org/texlive/) (Multiplataforma).

    - Instalación completa en Ubuntu:  

      `sudo apt install texlive-full`

  - Otra que recomiendo es [ProText](https://www.tug.org/protext/) (solo para Windows).

- Puedes utilizar cualquier editor de texto/LaTeX que tengas instalado.  
Personalmente recomiendo [VSCode](https://code.visualstudio.com/) con la extensión [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop), ambos son gratuitos y multiplataforma (Windows, Mac, GNU/Linux...).
  
### Compilación

- Para compilar en [VSCode](https://code.visualstudio.com/) con la extensión [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop), deberás abrir el archivo `Plantilla de Apunte.tex` y compilarlo con las teclas (`Ctrl + Alt + B`), automáticamente se generan los binarios. Otra forma es simplemente guardando el documento.

- También es posible compilar utilizando `make` proveído por el `Makefile`.

## Contribuir  

Pasos para contribuir:

1. Crea un fork del proyecto.
2. Añade/Arregla algo.
3. Crea una pull request.  

## Errores

Si encuentras un error en la plantilla no dudes en publicar un `issue` [aquí](https://github.com/rgormcl/Plantilla-de-Apunte/issues).  
