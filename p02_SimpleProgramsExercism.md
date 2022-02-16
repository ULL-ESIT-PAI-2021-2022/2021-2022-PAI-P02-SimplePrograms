# Práctica 2. Programas simples.
### Factor de ponderación: 4

### Objetivos
Los objetivos de esta práctica son:
* Realiar algunas tareas administrativas previas para facilitar el trabajo en la asignatura
* Conocer y configurar el entorno de trabajo de la asignatura en el sistema Linux del IaaS
* Configurar y practicar el uso del Visual Studio Code para editar ficheros en la máquina IaaS de la asignatura
* Instalar un servidor web estático en la máquina virtual de la asignatura
* Conocer la plataforma Jutge

### Rúbrica de evaluacion del ejercicio
Se señalan a continuación los aspectos más relevantes (la lista no es exhaustiva)
que se tendrán en cuenta a la hora de evaluar esta práctica:
* Se valorará la realización de las diferentes tareas que se proponen
* El alumnado ha de acreditar que es capaz de editar ficheros de forma remota en su VM usando VSC
* El alumnado ha de ser capaz de instalar y mantener ejecutando un servidor web estático
* El alumnado debe ser capaz de subir la solución a un problema de Jutge a esa plataforma

### Jutge
Cuando se inscriba Ud. en el curso `PAI - 2021-2022` de 
[Jutge](https://jutge.org/),
hallará una lista de problemas de programación de diferente dificultad.

El objeto de esta práctica es que comience Ud. a desarrollar algunos de esos ejercicios.

En el directorio `first-numbers-P37500` de esta práctica encontrará el fichero `first-numbers-P37500.js`
que es una posible solución al problema 
[P37500 First numbers](https://jutge.org/problems/P37500_en)
de Jutge.

Utilice ese programa como ejemplo de cómo debieran ser los programas que escribiremos en PAI.

### Comentarios de cabecera
Una buena práctica en el ámbito de la documentación del código consiste en incluir un bloque de comentarios al comienzo
de todos los ficheros de un proyecto de desarrollo de software.
El siguiente es un ejemplo de comentario de bloque que debería incluirse al comienzo de todos los ficheros
(`*.js`) de sus proyectos de programación:

```
/**
 * Universidad de La Laguna
 * Escuela Superior de Ingeniería y Tecnología
 * Grado en Ingeniería Informática
 * Programación de Aplicaciones Interactivas 2021-2022
 *
 * @author Alan Turing
 * @since Feb 16 2022
 * @desc First numbers
 *       The program reads a number n, and prints all numbers between 0 and n.
 * @see {@link https://jutge.org/problems/P37500_en}
 * @see {@link https://www.npmjs.com/package/@types/readline-sync}
 *
 */

```


Todo fichero debiera contener (etiqueta `@desc`) una breve descripción del contenido del fichero.
Si fuera necesario se incluirá a continuación una descripción más detallada.
Obviamente el comentario específico así como el nombre del fichero debieran particularizarse para cada caso
concreto.

Incluya siempre un bloque de comentarios similar al anterior en todos sus ficheros.
Preste cuidado a la práctica habitual de "copiar y pegar" estos comentarios de un proyecto a otro, puesto que parte de la
información cambiará.

En proyectos de desarrollo de software de cierta entidad es común que este bloque de comentarios de cabecera de los ficheros
incluya además la licencia de software bajo la que se publica el programa en cuestión.
A título de ejemplo, 
[consulte el texto](https://www.gnu.org/licenses/gpl-3.0.html)
que se debiera incluir en los ficheros para publicarlos bajo licencia GPLv3.

### The modern mode, "use strict"
Incluya siempre en sus programas la directiva 
['use strict';](https://javascript.info/strict-mode)

### Ejercicios de Jutge
* Escriba programas que solucionen los siguientes problemas y evalúe su solución utilizando Jutge.
* Escriba todos los programas de modo que estén estructurados en funciones.
Debiera haber como mínimo dos funciones siendo `main()` una de ellas.
* Recuerde que Jutge solo evalúa la corrección de su programa desde un punto de vista del funcionamiento.
Su código ha de cumplir adicionalmente con los requisitos de modularidad, formato y estilo.

1. [P48107](https://jutge.org/problems/P48107) Integer division and remainder of two natural numbers
2. [P29973](https://jutge.org/problems/P29973) Triangle
3. [P90615](https://jutge.org/problems/P90615) Maximum of three integer numbers
4. [P70955](https://jutge.org/problems/P70955) How many seconds are they?
5. [P34279](https://jutge.org/problems/P34279) Add one Second.
6. [P51352](https://jutge.org/problems/P51352) Elementos.
7. [P51126](https://jutge.org/problems/P51126) Intervals (I)
8. [P33839](https://jutge.org/problems/P33839) Sum of Digits 
9. [P97969](https://jutge.org/problems/P97969) Counting a's (I)
10. [P80660](https://jutge.org/problems/P80660) The sequence of Collatz

### Referencias
* [Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html)
* [Jutge web site](https://jutge.org/)
* [Jutge information](https://docs.google.com/presentation/d/14UvZPw4OJvogp6afLeouOAODcBNo5JhgePBQfkiAkic/edit?usp=sharing)
* [Jutge documentation](https://jutge.org/documentation)

