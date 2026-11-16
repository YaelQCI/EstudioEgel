# Errores y repasos

Diagnóstico inicial completado el 12 de noviembre de 2026.

| ID | Tema / reactivo | Evidencia | Corrección o refuerzo | Repasos previstos | Estado |
|---|---|---|---|---|---|
| E01 | Valores límite / 15 | A, seguro; correcta C | Probar 17,18,19,64,65,66 para rango inclusivo 18–65. El usuario declara conocerlo y posible confusión al escribir; validar antes de inferir debilidad | 13,15,19 nov. | Pendiente caso nuevo |
| E02 | Valor monetario esperado / 17 | A, adivinando; correcta B | 0.25 × 40,000 = 10,000; impacto no es valor esperado | 13,15,19 nov. | Pendiente caso nuevo |
| R01 | Cohesión / 7 | B correcta con duda | Responsabilidades relacionadas en un componente | 13,15,19 nov. | Refuerzo pendiente |
| R02 | Strategy / 8 | A correcta adivinando | Algoritmos intercambiables tras interfaz común | 13,15,19 nov. | Refuerzo pendiente |
| R03 | Atomicidad / 14 | B correcta con duda | Todo se confirma o se revierte en la transacción | 13,15,19 nov. | Refuerzo pendiente |
| R04 | Métricas / 19 | A correcta adivinando | Medir defectos normalizados; actividad no equivale a resultado | 13,15,19 nov. | Refuerzo pendiente |
| R05 | Idea central / 21 | B correcta con duda | Integrar el sentido completo con evidencia textual | 13,15,19 nov. | Refuerzo pendiente |
| R06 | Concordancia / 27 | C correcta con duda | Identificar núcleo de sujeto y concordancia verbal | 13,15,19 nov. | Refuerzo pendiente |
| R07 | Acentuación / 30 | C correcta adivinando; debilidad declarada | Validar acentuación general y diacrítica con más ejercicios | 13,15,19 nov. | Prioridad inicial |

Las fechas son propuestas de repaso, no sesiones completadas. El razonamiento de la 15 no fue desarrollado, pero el usuario aclara que conocía el tema y pudo confundirse al escribir. En la 17 confirma adivinación. No se atribuyen otras causas sin evidencia. Cerrar cada pendiente sólo tras explicar el concepto y resolver casos nuevos.


## Pendientes detectados en el diagnóstico integral — cierre de 19 bloques

| ID | Tema / evidencia | Refuerzo requerido | Estado |
|---|---|---|---|
| E08 | **CRÍTICO — Bloque 10, pregunta 7: NOT IN con NULL.** Solicitud expresa de explicación profunda; aún no resuelta. | Tabla de verdad SQL TRUE/FALSE/UNKNOWN; evaluar NOT IN fila por fila; comparar NOT EXISTS, <>, IS NULL; resolver ejercicios y explicar cada resultado. | Prioridad crítica, pendiente |
| E09 | Concurrencia SQL; transacciones, aislamiento, atomicidad, anomalías y consistencia. | Ejemplos concurrentes y análisis de interleavings, bloqueos e idempotencia. | Pendiente |
| E10 | Gestión cuantitativa: PERT, CPI, SPI, BAC, EAC, TCPI, EMV, valor ganado, ruta crítica y crashing. | Glosario, fórmulas, unidades y problemas progresivos, incluyendo múltiples rutas críticas. | Pendiente |
| E11 | Calidad: MC/DC, cobertura de sentencias/ramas, disponibilidad SLA y pruebas concurrentes. | Diseñar conjuntos de pruebas MC/DC, calcular disponibilidad/indisponibilidad y probar idempotencia bajo concurrencia. | Pendiente |
| E12 | Metodologías: Kanban, Ley de Little, WIP, throughput, cycle/lead time, TDD, story points, Scrum/XP y espiral. | Comparaciones por escenario y ejercicios numéricos. | Pendiente |
| E13 | Programación: paradigmas, polimorfismo, closures, reduce, Liskov, DIP y semántica Java/C#/JavaScript. | Trazar fragmentos de código, parámetros, referencias/copias, división entera, const, struct/class y checked. | Pendiente |
| E14 | Plataformas y herramientas: PWA, RTOS, OTA, source maps, trazas, perfiladores y analizadores estáticos. | Definiciones funcionales y selección de herramienta según escenario. | Pendiente |
| E15 | Arquitectura: UML, ATAM, MoSCoW, capas, CQRS y bases distribuidas. | Diagramas, trade-offs, patrones de consulta/actualización y fragmentación/replicación. | Pendiente |
| E16 | Ortografía: bloque 18, Q10 prevee frente a prevé; aun/aún y preguntas indirectas acertadas por adivinación. | Conjugación de prever, tildes diacríticas e interrogativos indirectos en contexto. | Pendiente |
| E17 | Puntuación: el usuario declara no distinguir dos puntos y punto y coma, aunque acertó el reactivo 9 del bloque 19. | Contrastar introducción de enumeraciones/explicaciones con separación de oraciones y listas complejas. | Pendiente |
| E18 | Concordancia y correferencia: respuestas correctas con duda en bloque 18, preguntas 3–4; bloque 19, pregunta 5. | Identificar núcleo del sujeto, sujetos compuestos y antecedentes coordinados. | Refuerzo preventivo |

Los aciertos por adivinación y los aciertos con dudas persistentes no cierran estos pendientes. Revalidar con casos nuevos antes de cambiar su estado.
