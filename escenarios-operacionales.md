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
  
## Diagramas de actividad para modelar en detalle un escenario

* Crear una actividad asociada a un caso de uso.
* Crear *swimlanes* en el diagrama de actividad que representan a las partes del sistema Contexto, representadas en el *ibd* del Contexto (ver [Model de Contexto](https://github.com/lmtanco/isbm-guia-de-estudio-cameo/blob/main/modelo-contexto.md) )
* Modelar los distintos pasos del escenario como acciones de tipo *CallBehaviourAction* que realizan los actores o el sistema.
* Crear flujos de ítems a partir de los elementos del modelo de Dominio enter estas acciones y gestionarlos mediante el *Item Flow Manager*.
* Realizar estos flujos en el diagrama de Contexto.
