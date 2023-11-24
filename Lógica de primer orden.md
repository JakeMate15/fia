## 3.2 Lógica de Primer Orden

### Definiciones y Conceptos

- **Lógica:** Ciencia de las leyes y formas del pensamiento que ofrece normas para la investigación científica y criterios de verdad.
- **Lógica Clásica:** Caracterizada por ser apofántica (verdadera o falsa), bivalente (dos valores de verdad) y asertórica (afirma proposiciones como verdaderas o falsas sin matices).
- **Lógicas Modales:** Sistemas lógicos que analizan distintas modalidades en los tipos de razonamiento, como la lógica alética (necesidad, posibilidad, imposibilidad, contingencia), lógicas polivalentes (valores de verdad no absolutos), y lógica modal de lo difuso (conjuntos nítidos vs. difusos).

#### Lógica Proposicional

- **Estudio:** Frases declarativas simples como base para la transmisión de conocimiento.
- **Proposición:** Enunciado calificable como verdadero o falso.
- **Alfabeto de la Lógica Proposicional:** Constantes, variables, símbolos de conectivas, y signos de puntuación.
- **Sintaxis:** Reglas para formar proposiciones válidas.
- **Tablas de Verdad:** Herramienta para determinar validez, contradicción, contingencia y satisfacibilidad de proposiciones.

#### Razonamiento en Lógica Proposicional

- **Validez:** Tautologías, contradicciones, contingencias.
- **Equivalencia Lógica:** Proposiciones con el mismo valor de verdad.
- **Consecuencia Lógica:** Relación entre premisas y conclusiones.

### 3.2.1 Lenguaje de Predicados

- **Predicado:** Afirma algo sobre el sujeto en una proposición.
- **Lenguaje de la Lógica de Primer Orden:** Permite representar propiedades y relaciones entre objetos.
- **Componentes:** Universo del discurso, esquemas de relación, esquemas de función.
- **Sintaxis:** Símbolos de constantes, predicados, funciones.
- **Sentencias Atómicas y Compuestas:** Construcción de enunciados usando conectivas lógicas.
- **Cuantificadores:** Universal (∀) y Existencial (∃).
- **Semántica:** Relación entre sentencias y modelos para determinar el valor de verdad.

### 3.2.2 Programación Lógica en PROLOG

- **PROLOG:** Lenguaje de programación basado en la Lógica de Primer Orden.
- **Hechos y Reglas:** Representación de conocimiento y lógica.
- **Gramáticas de Cláusulas Definidas (DCG):** Extensión sintáctica para implementar gramáticas formales.
- **JPL (Interfaz Java y SWI-Prolog):** Interfaz bidireccional entre Java y SWI-Prolog.

#### Ejercicios y Ejemplos

- **Ejercicios de Lógica de Primer Orden:** Representación en lógica de primer orden de situaciones y relaciones.
- **Listas en PROLOG:** Uso y manipulación de listas.
- **Mantenimiento de la Base de Conocimientos:** Uso de metapredicados como assert y retract para manipular cláusulas.

## Introducción a PROLOG

- **Definición:** PROLOG es un lenguaje de programación basado en la Lógica de Primer Orden y se utiliza para representar conocimiento mediante objetos, atributos y relaciones entre ellos, así como para inferir nuevo conocimiento.
- **Ejemplo básico:**
  - **Hecho:** `humano(socrates)` - Representa el atributo de Sócrates de ser humano.
  - **Regla:** `mortal(X):-humano(X)` - Indica que todo lo que es humano es mortal.

### Hechos y Reglas en PROLOG

- **Hechos:** Representaciones básicas de conocimiento, como `humano(socrates)` o `discipulo(platon, socrates)`.
- **Reglas:** Definiciones que establecen relaciones entre hechos. Ejemplo: `buenCandidato(X):-inteligente(X), honesto(X)` indica que un buen candidato es aquel que es inteligente y honesto.

### Gramáticas de Cláusulas Definidas (DCG)

- **Definición:** Extensión sintáctica de PROLOG para implementar gramáticas formales.
- **Ejemplo de DCG:** Representación de gramáticas simplificadas, como `oracion --> sintagma_nominal, sintagma_verbal`.

### Interfaz JPL

- **JPL:** Interfaz bidireccional entre Java y SWI-Prolog, permitiendo integraciones entre ambos entornos de programación.

### Mantenimiento de la Base de Conocimientos

- **Metapredicados:** `assert` y `retract` permiten modificar la base de conocimientos en tiempo de ejecución. Por ejemplo, `assert(nuevo_hecho)` agrega un hecho, y `retract(hecho_existente)` lo elimina.

### Ejercicios y Ejemplos en PROLOG

- **Listas:** Manipulación y acceso a elementos de listas en PROLOG, utilizando notaciones como `[H|T]` para cabeza y cola de la lista.
- **Recursividad:** Implementación de llamadas recursivas en PROLOG para operaciones complejas.
- **Ejemplos de Consultas:** Creación y ejecución de consultas para interrogar la base de conocimientos, como preguntar si un individuo es humano o mortal.
