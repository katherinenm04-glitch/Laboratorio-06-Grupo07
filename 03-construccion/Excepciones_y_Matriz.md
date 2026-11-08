# 3. Modelado de Procesos, Excepciones y Trazabilidad

## Modelado del Módulo Crítico (Procedimiento - Paso 4)
- **Módulo seleccionado:** Programación y ejecución de Riego Automatizado.
- **Flujo y Excepción:** El sistema verifica el nivel de agua disponible antes de abrir válvulas. Si no se cumple, activa el flujo alternativo `EXC-02: Agua Insuficiente`.

## Identificación de Riesgos y Mitigación (Procedimiento - Paso 6)
| Fase RUP | Riesgo Identificado | Impacto | Acción de Mitigación en el Roadmap |
| :--- | :--- | :--- | :--- |
| **Inicio** | Desacuerdo en los requerimientos clave con el cliente. | Alto | Talleres de validación y firma temprana del Documento de Visión. |
| **Elaboración** | Incompatibilidad del protocolo de telemetría con sensores IoT. | Crítico | Construir una Prueba de Concepto (POC) en la iteración E1. |
| **Construcción**| Retrasos en la integración del módulo de reportes hídricos. | Medio | Priorizar componentes core (riego/cultivos) antes de reportes secundarios. |
| **Transición** | Resistencia al uso del sistema por parte del personal de campo. | Alto | Capacitación presencial guiada y entrega de manuales simplificados. |

## Revisión por Pares - Checklist de Auditoría (Procedimiento - Paso 8)
| Criterio de Auditoría Cruzada | ¿Cumple? | Hallazgo / Corrección Aplicada |
| :--- | :---: | :--- |
| ¿Están representadas las 4 fases RUP en el roadmap? | Sí | Sin observaciones; fases completas. |
| ¿Los diagramas UML se vinculan correctamente a los RF? | Sí | Se ajustó la trazabilidad de los IDs de los Casos de Uso. |
| ¿Se incluyeron flujos alternativos y de excepción? | Sí | Se añadió el manejo de excepción por baja presión de agua. |
| ¿Los archivos editables y capturas se encuentran accesibles? | Sí | Enlaces verificados en el repositorio de GitHub. |
