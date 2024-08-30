#Paygen
paygen es una herramienta que permite agregar y ejecutar código en Bash o Python a un archivo específico desde la línea de comandos. El código puede ser en formato Bash o Python y se agregará al archivo especificado para su posterior ejecución.

#Uso Básico
La sintaxis básica para ejecutar paygen es:


./paygen <file_name> -p | -b <code>
Donde>

<file_name> > Nombre del archivo al que se agregará el código.
-p> Indica que el código es Python.
-b> Indica que el código es Bash.
<code> El código que se agregará al archivo especificado.
Ejemplos
Agregar y Ejecutar Código Bash
Para agregar código Bash a un archivo y ejecutarlo, usa el parámetro -b:


./paygen my_script.sh -b 'echo "Hello World!"'
Este comando agregará echo "Hello World!" al archivo my_script.sh y ejecutará el archivo como Bash.

Agregar y Ejecutar Código Python
Para agregar código Python a un archivo y ejecutarlo, usa el parámetro -p:



./paygen my_script.py -p 'print("Hello World!")'
Este comando agregará print("Hello World!") al archivo my_script.py y ejecutará el archivo como Python.

#Parámetros
-b <code> > Agrega el código Bash proporcionado al archivo especificado y lo ejecuta.
-p <code> > Agrega el código Python proporcionado al archivo especificado y lo ejecuta.
Instalación
Asegúrate de tener permisos de ejecución para paygen. Puedes hacer que el archivo sea ejecutable con el siguiente comando:

<git clone https://github.com/ScriptsXorgs/paygen.git>
<cd paygen>
<bash paygen>

Luego, ejecuta paygen siguiendo los ejemplos anteriores.
