# Resultado del diagnóstico inicial — 12 de noviembre de 2026

Preguntas originales realizadas en el chat, con tres opciones por pregunta; no es una prueba oficial ni validada de Ceneval.

**Resultado: 28/30 (93.3%). Tiempo de respuesta informado: 21 min 57 s**, sin incluir revisión, lectura de comentarios ni pausas. Bloques: 8:00, 7:53 y 6:04. Promedio aproximado: 44 s por pregunta; no extrapolar al examen real.

| Área | Aciertos | Seguras acertadas | Duda acertada | Adivinación acertada |
|---|---:|---:|---:|---:|
| Análisis | 5/5 | 5 | 0 | 0 |
| Diseño | 5/5 | 3 | 1 | 1 |
| Desarrollo | 4/5 | 3 | 1 | 0 |
| Gestión | 4/5 | 3 | 0 | 1 |
| Comprensión lectora | 5/5 | 4 | 1 | 0 |
| Redacción indirecta | 5/5 | 3 | 1 | 1 |

23 respuestas seguras: 22 correctas y 1 incorrecta (15). Cuatro con duda: todas correctas. Cuatro por adivinación: correctas 8, 19 y 30; incorrecta 17.

## Respuestas y confianza

| Nº | Tema | Respuesta | Correcta | Confianza | Resultado |
|---|---|---|---|---|---|
| 1 | Rendimiento | B | B | Seguro | Acierto |
| 2 | Observación | A | A | Seguro | Acierto |
| 3 | Conflictos de requerimientos | C | C | Seguro | Acierto |
| 4 | Verificabilidad | B | B | Seguro | Acierto |
| 5 | Trazabilidad | A | A | Seguro | Acierto |
| 6 | Separación por capas | C | C | Seguro | Acierto |
| 7 | Cohesión | B | B | Duda | Acierto |
| 8 | Strategy | A | A | Adivinando | Acierto |
| 9 | Detalle de pedido | C | C | Seguro | Acierto |
| 10 | Validación de interfaz | B | B | Seguro | Acierto |
| 11 | Lectura de código | B | B | Seguro | Acierto |
| 12 | Función pura | C | C | Seguro | Acierto |
| 13 | LEFT JOIN y COUNT | A | A | Seguro | Acierto |
| 14 | Atomicidad | B | B | Duda | Acierto |
| 15 | Valores límite | A | C | Seguro | Error |
| 16 | Ruta crítica | A | A | Seguro | Acierto |
| 17 | Valor monetario esperado | A | B | Adivinando | Error |
| 18 | Scrum | C | C | Seguro | Acierto |
| 19 | Métricas de defectos | A | A | Adivinando | Acierto |
| 20 | Prueba de concepto | B | B | Seguro | Acierto |
| 21 | Idea central | B | B | Duda | Acierto |
| 22 | Representatividad | C | C | Seguro | Acierto |
| 23 | Alcance de conclusiones | A | A | Seguro | Acierto |
| 24 | Interpretación literaria | B | B | Seguro | Acierto |
| 25 | Condiciones de convocatoria | C | C | Seguro | Acierto |
| 26 | Registro formal | A | A | Seguro | Acierto |
| 27 | Concordancia | C | C | Duda | Acierto |
| 28 | Conector adversativo | B | B | Seguro | Acierto |
| 29 | Puntuación | A | A | Seguro | Acierto |
| 30 | Acentuación diacrítica | C | C | Adivinando | Acierto |

## Explicaciones

1. **B — Rendimiento:** El tiempo de respuesta bajo una carga definida es una condición de calidad de rendimiento, no una función ni una elección tecnológica.

2. **A — Observación:** La observación permite descubrir actividades tácitas que no aparecen en el manual; consultar sólo al gerente o repetir el manual no las revela.

3. **C — Conflictos de requerimientos:** Las condiciones entran en conflicto entre pago y envío. Se necesita acordar una regla con los interesados antes de implementarla.

4. **B — Verificabilidad:** Fácil de usar no establece un criterio verificable. No depende exclusivamente del código ni impone una metodología.

5. **A — Trazabilidad:** La trazabilidad relaciona requerimientos con diseño y pruebas para analizar impacto; organigrama y glosario tienen otros objetivos.

6. **C — Separación por capas:** Separar presentación, negocio y persistencia con interfaces reduce dependencias. Duplicar reglas o incrustar SQL dificulta los cambios.

7. **B — Cohesión:** Cohesión mide la relación entre responsabilidades de un componente; no describe replicación ni concurrencia.

8. **A — Strategy:** Strategy encapsula algoritmos intercambiables. Singleton trata instancias y Observer notificaciones.

9. **C — Detalle de pedido:** DetallePedido resuelve la relación muchos a muchos y conserva cantidad y precio de cada venta; las otras opciones pierden estructura o historial.

10. **B — Validación de interfaz:** Formato visible y validación localizada facilitan corregir la entrada. Borrar campos o mostrar una excepción técnica empeora la interacción.

11. **B — Lectura de código:** Sólo 5 y 4 superan 3; su suma es 9. 14 suma todos y 5 omite el último valor válido.

12. **C — Función pura:** Crear una lista nueva con impuesto recibido evita modificar el argumento y depender de estado global.

13. **A — LEFT JOIN y COUNT:** LEFT JOIN conserva a Eva y COUNT(p.id) cuenta cero pedidos para ella: Ana 2, Luis 1, Eva 0. INNER JOIN excluye a Eva y COUNT(*) cuenta su fila extendida con NULL como una.

14. **B — Atomicidad:** La atomicidad de una transacción permite confirmar ambas operaciones o revertirlas. Replicación e índices no sustituyen esa garantía.

15. **C — Valores límite:** Para [18,65], probar 17,18,19 y 64,65,66 verifica límites y vecinos. Los valores interiores de A no verifican las fronteras.

16. **A — Ruta crítica:** A termina en 3; B en 7; C en 5; D espera ambas y termina en 9. Las rutas son 9 y 7; 11 suma tareas que pueden ir en paralelo.

17. **B — Valor monetario esperado:** 0.25 × 40,000 = 10,000 MXN. 40,000 es el impacto si ocurre, no el promedio ponderado; 160,000 no es probabilidad por impacto.

18. **C — Scrum:** Product Owner y Developers pueden revisar prioridad y negociar alcance sin poner en peligro el objetivo del sprint. No se debe imponer carga inviable ni prohibir todo cambio del proyecto.

19. **A — Métricas de defectos:** La tasa de defectos en producción normalizada por tamaño y comparada entre periodos aporta evidencia del resultado; contar reuniones o cuentas no mide defectos escapados. Por sí sola no prueba causalidad.

20. **B — Prueba de concepto:** Una prueba de concepto mínima prueba la compatibilidad desconocida; diseño visual y suposiciones no resuelven la incertidumbre técnica.

21. **B — Idea central:** El texto combina aumento de uso y decisión provisional pendiente de información. No afirma apoyo unánime ni cancelación.

22. **C — Representatividad:** 60 de 400 respuestas pueden no representar a todos. El texto no dice que sólo respondieran visitantes nocturnos ni invalida todas las encuestas.

23. **A — Alcance de conclusiones:** Más visitas no demuestra rentabilidad sin costos. No hay datos sobre notas académicas ni puede interpretarse falta de respuesta como desacuerdo.

24. **B — Interpretación literaria:** El piano y la partitura del padre sustentan una despedida personal. No hay indicios de enseñanza a trabajadores ni de propiedad ajena.

25. **C — Condiciones de convocatoria:** Dos integrantes inscritos, PDF y envío a las 17:30 cumplen todas las condiciones. Cinco integrantes exceden el máximo y 18:30 es extemporáneo.

26. **A — Registro formal:** El registro formal y la justificación explícita son adecuados para un comité; las otras expresiones son coloquiales.

27. **C — Concordancia:** Observaciones y fueron atendidas concuerdan en plural. En A documentación exige fue revisada y en B resultados exige muestran.

28. **B — Conector adversativo:** Sin embargo introduce contraste entre éxito funcional y problemas de rendimiento; no es consecuencia ni ejemplo.

29. **A — Puntuación:** La coma delimita la subordinada inicial completa sin separar el sujeto del verbo. B interrumpe publicar la actualización y C separa equipo de debe.

30. **C — Acentuación diacrítica:** Sé lleva tilde por ser forma de saber; si es conjunción sin tilde, el es artículo y tu posesivo. Tú y él con tilde serían pronombres.

## Interpretación y ajustes

Buen resultado en estos ejercicios iniciales, con distractores en ocasiones fáciles de descartar. Sólo cinco preguntas por área y un reactivo específico de acentuación no permiten determinar dominio completo ni predecir Satisfactorio o Sobresaliente. Falta evaluar casos de mayor dificultad, diagramas, paradigmas lógico/funcional, estándares, consultas complejas y textos más largos.

Prioridades: (1) acentuación, debilidad declarada por el usuario y respuesta 30 adivinada; validar con más reactivos; (2) valores límite, error con seguridad; (3) valor monetario esperado, error por adivinación. Refuerzo adicional: cohesión, Strategy, atomicidad, métricas de calidad, comprensión global y concordancia.

Próxima sesión de hasta 120 minutos: 15 de recuperación; 25 de acentuación; 20 de valores límite; 15 de riesgos; 30 de ejercicios nuevos; 15 de corrección y registro. Mantener cobertura del temario restante. Repetir los temas débiles con casos nuevos al día siguiente, tres días después y una semana después.


## Aclaración posterior del usuario

Sobre la pregunta 15, indica que conocía los valores límite y pudo confundirse al escribir la opción. Se conserva A como respuesta registrada y 28/30 como resultado bruto, sin concluir que desconoce el tema. Comprobar con un ejercicio nuevo antes de priorizarlo como debilidad. Confirma que la 17 fue adivinada.

El usuario autorizó guardar el contenido de preparación, incluyendo resultados y seguimiento, en este repositorio público tras informarse de su visibilidad. Las preguntas fueron introductorias: ampliar dificultad y contrastar con ejemplos oficiales antes de extraer conclusiones de dominio.
