## 3.4 Modelos de Llenado de Ranuras

**Concepto:** Esquemas de representación estructurada de conocimiento donde las ranuras o slots representan atributos de los objetos del dominio de discurso, y cada ranura se rellena con un valor para el atributo.

### 3.4.1 Redes Semánticas y Marcos

#### Marcos (Frames)

- **Propuestos por:** Marvin Minsky en la década de los 70.
- **Descripción:** Una forma de representación estructurada de conocimiento que muestra entidades con sus atributos y las relaciones entre ellos, formando una red de marcos.
- **Ejemplo de Marco:** Representaciones como Perro: Canis familiaris, que ladra, y es una instancia de animal, el cual respira.
- **Implementación en PROLOG:** Se muestra cómo implementar una red de marcos en PROLOG, utilizando predicados con parámetros que incluyen el nombre del marco, su relación con otro marco y las propiedades en una lista.

#### Redes Semánticas

- **Descripción:** Esquema de representación de conocimiento mediante un grafo, donde los nodos representan conceptos y los arcos relaciones semánticas entre los conceptos, como hiperonimia, hiponimia, meronimia, sinonimia, antonimia, etc.
- **Implementación en PROLOG:** Uso de tripletas para representar propiedades de objetos y predicados binarios para las relaciones entre ellos.

### 3.4.2 Dependencia Conceptual y Guiones

#### Dependencia Conceptual

- **Propuestos por:** Roger Schank.
- **Descripción:** Modelos que se refieren a la comprensión del lenguaje natural, basados en primitivas léxicas que representan cualquier concepto verbal.
- **Categorías Conceptuales:** Incluyen objeto físico (PP), acción (ACT), atributo de un objeto (PA), atributo de una acción (AA), tiempo (T) y localización (L).

#### Guiones

- **Descripción:** Describen de forma genérica el conocimiento procedimental en secuencias de escenas o eventos que describen el devenir esperado de los acontecimientos en una situación determinada.
- **Componentes:** Incluyen condiciones de entrada, resultados, objetos, roles y escenas.
