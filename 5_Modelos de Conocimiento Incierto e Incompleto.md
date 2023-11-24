## 3.5 Modelos de Conocimiento Incierto e Incompleto

### Incertidumbre

- **Definición:** Se refiere a la falta de conocimiento seguro, donde no se puede determinar a ciencia cierta la verdad de un enunciado.
- **Ejemplo:** La regla "todos los pacientes con dolor de muelas tienen caries" es incierta porque no se aplica en todos los casos.

#### Factores de Certidumbre

- **Concepto de Grado de Certeza:** Introducido en el sistema experto MYCIN, se asocia un Factor de Certeza a cada regla y evidencia.
- **Rango:** Varía entre -1 (totalmente falso) y 1 (totalmente verdadero), con 0 indicando desconocimiento.
- **Inferencia con Factores de Certeza:** Se utilizan reglas específicas para combinar estos factores durante el razonamiento.

### Métodos Bayesianos

- **Aplicación en Incertidumbre:** Utiliza probabilidades condicionales y el Teorema de Bayes para manejar incertidumbres.
- **Ejemplo:** Calculando la probabilidad de que un paciente tenga meningitis dado que presenta cuello hinchado, usando probabilidades a priori y condicionales.

### Lógica Difusa

- **Concepto:** Método de razonamiento aproximado no probabilista que extiende la lógica multivaluada.
- **Funciones de Pertenencia:** Asignan un grado de pertenencia a un conjunto para representar la similitud de un evento con respecto a otro.
- **Sistemas Basados en Lógica Difusa:** Utilizan inferencia de Mamdani, que incluye fuzzificación, evaluación de reglas, agregación y defuzzificación.
- **Ejemplos:** Comparación entre elegir líquidos potables basándose en etiquetas difusas o probabilísticas y representación de conjuntos difusos.
