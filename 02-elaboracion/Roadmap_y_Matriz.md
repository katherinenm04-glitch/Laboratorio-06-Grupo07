# 2. Roadmap de Iteraciones y Matriz Fase-Artefacto

## Roadmap de Iteraciones RUP (Procedimiento - Paso 2)
| Fase RUP | Iteración | Objetivo de la Iteración | Entregables Verificables | Riesgos Mitigados / Criterio de Salida |
| :--- | :---: | :--- | :--- | :--- |
| **Inicio** | I1 | Acordar alcance, actores y validar factibilidad del negocio. | Documento de Visión v1, Modelo de CU de alto nivel. | R01 (Incompatibilidad hardware): Aprobación del alcance inicial. |
| **Elaboración** | E1 | Validar arquitectura base y flujos críticos de riego. | SRS breve, Diagramas UML (Actividad y Secuencia). | R02 (Pérdida conectividad IoT): Validar arquitectura ejecutable base. |
| **Elaboración** | E2 | Diseñar modelos con excepciones y reportes. | Modelo BPMN con compuertas XOR, Matriz de excepciones. | R03 (Falta de agua en reservorio): Aprobación de flujos alternos. |
| **Construcción** | C1 | Registrar cultivos y programar riegos. | Incremento funcional v0.8, código probado. | Pruebas unitarias al 100% en escenarios normales. |
| **Construcción** | C2 | Integrar validaciones y control de errores. | Módulo de alertas, servicios de notificación. | Integración completa de servicios de excepción. |
| **Transición** | T1 | Piloto con usuarios finales en campo y correcciones. | Manual de usuario, Acta de aceptación. | Conformidad firmada por el usuario. |

## Matriz Fase-Artefacto UML (Procedimiento - Paso 3)
| Fase RUP | Artefacto / Diagrama UML Sugerido | Uso Específico en AgroVerde S.A.C. |
| :--- | :--- | :--- |
| **Inicio** | Documento de Visión, Diagrama de Casos de Uso (alto nivel) | Definir el alcance operativo y los actores (Agricultor, Administrador). |
| **Elaboración** | Diagrama de Actividades, Clases (dominio), Secuencia | Validar las reglas de negocio críticas y la lógica de programación de riegos. |
| **Construcción** | Diagrama de Clases (diseño), Secuencia refinada, Estados | Implementar la estructura orientada a objetos y verificar escenarios de prueba. |
| **Transición** | Manual de usuario, Pruebas de aceptación, Diagrama de Despliegue | Validar la adopción en campo y la puesta en marcha en servidores y nodos IoT. |
