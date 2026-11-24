# Respuestas — Ejercitario Unidad 04

## Tema 1 · El proceso de requerimientos

**1. Define en tus propias palabras qué es la ingeniería de requerimientos.**

_Respuesta:_ La ingeniería de requerimientos es el proceso de descubrir, analizar, documentar, validar y mantener las necesidades y restricciones que debe cumplir un sistema, es decir, lo que los usuarios y el negocio esperan de él. Su objetivo es que todos los involucrados tengan una comprensión clara y compartida de qué se va a construir antes de diseñarlo y programarlo.

**2. Explica la diferencia entre "requerimiento", "especificación de requisitos" e "ingeniería de requisitos", con un ejemplo de cada uno.**

_Respuesta:_ El **requerimiento** es una necesidad, condición o capacidad que el sistema debe cumplir. Ejemplo: "El sistema debe permitir registrar a un cliente nuevo". La **especificación de requisitos** es el documento donde se describen de forma organizada y detallada todos los requerimientos del sistema. Ejemplo: el documento de especificación de requisitos de software (ERS) de un sistema de farmacia. La **ingeniería de requisitos** es el proceso completo de obtener, analizar, especificar, validar y gestionar los requerimientos. Ejemplo: realizar entrevistas con el personal, redactar la especificación, revisarla con el cliente y controlar sus cambios durante el proyecto.

---

## Tema 2 · Tipos de requerimientos

**3. Ejercicio de relación**

| Tipo de requerimiento | Descripción |
|---|---|
| A. Funcional | **2** |
| B. No funcional | **3** |
| C. Del dominio | **1** |

**4. Completen el siguiente cuadro comparando los requerimientos de usuario y los requerimientos de sistema.**

| Aspecto | Requerimientos de usuario | Requerimientos de sistema |
|---|---|---|
| Audiencia principal | Clientes, usuarios finales y gerentes, que no necesariamente son técnicos. | Desarrolladores, analistas, arquitectos y testers, que construirán y probarán el sistema. |
| Nivel de detalle | Abstracto y general: describe qué servicios espera el usuario y las restricciones principales. | Detallado y preciso: describe con exactitud las funciones, entradas, salidas, restricciones y comportamiento del sistema. |
| Lenguaje utilizado | Lenguaje natural, con tablas y diagramas simples, sin tecnicismos. | Lenguaje natural estructurado, notaciones gráficas (UML), plantillas o modelos más técnicos. |

**5. Elegí un sistema que conozcas y da un ejemplo propio de un requerimiento funcional y uno no funcional para ese mismo sistema.**

_Respuesta:_ Sistema elegido: aplicación de banca móvil.
- **Requerimiento funcional:** el sistema debe permitir al usuario realizar transferencias entre cuentas ingresando la cuenta destino y el monto.
- **Requerimiento no funcional:** el sistema debe procesar cada transferencia en menos de 3 segundos y exigir autenticación de dos factores para cada operación.

---

## Tema 3 · Características de los requerimientos

**6. Completen el siguiente cuadro indicando qué pregunta permite verificar cada característica de un buen requerimiento.**

| Característica | Pregunta que permite verificarla |
|---|---|
| Correcto | ¿Refleja realmente una necesidad válida del usuario o del negocio, y está libre de errores? |
| No ambiguo | ¿Puede interpretarse de una sola manera por cualquier persona que lo lea? |
| Completo | ¿Incluye toda la información necesaria (entradas, salidas, condiciones, excepciones) para poder implementarlo sin suposiciones? |
| Verificable | ¿Se puede comprobar mediante una prueba, medición o inspección que el sistema lo cumple? |

**7. Tomá el requerimiento "El sistema debe ser rápido" y reescribilo de forma que cumpla con las características de un buen requerimiento vistas en clase.**

_Respuesta:_ "El sistema deberá responder a cualquier consulta de búsqueda de productos en un tiempo máximo de 2 segundos, en el 95 % de los casos, con hasta 500 usuarios conectados simultáneamente." Este requerimiento es no ambiguo (indica un tiempo concreto), verificable (se puede medir con pruebas de carga), completo (define condiciones de carga y porcentaje) y correcto (puede validarse con el cliente).

---

## Tema 4 · Obtención y análisis de requerimientos

**8. Enumera las cuatro etapas del ciclo de obtención y análisis de requerimientos vistas en clase.**

_Respuesta:_ 1) Descubrimiento de requerimientos (obtención). 2) Clasificación y organización de requerimientos. 3) Priorización y negociación de requerimientos. 4) Especificación (documentación) de requerimientos.

**9. Ejercicio de relación**

| Técnica de obtención | Situación en que conviene usarla |
|---|---|
| A. Entrevistas | **3** |
| B. Observación | **1** |
| C. Talleres / workshops | **2** |

---

## Tema 5 · Técnicas de especificación de requerimientos

**10. Completen el siguiente cuadro indicando una ventaja y una limitación de cada técnica de especificación de requerimientos.**

| Técnica | Ventaja | Limitación |
|---|---|---|
| Lenguaje natural estructurado | Es fácil de entender para cualquier persona y mantiene un formato uniforme gracias a plantillas. | Aún puede generar ambigüedades y es difícil de verificar automáticamente. |
| Casos de uso | Muestran cómo interactúan los usuarios con el sistema, lo que facilita entender los escenarios de uso. | No describen bien los requerimientos no funcionales ni los detalles internos del sistema. |
| Historias de usuario | Son breves, fáciles de escribir y de priorizar, y favorecen la comunicación con el cliente en metodologías ágiles. | Son poco detalladas y pueden quedar incompletas o sin documentación formal si no se complementan. |
| Diagramas (UML) | Representan visualmente el sistema y sus relaciones, lo que reduce malentendidos. | Requieren conocer la notación y pueden resultar difíciles de entender para usuarios no técnicos. |

---

## Tema 6 · Especificaciones formales

**11. ¿Qué es una especificación formal y en qué tipo de sistemas se justifica su uso? Da un ejemplo hipotético de un sistema donde la usarías.**

_Respuesta:_ Una especificación formal es una descripción de los requerimientos escrita con un lenguaje de base matemática (por ejemplo Z, B o VDM), con sintaxis y semántica precisas, que elimina ambigüedades y permite demostrar y verificar propiedades del sistema. Su uso se justifica en sistemas críticos, donde un fallo puede causar pérdidas de vidas, daños graves o grandes pérdidas económicas (sistemas de seguridad, médicos, aeronáuticos o financieros), porque su costo y complejidad son altos. Ejemplo hipotético: el software de control de una bomba de infusión de medicamentos en un hospital, donde un error en la dosis podría poner en riesgo la vida del paciente.

---

## Tema 7 · Prototipado de los requerimientos

**12. Explica la diferencia entre un prototipo desechable y un prototipo evolutivo, con un ejemplo de un proyecto donde usarías cada uno.**

_Respuesta:_ El **prototipo desechable** se construye rápidamente para aclarar y validar requerimientos poco claros, y luego se descarta; el sistema final se desarrolla desde cero con mejor calidad. Ejemplo: en un sistema de gestión para un taller mecánico, haría maquetas rápidas de las pantallas para que el cliente confirme qué datos quiere ver, y luego las descartaría. El **prototipo evolutivo** se construye con calidad suficiente para ir mejorándose y refinándose hasta convertirse en el sistema final. Ejemplo: una aplicación web de delivery cuyos requerimientos cambian con frecuencia, donde se va entregando una versión funcional que se amplía con cada retroalimentación de los usuarios.

---

## Tema 8 · Técnicas de construcción rápida

**13. Menciona dos técnicas de construcción rápida de prototipos vistas en clase y explica brevemente en qué consiste cada una.**

_Respuesta:_ 1) **Programación en lenguajes de muy alto nivel o de cuarta generación (4GL):** se usan lenguajes y herramientas que permiten crear funcionalidad con poco código, lo que acelera la construcción del prototipo. 2) **Prototipado de interfaces con herramientas visuales o generadores de pantallas:** se diseñan rápidamente las pantallas y la navegación con herramientas gráficas (por ejemplo Figma o similares) para simular la interacción del usuario sin implementar la lógica completa. Otras técnicas comunes son la reutilización de componentes existentes y la programación con bases de datos y hojas de cálculo.

---

## Tema 9 · Validación de requerimientos

**14. Completen el siguiente cuadro relacionando cada técnica de validación con el tipo de problema que detecta mejor.**

| Técnica de validación | Qué tipo de problema detecta mejor |
|---|---|
| Revisiones de requisitos | Inconsistencias, ambigüedades, omisiones y errores de redacción o de lógica en el documento de requisitos. |
| Prototipado | Requerimientos mal entendidos o que no reflejan lo que el usuario realmente necesita, especialmente en la interfaz y el flujo de uso. |
| Generación de casos de prueba | Requerimientos que no son verificables o que están incompletos, ya que si no se puede diseñar una prueba para ellos, probablemente estén mal definidos. |

---

## Tema 10 · Administración de requerimientos

**15. Explica con tus palabras qué es la trazabilidad de requerimientos y por qué es importante en un proyecto real.**

_Respuesta:_ La trazabilidad de requerimientos es la capacidad de seguir el recorrido de cada requerimiento, desde su origen (quién lo pidió y por qué) hasta su diseño, su implementación y sus pruebas, y viceversa. Es importante porque permite saber qué partes del sistema se ven afectadas cuando un requerimiento cambia, comprobar que todos los requerimientos fueron implementados y probados, y justificar cada elemento del sistema. Así se controlan mejor los cambios, se reduce el riesgo de errores y se facilita el mantenimiento.

---

## Tema 11 · Medición de requerimientos

**16. Menciona dos métricas que se pueden aplicar a los requerimientos de un proyecto y qué información le aporta cada una al equipo.**

_Respuesta:_ 1) **Volatilidad de requerimientos (cantidad de cambios por periodo):** indica qué tan estables son los requerimientos y permite anticipar riesgos de retrasos y sobrecostos si cambian demasiado. 2) **Porcentaje de requerimientos implementados o verificados:** muestra el avance real del proyecto y cuántos requerimientos ya fueron construidos y probados. También pueden usarse el número total de requerimientos o la cantidad de requerimientos ambiguos detectados en las revisiones.

**17. Reflexión final:** pensá en un proyecto de software (hipotético o real). Describí qué técnica de obtención, qué técnica de especificación y qué técnica de validación usarías, y justificá tu elección.

_Respuesta:_ Proyecto: sistema de gestión para un taller mecánico de autos y motos.
- **Obtención:** entrevistas con el dueño y los mecánicos, complementadas con observación del trabajo diario en el taller, porque los usuarios no siempre pueden explicar con palabras cómo organizan órdenes, repuestos y clientes.
- **Especificación:** historias de usuario junto con algunos casos de uso para los flujos principales (recepción del vehículo, orden de trabajo, facturación), ya que el proyecto es pequeño, los usuarios son poco técnicos y los requerimientos pueden cambiar.
- **Validación:** prototipado de las pantallas, para que los usuarios vean y prueben el sistema antes de construirlo, complementado con una revisión de requisitos con el dueño para detectar omisiones o contradicciones.

Esta combinación es adecuada porque el proyecto es de tamaño pequeño o mediano, los usuarios no son técnicos y el contacto directo y las validaciones tempranas reducen el riesgo de construir algo que no necesitan.
