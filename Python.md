&#x09;				■ Python

♦ METODOS DE LAS CADENAS DE CARACTERES:

→ Capitalize

♦ Permiten encontrar caracteres o cadenas dentro de otra:

→ Find

→ index

♦ Retorna true o false:

→ isalnum

→ isalpha

→ isdecimal

→ isdigit

→ islower

→ isupper

→ isupper

→ upper

♦ OPERADORES ARITMETICOS:

→ =

→ -=

→ /=

→ //=

→ +=

→ \*=

→ \*\*=

→ %=

&#x09;■ LISTAS:

✅ Sintaxis básica:

🔧 Operaciones comunes con listas:

1\. Acceder a elementos:

2\. Modificar un valor:

3\. Agregar elementos:

4\. Eliminar elementos:

5\. Longitud de una lista:

6\. Recorrer con un bucle:

7\. Verificar si un valor está:

🧠 Otras funciones útiles:

♦ Métodos

→ lista.sort()

→ sorted( lista )

→ lista.reverse()

→ lista.copy()

→ lista.clear()

→ lista.count( x )

→ lista.index( x )

→ lista.extend( otra\_lista )

&#x09;■ TUPLA

&#x09;■ Archivos

► Modos de apertura de Archivos:

→ r (read - leer)

→ w (write - escribir)

→ a (append - añadir)

→ Agregar un + incluye leer. por ejemplo: w+ es leer y escribir.

🔹 Leer el archivo.

♦ Escribir en el archivo.



🔹 1. Abrir un archivo

► Se usa la función open(nombre, modo):

• "r" → leer (default, error si no existe).

• "w" → escribir (crea el archivo o sobrescribe).

• "a" → añadir al final (append).

• "r+" → leer y escribir.

🔹 2. Leer un archivo

🔹 3. Escribir (sobrescribir) en un archivo

✅ Con with no necesitas close(), se cierra solo.

🔹 4. Añadir contenido sin borrar lo anterior

🔹 5. Leer todas las líneas en lista

🔹 6. Escribir lista de líneas

📌 En resumen:

→ open("archivo.txt", "r") → leer.

→ open("archivo.txt", "w") → sobrescribir.

→ open("archivo.txt", "a") → agregar.

→ Usa with open(...) as f: → más seguro y limpio.



\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_



&#x20;			  		■ Python



IDLE: Entorno integrado de programación que se instala automáticamente cuando instalas Python



¿Qué puede hacer IDLE?

Escribir, Editar, Ejecutar.



\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_



♦ METODOS DE LAS CADENAS DE CARACTERES:



→ Capitalize : Retorna una copia de la cadena con el primer carácter en mayúsculas y el resto de minúsculas.

cadena.capitalize().



♦ Permiten encontrar caracteres o cadenas dentro de otra:

→ Find

→ index



♦ Retorna true o false:

Si solo contiene caracteres alfaNumericos:

→ isalnum



Si solo contiene caracteres alfabéticos:

→ isalpha



Si solo contiene caracteres decimales:

→ isdecimal



Si solo contiene dígitos:

→ isdigit



Si solo contiene caracteres en minúsculas:

→ islower



Si solo contiene caracteres en mayúsculas:

→ isupper



Retorna una copia en minúsculas de la cadena de caracteres.

→ lower



Retorna una copia en mayúsculas de la cadena de caracteres.

→ upper



♦ OPERADORES ARITMETICOS:

→ =

→ -=

→ /=

→ //=

→ +=

→ \*=

→ \*\*=

→ %=



\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_



&#x09;					■ LISTAS:

\['a', 'b', 'c'...]

\[1, 2, 3...]



✅ Sintaxis básica:

mi\_lista = \[10, "hola", True, 3.14]



🔧 Operaciones comunes con listas:

1\. Acceder a elementos:

print(mi\_lista\[0])  |  # 10

print(mi\_lista\[-1]) |  # 3.14 (último elemento)



2\. Modificar un valor:

mi\_lista\[1] = "mundo"



3\. Agregar elementos:

mi\_lista.append("nuevo")     |  # Al final

mi\_lista.insert(1, "medio")  |  # En índice específico



4\. Eliminar elementos:

mi\_lista.remove("mundo") | # Por valor

mi\_lista.pop()           | # Último

mi\_lista.pop(0)          | # Por índice

del mi\_lista\[2]          | # También por índice



5\. Longitud de una lista:

len(mi\_lista)



6\. Recorrer con un bucle:

for item in mi\_lista:

&#x20;   print(item)



7\. Verificar si un valor está:

"hola" in mi\_lista | # True o False



🧠 Otras funciones útiles:

♦ Método		                      Descripción

→ lista.sort()	            |   Ordena (modifica la lista).

→ sorted(lista)	            |   Ordena (sin modificar la original).

→ lista.reverse()	    |   Invierte el orden.

→ lista.copy()              |   Copia la lista.

→ lista.clear()	            |   Borra todos los elementos.

→ lista.count(x)	    |   Cuenta cuántas veces aparece x.

→ lista.index(x)            |   Devuelve el índice de x.

→ lista.extend(otra\_lista)  |   Extender la lista agregándole los elementos de otra lista.



\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_



&#x09;			■ TUPLA



Estructura de datos inmutable que contiene una secuencia ordenada de elementos.

Se pueden acceder con subíndices.



♦ CARACTERISTICAS:

secuencia ordenada de valores.

Puede contener valores de cualquier tipo de datos.

puede contener valores de distintos tipos de datos.

Cada posición de la tupla se identifica con un entero denominado 'indice'.

Es inmutable. No puede ser modificada.



\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_



&#x09;			■ Archivos



► Modos de apertura de Archivos:

• r (read - leer)

• w (write - escribir)

• a (append - añadir)

• Agregar un + incluye leer. por ejemplo: w+ es leer y escribir.



🔹 Leer el archivo.

&#x20; with open('nombre\_archivo.text', 'r') as archivo: 

&#x20;   for linea in archivo:

&#x20;     print('=== Frase ===')

&#x20;     print(linea)

&#x20;     

&#x20; ♦ Escribir en el archivo.

&#x20; with open('nombre\_archivo.txt', 'w') as archivos: print



🔹 1. Abrir un archivo



► Se usa la función open(nombre, modo):



• "r" → leer (default, error si no existe).

• "w" → escribir (crea el archivo o sobrescribe).

• "a" → añadir al final (append).

• "r+" → leer y escribir.



Ejemplo:



archivo = open("datos.txt", "w")  # Abre para escribir

archivo.write("Hola, Python!\\n")

archivo.close()



🔹 2. Leer un archivo

archivo = open("datos.txt", "r")

contenido = archivo.read()   # Lee todo

print(contenido)

archivo.close()





• O leer línea por línea:



archivo = open("datos.txt", "r")

for linea in archivo:

&#x20;   print(linea.strip())  # .strip() quita saltos de línea

archivo.close()



🔹 3. Escribir (sobrescribir) en un archivo

with open("datos.txt", "w") as archivo:

&#x20;   archivo.write("Primera línea\\n")

&#x20;   archivo.write("Segunda línea\\n")





✅ Con with no necesitas close(), se cierra solo.



🔹 4. Añadir contenido sin borrar lo anterior

with open("datos.txt", "a") as archivo:

&#x20;   archivo.write("Nueva línea añadida\\n")



🔹 5. Leer todas las líneas en lista

with open("datos.txt", "r") as archivo:

&#x20;   lineas = archivo.readlines()



print(lineas)   # \['Primera línea\\n', 'Segunda línea\\n', 'Nueva línea añadida\\n']



🔹 6. Escribir lista de líneas

lineas = \["Uno\\n", "Dos\\n", "Tres\\n"]



with open("numeros.txt", "w") as archivo:

&#x20;   archivo.writelines(lineas)



📌 En resumen:

→ open("archivo.txt", "r") → leer.

→ open("archivo.txt", "w") → sobrescribir.

→ open("archivo.txt", "a") → agregar.

→ Usa with open(...) as f: → más seguro y limpio.



\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ ■ PRINCIPIOS PYTHON \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_



SRP

OCP

CSP

ISP

DIP



\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ ■ IMPORTACIONES python \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_



→ from flask import Flask, jsonify, render\_template\_string, send\_from\_directory

• Flask: Crea la instancia principal de tu aplicación web. Es el núcleo del servidor.

• jsonify: Convierte diccionarios o listas de Python en respuestas JSON válidas para APIs. Ideal para enviar datos al frontend.

• render\_template\_st: Renderiza HTML directamente desde un string (útil para pruebas rápidas o plantillas generadas dinámicamente).

• send\_from\_director: Sirve archivos estáticos (como imágenes, PDFs, etc.) desde una carpeta específica. Muy útil para evidencia visual o descargas



\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_



→ from flask\_cors import CORS

La línea importa la función CORS desde el paquete , que se usa para habilitar el Cross-Origin Resource Sharing en tu aplicación Flask.



¿Cómo se usa?

→ app = Flask(\_\_name\_\_)



&#x09;EJEMPLO:

app = Flask(\_\_name\_\_, static\_folder='.')



&#x09;¿Qué significa static\_folder='.'?

• static\_folder es un parámetro opcional que define dónde están tus archivos estáticos (como imágenes, CSS, JS, PDFs, etc.).

• El valor '.' indica que esos archivos están en el directorio raíz del proyecto, es decir, donde está tu app.py.



&#x09;✅ ¿Cuándo usar ?

• Para pruebas rápidas.

• Cuando tus archivos están en el mismo nivel que .

• Si estás sirviendo evidencia visual desde el backend y no quieres mover los archivos a otra carpeta.



\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_



&#x09;🔐 ¿Qué es CORS?

CORS (Cross-Origin Resource Sharing) es una política de seguridad que los navegadores aplican para evitar que una página web haga peticiones a otro dominio distinto del que la sirvió.

Por ejemplo:

\- Si tu frontend está en http://localhost:3000 (React, Bootstrap, etc.)

\- Y tu backend Flask está en http://localhost:5000

\- Entonces el navegador bloqueará las peticiones AJAX/fetch a tu API Flask… a menos que uses CORS.



\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_



&#x09;🔹 import pyodbc

\- ¿Qué hace?

Permite conectarte a bases de datos como SQL Server desde Python usando el protocolo ODBC.





&#x09;🔹 import os

\- ¿Qué hace?

Accede a funciones del sistema operativo: rutas, archivos, variables de entorno, etc.

\- ¿Ejemplos comunes?

\- Obtener la ruta actual:



EJEMPLOS:

• Construir rutas seguras:

&#x09;→ archivo = os.path.join('static', 'imagen.jpg') >

• Obtener la ruta actual:

&#x09;→ ruta = os.getcwd()



\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_



📁 .venv - Carpeta de entorno virtual

📁 venv:  es una herramienta integrada en Python que permite crear entornos virtuales. Esencial para mantener tus proyectos organizados y evitar conflictos entre dependencias.

⚙️ ¿Para qué sirve ?

• ✅ Separar dependencias: Cada proyecto puede tener sus propias versiones de librerías.

• ✅ Evitar conflictos: No se mezclan paquetes entre proyectos.

• ✅ Facilita despliegue: Puedes replicar el entorno en otros equipos usando .

🛠️ ¿Cómo se crea y activa?

1\. Crear el entorno:



🛠️ ¿Cómo se crea y activa?

1\. Crear el entorno:

→ python -m venv nombre\_del\_entorno | Esto crea una carpeta con el entorno virtual.

2\. Activar el entorno:

\- En Windows:

→ nombre\_del\_entorno\\Scripts\\activate

3\. Instalar paquetes:

→ pip install flask

4\. Guardar dependencias:

→ pip freeze > requirements.txt

5\. Desactivar:

→ deactivate



\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ ■ jsonify \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_



¿Qué hace jsonify?

🔧 Función principal:

jsonify convierte datos Python en respuestas HTTP con formato JSON válido.



\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ ■ .JSON  \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_



El formato .json (JavaScript Object Notation) es un tipo de archivo que se utiliza para almacenar y transportar datos estructurados de forma ligera y legible tanto para humanos como para máquinas. Aquí te explico qué hace y cómo se usa:



📦 ¿Qué hace un archivo .json?

Un archivo .json guarda información en forma de pares clave-valor, similar a un diccionario en Python o un objeto en JavaScript. Su propósito principal es:

\- Intercambiar datos entre sistemas (por ejemplo, entre frontend y backend)

\- Guardar configuraciones (como en VS Code, ESLint, etc.)

\- Persistir información estructurada (como listas de productos, usuarios, inventarios)



🧠 ¿Cómo se ve un .json?

{

&#x20; "nombre": "Brayan",

&#x20; "ocupacion": "Almacenista",

&#x20; "habilidades": \["SQL", "Python", "Flask"],

&#x20; "activo": true

}



🔧 ¿Dónde se usa?

\- APIs REST: Las respuestas suelen venir en formato JSON.

\- Bases de datos NoSQL: MongoDB usa documentos JSON.

\- Configuraciones: Archivos como package.json, tsconfig.json, settings.json.

\- Frontend y backend: Para enviar y recibir datos entre cliente y servidor.



✅ Ventajas

\- Ligero y fácil de leer

\- Compatible con muchos lenguajes (Python, JavaScript, Java, etc.)

\- Ideal para estructuras anidadas y listas



\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ ■ 🔐 ¿QUE ES CORS? \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_



CORS = Cross-Origin Resource Sharing (Compartir Recursos de Origen Cruzado)



Es un mecanismo de seguridad del navegador que controla qué sitios web pueden acceder a tu API.

