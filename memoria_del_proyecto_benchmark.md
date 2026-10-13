# CONTEXTO DEL PROYECTO: "RecetApp"

**Materia:** Taller UX, Accesibilidad e Inteligencia Artificial (UTN.BA)
**Objetivo del Proyecto:** Diseñar la experiencia completa de una aplicación ("RecetApp") que resuelva el recorrido desde "no sé qué cocinar con lo que tengo en casa" hasta "ya tengo mi lista de compras de lo que me falta", asegurando que sea simple, útil y accesible.

# TAREA ACTUAL: Benchmark de Aplicaciones

**Objetivo de la tarea:** Analizar y comparar 3 aplicaciones de recetas de cocina para identificar buenas prácticas, fricciones/problemas y patrones de UX, con el fin de obtener insights aplicables al diseño de "RecetApp".

**Aplicaciones seleccionadas para el análisis principal:**

1. **Supercook:** Enfocada en la búsqueda exacta por ingredientes disponibles (ideal para evaluar flexibilidad).

2. **Cookpad:** App sencilla enfocada en que los usuarios puedan compartir sus recetas y decidir cuál seguir. Tiene un catálogo muy amplio gracias a su comunidad activa (ideal para evaluar calidad de las propuestas y el alcance/cobertura regional).

3. **Gronda:** App orientada a chefs y entusiastas con recetas de alta calidad visual y técnicas culinarias. (Aporta un enfoque relevante: ideal para evaluar la interfaz de usuario, calidad de las propuestas y un modelo de negocio de suscripción fuertemente establecido).

*(Nota: Como referencia y contexto general del mercado, también se cuenta con análisis preliminares de competidores indirectos como Pedidos Ya, Nestlé Cocina y MyFitnessPal).*

# ESTRUCTURA DE TRABAJO Y ARCHIVOS

El espacio de trabajo local estará organizado de la siguiente manera para recolectar la información antes de maquetar:

* Se creará **una carpeta por cada aplicación** analizada (ej: `/supercook`, `/cookpad`, `/gronda`).

* **Dentro de cada carpeta** se alojarán:

  1. **Capturas de pantalla (Screenshots):** Evidencia visual de los flujos, pantallas de carga, errores, interfaces, etc.

  2. **Un archivo `.txt` (ej: `anotaciones.txt`):** Donde se irán volcando en crudo las observaciones directas del uso de la app, cantidad de clics, textos literales de la UI y problemas detectados.

# RESULTADO FINAL ESPERADO

El objetivo técnico de este benchmark es construir una **Página Web (HTML/CSS)** que consolide toda la información recopilada. Esta página web deberá contener:

1. **Tabla comparativa:** Evaluando todos los criterios exigidos para las 3 apps.

2. **Screenshots:** Integrados en el diseño para facilitar la comprensión de las observaciones.

3. **Análisis cualitativo:** Destacando buenas prácticas detectadas y problemas/fricciones.

4. **Conclusiones generales:** Respondiendo qué hacen bien la mayoría de las apps y qué oportunidades de mejora existen para "RecetApp".

# REGLAS ESTRICTAS PARA EL ANÁLISIS Y LA REDACCIÓN

Al momento de procesar los `.txt` para pasarlos al HTML final, **Copilot debe respetar estrictamente las siguientes pautas de la cátedra:**

1. **Cero Subjetividad:** ESTÁ PROHIBIDO usar palabras subjetivas como "bueno", "malo", "lindo" o "feo".

2. **Datos Cuantitativos y Hechos:** Se deben usar métricas concretas y descripciones literales (ej: "Requiere 4 taps para buscar", "La pantalla de carga dura 5 segundos", "El botón dice literalmente 'Comprar ahora'").

3. **Perspectiva del Usuario:** Analizar desde el punto de vista de un usuario real intentando completar la tarea (flujo principal).

4. **Criterios de Evaluación Obligatorios para la Tabla:**

   * **Funcionalidades:** Qué permite hacer concretamente.

   * **Flexibilidad:** Cómo se adapta si faltan ingredientes, presupuesto o conocimientos.

   * **Claridad del flujo principal:** Número de pasos y qué tan intuitiva es la tarea central.

   * **Lenguaje:** Claridad de los textos y tono.

   * **Calidad de las propuestas:** Coherencia y variedad de las recetas.

   * **Cómo llega el usuario:** Facilidad de descubrimiento (App store, web, etc.).

   * **Interfaz de Usuario (UI):** Claridad, navegación, consistencia.

   * **Estados del sistema:** Tiempos de espera (loaders, skeletons) y notificaciones de éxito/error.

   * **Accesibilidad:** Uso por personas mayores, contrastes, lenguaje sencillo.

   * **Modelo de negocio:** Freemium, pago, publicidad, etc.

   * **Cobertura y alcance:** Localización de ingredientes, métricas (gramos/tazas), etc.

   * **Fortalezas y Debilidades.**

5. **Detección de Inconsistencias y Validación Proactiva (Rol de Copilot):**
   * El usuario volcará sus anotaciones y observaciones en crudo en los archivos `anotaciones.txt` y subirá capturas a la carpeta `screenshots/`.
   * Copilot se encargará de estructurar la información, eliminar subjetividades y formalizar el análisis técnico.
   * **Regla estricta:** Si Copilot detecta vacíos de información, contradicciones, inconsistencias entre las capturas y los textos, o necesita cuantificar métricas específicas (precios exactos, textos literales de botones, conteo de taps), **DEBE frenar y hacerle preguntas puntuales al usuario** antes de asumir datos o pasarlos a la tabla comparativa final.