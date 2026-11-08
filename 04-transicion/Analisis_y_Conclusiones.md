# 4. Registros, Análisis de Resultados y Conclusiones

## Análisis de Resultados (Guía del Estudiante - Sección II)
- **Desarrollo:** La integración del Proceso Unificado RUP con el modelado UML permitió estructurar un sistema complejo de manera controlada.
- **Brechas identificadas:** Durante la elaboración del diagrama de secuencia inicial, no se contemplaban las respuestas ante la pérdida temporal de red de los sensores IoT.
- **Corrección propuesta:** Se incorporó un flujo alternativo de reintentos automáticos y una bitácora de eventos locales, lo que incrementó la robustez del sistema y garantizó la consistencia de los datos almacenados en la base de datos de AgroVerde S.A.C.

## Conclusiones (Guía del Estudiante - Sección III)
1. **Planificación iterativa:** La planificación bajo el marco RUP facilitó la distribución progresiva del trabajo en 4 fases, permitiendo mitigar los riesgos de conectividad IoT e integración durante la Fase de Elaboración antes de iniciar el desarrollo masivo en Construcción.
2. **Modelado de excepciones:** El modelado explícito de procesos no tradicionales y excepciones mediante notación BPMN y fragmentos `alt` en diagramas de secuencia incrementó la robustez del sistema AgroVerde S.A.C., garantizando la continuidad del negocio ante fallas operativas como el desabastecimiento de agua o la pérdida de señal de sensores.
3. **Trazabilidad:** La elaboración de la Matriz de Trazabilidad Actividades-Requisitos aseguró una correspondencia biunívoca entre los Requisitos Funcionales (RF-01 a RF-04) y sus realizaciones en UML, evitando funciones huérfanas y garantizando que cada flujo de error cuente con su mecanismo de validación.
