# Respuestas — Ejercitario Unidad 02

## Tema 1 · Propiedades de los sistemas

**1. Define en tus propias palabras qué es un sistema y da un ejemplo distinto al utilizado en clase.**

_Respuesta:_ Un sistema es un conjunto de elementos relacionados entre sí que trabajan de forma organizada para cumplir un objetivo común. Ejemplo: un hospital, donde médicos, enfermeros, equipos, historias clínicas y procedimientos funcionan juntos para atender la salud de los pacientes.

**2. Enumera los seis elementos de un sistema basado en computadora.**

_Respuesta:_ Software, hardware, personas, bases de datos, documentación y procedimientos.

**3. Piensa en un sistema cotidiano (por ejemplo, una biblioteca, un supermercado o un club deportivo) y completa la tabla con un ejemplo propio para cada propiedad.**

Sistema elegido: biblioteca.

| Propiedad | Ejemplo en el sistema elegido |
|---|---|
| Jerarquía | La biblioteca se divide en subsistemas (préstamos, catálogo, adquisiciones), y cada uno se organiza en niveles: director, encargados de área y auxiliares. |
| Límites (fronteras) | El sistema abarca los libros, el personal, los socios registrados y el catálogo; fuera de él quedan las editoriales, otras bibliotecas y los organismos que la financian. |
| Interrelación de elementos | El catálogo informa qué libros hay, el sistema de préstamos registra quién los tiene y el personal controla las devoluciones; si uno falla, se afectan los demás. |
| Propiedades emergentes | El servicio de calidad que recibe el lector y el conocimiento accesible para la comunidad surgen de la interacción de todos los elementos, no de uno solo. |

**4. Dentro del mismo sistema, identifica un posible subsistema y justifica por qué lo consideras tal.**

_Respuesta:_ El subsistema de préstamos. Es un sistema más pequeño dentro de la biblioteca, con sus propios elementos (registro de socios, fichas de préstamo, fechas de devolución, personal de mostrador), una función específica (controlar la entrega y devolución de libros) e interacciones con el resto, como el catálogo.

---

## Tema 2 · Los sistemas y su entorno

**5. Elige un sistema de software que uses habitualmente e identifica: una entrada, una salida y un elemento de su entorno.**

| Elemento | Descripción en el sistema elegido |
|---|---|
| Sistema elegido | Aplicación de banca móvil |
| Una entrada | Los datos que ingresa el usuario para hacer una transferencia (cuenta destino, monto y clave). |
| Una salida | El comprobante de la transferencia y la actualización del saldo. |
| Un elemento del entorno | El banco central o la red de pagos interbancaria, que el sistema no controla pero con la que debe interactuar. |

**6. ¿El sistema que elegiste es abierto o cerrado? Justifica tu respuesta.**

_Respuesta:_ Es un sistema abierto, porque intercambia información constantemente con su entorno: recibe datos de los usuarios, se comunica con otros bancos y redes de pago, y debe adaptarse a cambios externos como nuevas normativas o actualizaciones del sistema operativo del celular.

**7. Explica con tus palabras qué es la retroalimentación (feedback) en un sistema y da un ejemplo.**

_Respuesta:_ La retroalimentación es el proceso en el que parte de la salida del sistema vuelve como entrada para controlarlo o corregirlo. Ejemplo: en la app bancaria, si el usuario ingresa mal la clave, el sistema muestra un mensaje de error y le permite corregirla; además, el saldo actualizado tras cada operación sirve de base para validar la siguiente.

**8. Para el mismo sistema, menciona una restricción externa real que podría afectarlo, indicando si es organizacional, regulatoria o tecnológica.**

_Respuesta:_ Restricción regulatoria: las normas del banco central sobre seguridad y protección de datos exigen autenticación reforzada y registro de las operaciones, lo que limita cómo se puede diseñar el sistema.

---

## Tema 3 · Modelado de sistemas

**9. Menciona dos razones por las cuales es útil modelar un sistema antes de construirlo.**

_Respuesta:_ (1) Permite entender y comunicar el sistema entre analistas, clientes y desarrolladores, y detectar errores o requisitos mal entendidos antes de escribir código. (2) Reduce costos y riesgos, ya que corregir un problema en el modelo es mucho más barato que corregirlo en el sistema ya construido.

**10. Ejercicio de relación**

| Nivel de visión | Descripción |
|---|---|
| A. Visión del mundo (worldview) | **3** |
| B. Visión del dominio | **4** |
| C. Visión del elemento | **1** |
| D. Visión detallada | **2** |

**11. Explica la diferencia entre vista estructural y vista de comportamiento, y da un ejemplo de notación para cada una.**

_Respuesta:_ La vista estructural describe los componentes del sistema y cómo se relacionan o se organizan (qué lo compone). Ejemplo de notación: diagrama de clases UML o diagrama entidad-relación. La vista de comportamiento describe cómo actúa el sistema a lo largo del tiempo, es decir, cómo responde a eventos y cómo cambia su estado o fluye la información. Ejemplo de notación: diagrama de estados, diagrama de secuencia o diagrama de flujo de datos.

**12. Diagrama de contexto:**

Sistema elegido: cajero automático (ATM).

```
                 Tarjeta y PIN, monto
   ┌─────────┐ ───────────────────────►  ┌───────────────────┐
   │ Cliente │                           │                   │
   │         │ ◄───────────────────────  │  SISTEMA CAJERO   │
   └─────────┘   Efectivo y comprobante  │    AUTOMÁTICO     │
                                          │                   │
   ┌─────────┐   Solicitud de validación │                   │
   │  Banco  │ ◄───────────────────────  │                   │
   │ (Core   │                           │                   │
   │ bancario)│ ───────────────────────► │                   │
   └─────────┘   Autorización y saldo    └───────────────────┘
                                                  ▲
   ┌──────────────┐   Reposición de efectivo,     │
   │ Personal de  │ ──────────────────────────────┘
   │ mantenimiento│   mantenimiento
   └──────────────┘
```

Entidades externas: Cliente, Banco (core bancario) y Personal de mantenimiento.

**13. ¿En qué situación elegirías usar simulación en lugar de un modelo estático? Da un ejemplo concreto.**

_Respuesta:_ Usaría simulación cuando necesito analizar el comportamiento del sistema a lo largo del tiempo o bajo condiciones cambiantes, algo que un modelo estático no muestra. Ejemplo: para dimensionar un sistema de atención en un banco, simularía la llegada de clientes en horas pico y observaría los tiempos de espera con distinta cantidad de cajas, antes de construir o contratar nada.

---

## Tema 4 · El proceso de Ingeniería de Sistemas

**14. Explica la diferencia entre Ingeniería de procesos de negocio e Ingeniería de producto, dando un ejemplo de cada una.**

_Respuesta:_ La Ingeniería de procesos de negocio define la arquitectura que permite a una empresa u organización cumplir sus objetivos, rediseñando sus procesos y sistemas de información. Ejemplo: rediseñar el proceso de ventas de una cadena de tiendas para integrar inventario, facturación y atención al cliente. La Ingeniería de producto se centra en crear un producto concreto que satisfaga las necesidades de un cliente, definiendo su arquitectura y sus componentes. Ejemplo: desarrollar un sistema de control para un cajero automático o una aplicación móvil de delivery.

**15. Ordena numéricamente (1 a 4) los pasos genéricos del proceso de Ingeniería de Sistemas.**

| N.º | Paso |
|---|---|
| 3 | Especificación del sistema |
| 1 | Definición de necesidades |
| 4 | Asignación de requisitos entre elementos |
| 2 | Análisis de factibilidad |

**16. Reflexión final:** ¿por qué crees que es importante que un ingeniero de software comprenda el sistema completo antes de comenzar a programar?

_Respuesta:_ Porque el software es solo una parte de un sistema mayor que incluye hardware, personas, datos y procedimientos, y su éxito depende de cómo encaja con todos ellos y con su entorno. Si el ingeniero programa sin comprender el sistema completo, puede construir algo que funciona técnicamente pero no resuelve el problema real. Esto se relaciona con la Unidad 01, donde vimos que la visión sistémica evita soluciones aisladas y que muchos fracasos históricos (la crisis del software) vinieron de requisitos mal entendidos más que de problemas técnicos. En esta unidad, herramientas como el diagrama de contexto y el análisis de factibilidad ayudan justamente a entender los límites, el entorno y las restricciones antes de escribir una sola línea de código.
