# customer-churn-classification
(Español al final)

## Business Problem 

The telecommunications company Telecom needs to determine the probability that a customer will cancel their subscription to the service portfolio currently held with the company, in order to offer promotions and special plans to users at risk of churn

## Objetives

Develop a classification model to identify customers with a high probability of churn. The model is designed to provide clear and actionable insights that help the marketing team make data-driven decisions and create effective customer retention strategies

## Technologies used

### Programming Language
- Python

### Data Analysis
- Pandas
- NumPy

### Machine Learning
- Scikit-learn
- CatBoost
- LightGBM

### Data Visualization
- Matplotlib
- Seaborn

### Development Tools
- Jupyter Notebook
- VS Code
- Git
- GitHub

## Methdology

1. Data Upload and Initial Exploration
   - Loaded the dataset and explored its structure, variables, and missing values.

2. Data Preprocessing
   - Cleaned and transformed messy data.
   - Handled null values.
   - Standardized text formatting.
   - Corrected data types.
   - Organized information into structured tables.

3. Exploratory Data Analysis (EDA)
   - Analyzed patterns, correlations, and customer behavior.
   - Created visualizations to identify trends and insights.

4. Feature engineering
  - Creation of a new variable (tenure_days) to determine customer tenure

5. Model Training and Evaluation
   - Trained multiple machine learning models.
   - Evaluated model performance using classification metrics.

6. Conclusions
   - Summarized the main findings and business insights obtained from the analysis.

 ## Key Results and Findings

- Addressed class imbalance (26% vs. 74%) using native model hyperparameters such as `scale_pos_weight` and `auto_class_weights` instead of synthetic oversampling techniques, reducing the risk of overfitting while preserving the original data distribution.

- Missing values and inconsistent data were treated during preprocessing to improve data quality and model reliability.

- Feature engineering played a critical role in model performance. In particular, the creation of the variable *Customer Tenure in Days* helped identify important churn patterns among long-term customers with high accumulated charges.

- CatBoost was selected as the best-performing model due to its superior AUC-ROC (93%) and F1-Score (78%), demonstrating strong predictive capability and balanced classification performance.

- The final model achieved a Recall of 81%, allowing the detection of approximately 8 out of 10 customers at risk of churn before cancellation, enabling proactive retention strategies.

## Strategic Business Insights

1. Identify customers with a high probability of churn in order to develop targeted retention strategies such as personalized promotions and loyalty programs.

2. Once high-risk customers are identified, analyze their level of engagement with the company, including the service packages they currently use, and evaluate opportunities to adapt products or plans according to their profile and customer needs.

3. Further analyze churn patterns to better understand the main causes of customer attrition. For example:
   - Are customers switching to competitors?
   - Is service quality influencing the probability of churn?
   - Are there specific products or services associated with higher cancellation rates?

4. From a managerial perspective, these analytical tools and recommendations can provide significant value to the marketing department when designing targeted retention campaigns and strengthening customer relationship strategies.


# Problema de Negocio

La empresa de telecomunicaciones Telecom necesita determinar la probabilidad de que un cliente cancele su suscripción al portafolio de servicios que actualmente tiene con la compañía, con el fin de ofrecer promociones y planes especiales a los usuarios con riesgo de fuga.

## Objetivos

Desarrollar un modelo de clasificación para identificar clientes con alta probabilidad de abandono. El modelo está diseñado para proporcionar información clara y accionable que ayude al equipo de marketing a tomar decisiones basadas en datos y crear estrategias efectivas de retención de clientes.

## Tecnologías Utilizadas
### Lenguaje de Programación
- Python
- Análisis de Datos
- Pandas
- NumPy
- Machine Learning
- Scikit-learn
- CatBoost
- LightGBM
- 
### Visualización de Datos
- Matplotlib
- Seaborn

### Herramientas de Desarrollo
- Jupyter Notebook
- VS Code
- Git
- GitHub
  
### Metodología 

1. Carga de Datos y Exploración Inicial
- Se cargó el conjunto de datos y se exploró su estructura, variables y valores faltantes.
2. Preprocesamiento de Datos
- Limpieza y transformación de datos inconsistentes.
3. Manejo de valores nulos.
- Estandarización del formato de texto.
4. Corrección de tipos de datos.
- Organización de la información en tablas estructuradas.
5. Análisis Exploratorio de Datos (EDA)
- Análisis de patrones, correlaciones y comportamiento de los clientes.
- Creación de visualizaciones para identificar tendencias e insights.
6. Ingeniería de Características
- Creación de una nueva variable (tenure_days) para determinar la antigüedad del cliente.
7. Entrenamiento y Evaluación del Modelo
- Entrenamiento de múltiples modelos de machine learning.
- Evaluación del desempeño utilizando métricas de clasificación.

##  Conclusiones

- Se abordó el desbalance de clases (26% vs. 74%) utilizando hiperparámetros nativos de los modelos, como scale_pos_weight y auto_class_weights, en lugar de técnicas de sobremuestreo sintético, reduciendo el riesgo de sobreajuste y preservando la distribución original de los datos.
- Los valores faltantes y los datos inconsistentes fueron tratados durante el preprocesamiento para mejorar la calidad de los datos y la confiabilidad del modelo.
- La ingeniería de características desempeñó un papel fundamental en el rendimiento del modelo. En particular, la creación de la variable Antigüedad del Cliente en Días ayudó a identificar patrones importantes de churn en clientes de larga permanencia con altos cargos acumulados.
- CatBoost fue seleccionado como el modelo con mejor desempeño debido a su superior AUC-ROC (93%) y F1-Score (78%), demostrando una fuerte capacidad predictiva y un rendimiento equilibrado en la clasificación.
- El modelo final alcanzó un Recall del 81%, permitiendo detectar aproximadamente 8 de cada 10 clientes en riesgo de abandono antes de la cancelación, facilitando estrategias de retención proactivas.
  
## Insights Estratégicos de Negocio
- Identificar clientes con alta probabilidad de abandono para desarrollar estrategias de retención dirigidas, como promociones personalizadas y programas de fidelización.
- Una vez identificados los clientes de alto riesgo, analizar su nivel de compromiso con la empresa, incluyendo los paquetes de servicios que utilizan actualmente, y evaluar oportunidades para adaptar productos o planes según su perfil y necesidades.
- Analizar con mayor profundidad los patrones de churn para comprender mejor las principales causas de abandono de clientes. Por ejemplo:
¿Los clientes están migrando hacia la competencia?
¿La calidad del servicio influye en la probabilidad de churn?
¿Existen productos o servicios específicos asociados con mayores tasas de cancelación?
- Desde una perspectiva gerencial, estas herramientas analíticas y recomendaciones pueden aportar un valor significativo al departamento de marketing en el diseño de campañas de retención dirigidas y en el fortalecimiento de las estrategias de relación con los clientes.


  
