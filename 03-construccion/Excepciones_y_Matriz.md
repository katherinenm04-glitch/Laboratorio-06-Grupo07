# 3. Modelado de Procesos, Excepciones y Trazabilidad

## Modelado del Módulo Crítico (Procedimiento - Paso 4)
- **Módulo seleccionado:** Programación y ejecución de Riego Automatizado[cite: 60].
- **Flujo y Excepción:** El sistema verifica el nivel de agua disponible antes de abrir válvulas. Si no se cumple, activa el flujo alternativo `EXC-02: Agua Insuficiente`[cite: 60, 61].

## Identificación de Riesgos y Mitigación (Procedimiento - Paso 6)
| Fase RUP | Riesgo Identificado | Impacto | Acción de Mitigación en el Roadmap |
| :--- | :--- | :--- | :--- |
| **Inicio** | Desacuerdo en los requerimientos clave con el cliente[cite: 62]. | Alto[cite: 62] | Talleres de validación y firma temprana del Documento de Visión[cite: 62]. |
| **Elaboración** | Incompatibilidad del protocolo de telemetría con sensores IoT[cite: 62]. | Crítico[cite: 62] | Construir una Prueba de Concepto (POC) en la iteración E1[cite: 62]. |
| **Construcción**| Retrasos en la integración del módulo de reportes hídricos[cite: 62]. | Medio[cite: 62] | Priorizar componentes core (riego/cultivos) antes de reportes secundarios[cite: 62]. |
| **Transición** | Resistencia al uso del sistema por parte del personal de campo[cite: 62]. | Alto[cite: 62] | Capacitación presencial guiada y entrega de manuales simplificados[cite: 62]. |

## Revisión por Pares - Checklist de Auditoría (Procedimiento - Paso 8)
| Criterio de Auditoría Cruzada | ¿Cumple? | Hallazgo / Corrección Aplicada |
| :--- | :---: | :--- |
| ¿Están representadas las 4 fases RUP en el roadmap?[cite: 62] | Sí[cite: 62] | Sin observaciones; fases completas[cite: 62]. |
| ¿Los diagramas UML se vinculan correctamente a los RF?[cite: 63] | Sí[cite: 63] | Se ajustó la trazabilidad de los IDs de los Casos de Uso[cite: 63]. |
| ¿Se incluyeron flujos alternativos y de excepción?[cite: 63] | Sí[cite: 63] | Se añadió el manejo de excepción por baja presión de agua[cite: 63]. |
| ¿Los archivos editables y capturas se encuentran accesibles?[cite: 63] | Sí[cite: 63] | Enlaces verificados en el repositorio de GitHub[cite: 63]. |
