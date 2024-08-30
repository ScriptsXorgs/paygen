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

     ./paygen my_script.sh -b 'echo "Hello World!"'

Este comando agrega echo "Hello World!" al archivo my_script.sh y lo ejecuta como un script Bash.

## Agregar y Ejecutar Código Python Directamente

    ./paygen my_script.py -p 'print("Hello World!")'
Este comando agrega print("Hello World!") al archivo my_script.py y lo ejecuta como un script Python.

## Agregar y Ejecutar Código Bash desde un Archivo
    ./paygen my_script.sh -b -f keyware.txt
Este comando agrega el código contenido en keyware.txt al archivo my_script.sh y lo ejecuta como un script Bash.

## Agregar y Ejecutar Código Python desde un Archivo
    ./paygen my_script.py -p -f keyware.txt
Este comando agrega el código contenido en keyware.txt al archivo my_script.py y lo ejecuta como un script Python.

## Parametros
-b: Agrega el código Bash proporcionado al archivo especificado y lo ejecuta.
-p: Agrega el código Python proporcionado al archivo especificado y lo ejecuta.
-f <file_with_code>: Indica que el código se tomará de un archivo especificado, en lugar de proporcionarlo directamente en la línea de comandos.

## Instalación

1. Clona el repositorio.

      git clone https://github.com/ScriptsXorgs/paygen.git
      cd paygen

2. Asegúrate de que el archivo paygen sea ejecutable:
      chmod +x paygen

3. Ahora puedes usar paygen siguiendo los ejemplos proporcionados.

Licencia
Este proyecto está licenciado bajo la Licencia Apache.
   
