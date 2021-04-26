# GUÍA DE ESTUDIO ISBM - ¿Qué debemos saber hacer en CAMEO?

La mejor forma de usar esta guía es abrir Cameo e ir chequeando si se sabe hacer
lo que cada uno de los ítems indica. En este formato, aparecen “pistas” más o
menos explícitas, de cómo se hace lo que el ítem pide.

## General Entorno Cameo

*   Cosas generales que tenemos que saber hacer en el entorno cameo: [General Entorno Cameo](https://github.com/lmtanco/isbm-guia-de-estudio-cameo/blob/main/general-entorno-cameo.md)
*   Modelar el contexto mediante diagramas de bloque: [Modelar el Contexto](https://github.com/lmtanco/isbm-guia-de-estudio-cameo/blob/main/modelo-contexto.md)

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
    
*   Crear identificadores únicos para los requisitos con los prefijos que queramos. 
    > En el requisito. Menú emergente botón derecho \-\> Specification \-\> Id  
         
*   Crear relaciones de contención entre requisitos (*parent y child
    requirements*) desde la vista *Containment* y desde el diagrama de
    requisitos.
    
*   Encontrar y eliminar *del modelo* relaciones de contención entre requisitos
    desde la vista *Containment.*
    
*   Aplicar estereotipos de tipo *Need* o *Capability* a requisitos.

*   Crear una matriz de trazabilidad entre *Needs* y casos de uso.

*   Crear una matriz de trazabilidad entre *Capabilities* y *Needs*.
