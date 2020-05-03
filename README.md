# Plantilla de Apunte

<div style="text-align:center">
    <a href="https://github.com/rgormcl/Plantilla-de-Apunte/issues">
        <img alt="GitHub issues" src="https://img.shields.io/github/issues/rgormcl/Plantilla-de-Apunte">
    </a>
    <a href="https://github.com/rgormcl/Plantilla-de-Apunte/network">
        <img alt="GitHub forks" src="https://img.shields.io/github/forks/rgormcl/Plantilla-de-Apunte">
    </a>
    <a href="https://github.com/rgormcl/Plantilla-de-Apunte/stargazers">
        <img alt="GitHub stars" src="https://img.shields.io/github/stars/rgormcl/Plantilla-de-Apunte">
    </a>
    <a href="https://github.com/rgormcl/Plantilla-de-Apunte/blob/master/LICENSE">
        <img alt="GitHub license" src="https://img.shields.io/github/license/rgormcl/Plantilla-de-Apunte">
    </a>
    <a href="https://github.com/rgormcl/Plantilla-de-Apunte/releases/latest">
        <img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/rgormcl/Plantilla-de-Apunte">
    </a>
</div>

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

Una demostración disponible de la plantilla se encuentra en el binario (`.pdf`).

## Compilación del Proyecto

Puedes utilizar cualquier editor de texto/LaTeX que tengas instalado. Personalmente recomiendo [VSCode](https://code.visualstudio.com/) con la extensión [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop), ambos son gratuitos y multiplataforma (Windows, Mac, GNU/Linux...).

Para compilar necesitas tener instalada una versión de TeX:

- Recomiendo [Tex Live](https://www.tug.org/texlive/) (Multiplataforma).
  
  - Instalación completa en Ubuntu:  

    `sudo apt install texlive-full`
  
- Otra que recomiendo es [ProText](https://www.tug.org/protext/) (solo para Windows).
  
Para compilar en [VSCode](https://code.visualstudio.com/) con la extensión [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop), deberás abrir el archivo `Plantilla de Apunte.tex` y compilarlo con las teclas (`Ctrl + Alt + B`), automáticamente se generan los binarios. Otra forma es simplemente guardando el documento.

También es posible compilar utilizando `make` proveído por el `Makefile`.

## Errores

Si encuentras un error en la plantilla no dudes en publicar un `issue`.  
