# Actividad-2.2

Tec de Monterrey
Act 2.2 - Verificación de las funcionalidades de una estructura de datos lineal
¿Qué tengo que hacer?
En este repositorio encontrarás el archivo "list.h" que deberás modificar para el desarrollo de esta actividad. Deberás colocar en la parte superior, en comentarios, tus datos. Por ejemplo:

// =========================================================
// File: list.h
// Author: Edward Elric - A00123456
// Date: 01/01/2021
// =========================================================
Diseña e implementa, de forma forma individual, siguiendo la especificación de la interfaz para un ADT que represente una estructura de datos lineal:

Dependiendo del ADT de estructura de datos lineal deberán implementar las operaciones CRUD (Create, Read (buscar), Update, Delete) elementos en la estructura de datos. Algunas operaciones no aplican para ciertas estructura de datos

before	Descripción	Devuelve el valor que se encuentra en previo a la primera ocurrencia de *val*.
Entrada	*val*, valor a ser buscado.
Salida	Elemento que se encuentra previo a la primera ocurrencia del elemento buscado. Si elemento *val* no existe, deberá arrojar una excepción.
Precondición	Una estructura válida.
Postcondición	Nada.
after	Descripción	Devuelve el valor que se encuentra en después de la primera ocurrencia de *val*.
Entrada	*val*, valor a ser buscado.
Salida	Elemento que se encuentra después de la primera ocurrencia del elemento buscado. Si elemento *val* no existe, deberá arrojar una excepción.
Precondición	Una estructura válida.
Postcondición	Nada.
insert_before	Descripción	Inserta un nuevo valor, *newVal*, antes de la primera ocurrencia de *lookingFor*.
Entrada	*lookingFor*, valor a ser buscado.
newVal, valor a ser insertado.

Salida	Estructura de datos actualizada con el elemento *newVal* antes de la primera ocurrencia de *lookingFor*. Si elemento *lookingFor* no existe, deberá arrojar una excepción.
Precondición	Estructura de datos válida
Postcondición	Estructura de datos debidamente actualizada
insert_after	Descripción	Inserta un nuevo valor, *newVal*, después de la primera ocurrencia de *lookingFor*.
Entrada	*lookingFor*, valor a ser buscado.
newVal, valor a ser insertado.

Salida	Estructura de datos actualizada con el elemento *newVal* despues de la primera ocurrencia de *lookingFor*. Si elemento *lookingFor* no existe, deberá arrojar una excepción.
Precondición	Estructura de datos válida
Postcondición	Estructura de datos debidamente actualizada

Todas las funcionalidades deberán de estar correctamente alineadas y documentadas.  Recuerda que todas las funcionalidades deberán pasar exitosamente todas las pruebas. Como parte de la documentación deberá incluirse la complejidad de cada una de ellas.

Para probar tu implementación, ejecuta el comando:

make
Este comando compilará tu código y generará una serie de archivos de pruebas llamados "runTest#", donde # será un número de prueba. Para ejecutar prueba, solo deberás ejecutar el archivos correcto. Por ejemplo, si quiere revisar si mi código cumple con la prueba número 3, deberías ejecutar:

./runTest3
¿Bajo qué criterios se evalúa mi evidencia?
80% - Para cada una de las funcionalidades se evaluará:

Excelente (80%) - pasa correctamente todos los casos de prueba.
Muy Bien (60%) - pasa correctamente el 75% de los casos de prueba.
Bien (40%) - pasa correctamente el 50% de los casos de prueba.
Insuficiente (20%) - pasa correctamente menos del 50% de los casos de prueba.
10% - El código deberá seguir los lineamientos estipulados en el estándar de codificación: liga_estándar_codificación

10% - Se respetan los nombres de las funciones en la aplicación.

¿Dónde la entrego?
Cuando hayas pasado todas las pruebas, recuerda publicar el código en tu repositorio (git push).
