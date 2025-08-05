# ✈️ Airline Loyalty

Este proyecto tiene como objetivo demostrar mi capacidad para limpiar, analizar y visualizar datos reales del sector aéreo y de fidelización de clientes.

A través del análisis de datos históricos de vuelos y perfiles de clientes, busqué identificar patrones de comportamiento, relaciones relevantes entre variables y oportunidades de segmentación de clientes dentro del programa de lealtad de una aerolínea.


## 📊 Objetivos del análisis

- Unir dos datasets complejos y con distintos niveles de granularidad.
- Tratar valores nulos, inconsistencias y conversiones necesarias para preparar los datos.
- Aplicar visualizaciones claras y efectivas para responder preguntas de negocio reales.
- Extraer insights accionables que permitan comprender el comportamiento de los clientes.

---

## 🔧 Proceso de trabajo

### 1. Exploración y limpieza de datos
- Realicé una exploración inicial con `pandas` para entender la estructura y calidad del dataset.
- Traté valores nulos.
- Hice limpieza de algunos valores que podian arrojar datos erroneos.
- Cambie el tipo de dato de algunas columnas.
- Imputé datos ausentes de forma lógica, como el salario promedio estimado para las personas de nivel educativo College.
- Uní correctamente los datasets usando `Loyalty Number` como clave.

### 2. Visualización y análisis de comportamiento

Utilizando `seaborn` y `matplotlib`, construí visualizaciones para responder a preguntas clave:

- **1. ¿Cómo se distribuyen los vuelos reservados por mes?**  
  → Scatterplot para entender estacionalidad.

- **2. ¿Existe relación entre distancia volada y puntos acumulados?**  
  → Scatterplot para visualizar correlación positiva.

- **3. ¿Cómo se distribuyen los clientes por provincia o estado?**  
  → Barplot para identificar concentraciones geográficas.

- **4. ¿Cómo varía el salario promedio según el nivel educativo?**  
  → Barplot para comparar y detectar tendencias salariales por formación académica.

- **5. ¿Qué proporción de clientes tiene cada tipo de tarjeta de fidelidad?**  
  → Countplot con para visualizar la segmentación del programa.

- **6. ¿Cómo se distribuyen los clientes según estado civil y género?**  
  → Countplot cruzado para analizar perfiles demográficos.

---

## 🧠 Principales insights
- Los meses donde se concentran la mayor cantidad de vuelos es Julio, Junio, Agosto y Diciembre. Los meses con menor cantidad de vuelos es Febrero y Enero. 
- La relacion entre distancia de vuelo y puntos acumulados es ascendente, mientras mayor la distancia del vuelo mas puntos acumula el cliente.
- La mayor cantidad de clientes son de Ontario y British Columbia. Donde tenemos una menor consentracion de clientes es en Prince Edward Island
- El salario promedio varía significativamente según el nivel educativo, con diferencias claras entre grupos.
- Ciertos tipos de tarjeta de fidelidad dominan el programa, lo que puede sugerir oportunidades de personalización.
- El análisis demográfico reveló desequilibrios en ciertas categorías de clientes, útiles para campañas de retención o marketing.


## 🎯 Perfil profesional

Como profesional en formación para el rol de **Data Analyst**, este proyecto demuestra mi habilidad para:

- Preparar y transformar datos reales y desordenados.
- Formular preguntas de negocio relevantes y responderlas con análisis de datos.
- Comunicar resultados de manera visual, clara y orientada a toma de decisiones.

Un saludo, Gabriela Layas. 

