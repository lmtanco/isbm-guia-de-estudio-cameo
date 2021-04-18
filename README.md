# GUÍA DE ESTUDIO ISBM - ¿Qué debemos saber hacer en CAMEO?
A study-guide of Cameo Systems Modeler (in Spanish) for a module on MBSE for the Master's Deg. in Telecommunication Engineering at ETSIT UMA.  

La mejor forma de usar esta guía es abrir Cameo e ir chequeando si se sabe hacer
lo que cada uno de los ítems indica. En este formato, aparecen “pistas” más o
menos explícitas, de cómo se hace lo que el ítem pide.

## General Entorno Cameo

*   Crear un modelo y estructurar los distintos elementos del modelo en forma de
    árbol de *Packages*.

*   Distinguir entre:

    *   Vistas del modelo (Containment, Diagrams, Structure)

    *   Diagramas que representan determinados elementos del modelo y sus
    relaciones.

*   Crear elementos del modelo desde su diagrama correspondiente.

*   Representar elementos del modelo ya creados, en su diagrama/s
    correspondiente/s.

*   Encontrar un elemento que tenemos localizado en un diagrama en la vista
    *Containment* del modelo.

    > Seleccionado el elemento, Menú emergente botón derecho-\> Select in
    > Containment tree

*   Encontrar en un diagrama abierto la representación de un determinado
    elemento que tenemos localizado en una vista del modelo.

    > Seleccionado el elemento, Menú emergente botón derecho-\> Go to -\> Usage in
    > Diagrams

*   Eliminar elementos del modelo desde alguna vista del modelo. Tener claro que
    Borrar un elemento de un diagrama NO es eliminarlo del modelo.

*   Dar distintas apariencias en los diagramas a los elementos del modelo.

    > Seleccionado el elemento, Menú emergente botón derecho -\> Edit Compartments
    
    > Seleccionado el elemento, Menú emergente botón derecho -\> Symbol Properties
    > \-\> Expert  
    > \-\> Show Stereotypes

*   Encontrar y eliminar del modelo relaciones entre elementos del modelo ya
    creados, seleccionando:

    *   La relación en el Diagrama correspondiente (si está representada).

    *   Los elementos implicados en la relación en la vista *Containment* del
        modelo.

        > Abrir la ventana de Especificaciones del elemento: Seleccionado el
        > elemento, Menú emergente botón derecho-\> Specification (o simplemente
        > doble click sobre el elemento)

        > En la ventana de especificaciones -\> Submenú Relations

*   En un diagrama en dónde esté representado un determinado elemento del
    modelo, mostrar sus relaciones con otros elementos ya representados en el
    diagrama

    > Seleccionado el elemento, Menú emergente botón derecho-\> Display -\>
    > Display Paths

*   En un diagrama en dónde esté representado un determinado elemento del
    modelo, mostrar sus relaciones con otros elementos no presentes en el
    diagrama.

    > Seleccionado el elemento, Menú emergente botón derecho-\> Display -\>
    > Display Related Elements

## Diagramas de bloques para modelar el contexto.

*   Distinguir entre un diagrama de bloques (bdd) y un diagrama interno de
    bloques (ibd).

*   Crear actores y bloques; crear bloques de tipo *system*, *system* *context*,
    *external* desde la vista *Containment* y desde las paletas de componentes
    del diagrama de definición de bloques.

*   Crear relaciones de agregación entre bloques.

    > Esta relación tiene sentido en el bdd

*   Crear una relación de generalización (clasificación) entre bloques.

    > Esta relación tiene sentido en el bdd

*   Crear relaciones de conexión entre bloques.

    > Esta relación tiene sentido en el ibd

*   Crear puertos de tipo proxy en la frontera de los bloques, y crear
    conexiones ente bloques a través de estos puertos.

    > Esta relación tiene sentido en el diagrama de bloques interno

*   Crear un modelo de contexto en sus dos fases: primero, el bdd; luego, el ibd
    del bloque *system context*.

## Diagramas de casos de uso para modelar los escenarios operacionales:

*   Utilizar el perfil de Cameo *UseCase Description Profile*.

*   Introducir la descripción del escenario principal, las precondiciones y las
    postcondiciones del caso de uso, en ventana de especificación del caso de
    uso.

*   Crear diagramas de casos de uso.

*   Crea actores y casos de uso desde la vista *Containment.*

*   Colocar casos de uso sobre el sistema de interés (bloque *system*) en el
    diagrama de casos de uso.

*   Crear relaciones *include* (incluye a) entre casos de uso.

    > Ojo con el sentido de las flechas (la flecha va sobre el "a")

*   Crear una relación de generalización (clasificación) entre actores, y entre
    casos de uso.

## Diagramas y tablas de requisitos para modelar necesidades y capacidades

*   Crear requisitos y rellenar sus campos principales: identificador, nombre
    corto y descripción.

*   Crear relaciones de contención entre requisitos (*parent y child
    requirements*) desde la vista *Containment* y desde el diagrama de
    requisitos.

*   Encontrar y eliminar *del modelo* relaciones de contención entre requisitos
    desde la vista *Containment.*

*   Aplicar estereotipos de tipo *Need* o *Capability* a requisitos.

*   Crear una matriz de trazabilidad entre *Needs* y casos de uso.

*   Crear una matriz de trazabilidad entre *Capabilities* y *Needs*.
