# Paygen

**Paygen** es una herramienta que permite agregar y ejecutar código en Bash o Python a un archivo específico desde la línea de comandos. También incluye un nuevo comando `-f` que permite agregar el código de un archivo al payload.

## Uso Básico

La sintaxis básica para usar Paygen es:


      ./paygen <file_name> -p | -b [-f <file_with_code>]

Donde:

<file_name> es el nombre del archivo al que se agregará el código.
-p indica que el código es Python.
-b indica que el código es Bash.
-f indica que el código se tomará de un archivo especificado en lugar de proporcionar el código directamente.

## Ejemplos
Agregar y Ejecutar Código Bash Directamente
