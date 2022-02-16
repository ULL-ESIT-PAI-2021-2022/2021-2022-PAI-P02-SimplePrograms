# Práctica 2. Programas simples. Exercism
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

**Avise al profesor** al finalizar la realización de cada una de las **TAREAS** que se indican a continuación. 
No inicie una nueva tarea sin haber revisado la anterior.

### Ejercicios de Jutge
22. **TAREA #10** En su correo electrónico debe tener un mensaje de invitación a la plataforma Jutge.
Acepte esa invitación y regístrese en la plataforma con su **cuenta de correo institucional**.

[Jutge](https://jutge.org/) es una plataforma que ha sido desarrollada en la
[UPC](https://www.upc.edu/en) para uso docente en asignaturas de programación.
La plataforma ofrece una gran cantidad de problemas que los estudiantes han
de resolver y el Jutge (juez en catalán) asigna un 
[veredicto](https://jutge.org/documentation/verdicts) 
a cada solución que se suba a la plataforma.

Jutge solo evalúa los programas desde el punto de vista de la corrección del resultado que ofrecen, 
no evalúa la calidad del código en cuanto a otros aspectos: diseño, estilo, formato, etc.
Para determinar si un programa es correcto o no, Jutge aplica varios tests al programa (tests unitarios)
que tratan de acreditar la bondad de la solución, que podría ser parcialmente correcta.
Algunos de esos tests son públicos y la programadora debiera encargarse de asegurar que su programa pasa
esos tests públicos (ofrece los resultados esperados) antes de enviar el programa al juez.

[Este documento](https://docs.google.com/presentation/d/14UvZPw4OJvogp6afLeouOAODcBNo5JhgePBQfkiAkic/edit?usp=sharing)
contiene información algo más detallada sobre el uso de la plataforma Jutge. 
Estúdielas antes de comenzar a trabajar con la misma.

A la hora de escribir un programa para enviarlo a Jutge ha de tener en cuenta que el programa no ha 
de escribir otra información como salida que la requerida por los tests de Jutge.
De este modo, el mensaje inicial que se utiliza para que el programa escriba en pantalla tanto la utilidad
del mismo como su modo de uso ha de omitirse.
La recomendación que hacemos es que ese mensaje se escriba en una función que será (o no) invocada desde `main()`.

Una vez que tenga su cuenta en Jutge, realice cuantos ejercicios sea capaz de programar y súbalos para su evaluación
por el juez, hasta obtener un veredicto de 
[AC](https://jutge.org/documentation/verdicts/AC)
(Accepted).
Cuantos más problemas resuelva, más incrementará sus capacidades como programadora.
