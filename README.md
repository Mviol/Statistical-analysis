1. Description of the Data Set
- Features: The Wisconsin breast cancer dataset contains 30 features that describe properties of cell nuclei, such as:
- Radius
- Texture
- Perimeter
- Area
- Smoothness
- Compactness
- Concavity
- Number of concave points
- Symmetry
- Fractal dimension
- Classes: The target is binary, indicating whether the tumor is:
- Malignant (1)
- Benign (0)
2. Statistical analysis
2.1 Descriptive Statistics
- Mean and Standard Deviation: Descriptive statistics, such as mean and standard deviation, are calculated for each characteristic. This helps to understand the distribution of the data.
- Distribution: Analysis of the distribution of characteristics can reveal whether the data is symmetrical or has asymmetry, which can affect modeling.
2.2 Correlation Matrix
- Correlation between characteristics: The correlation matrix is an important tool for identifying relationships between characteristics.
- Values close to 1: Indicate a strong positive correlation.
- Values close to -1: Indicate a strong negative correlation.
- Values close to 0: Indicate little or no correlation.
- Interpretation: For example, if tumor area and perimeter are highly correlated, this suggests that an increase in one characteristic may be associated with an increase in the other.
3. Predictive modeling
3.1 Logistic regression
- Model: Logistic Regression is a statistical model used to predict the probability of a binary event (in this case, malignant or benign).
- Model evaluation:
- Confusion Matrix: Shows the number of true positives, true negatives, false positives and false negatives. This helps to understand the effectiveness of the model.
- Classification Report: Includes metrics such as precision, recall and F1-score:
- Precision: Proportion of true positives in relation to the total number of positives predicted.
- Recall: Proportion of true positives in relation to total actual positives.
- F1-score: Harmonic mean of precision and recall, useful for assessing the balance between the two metrics.
3.2 Evaluation results
- Precision: A high precision indicates that the model is good at predicting malignant tumors correctly.
- Recall: A high recall indicates that the model is effective at identifying the majority of malignant tumors.
- F1-score: A high F1-score suggests that the model has a good balance between precision and recall.




1. Descripción del conjunto de datos
- Características: El conjunto de datos de cáncer de mama de Wisconsin contiene 30 características que describen propiedades de los núcleos celulares, como:
- Radio
- Textura
- Perímetro
- Superficie
- Suavidad
- Compacidad
- Concavidad
- Número de puntos cóncavos
- Simetría
- Dimensión fractal
- Clases: El objetivo es binario, indicando si el tumor es
- Maligno (1)
- Benigno (0)
2. 2. Análisis estadístico
2.1 Estadística descriptiva
- Media y desviación típica: Para cada característica se calculan estadísticas descriptivas como la media y la desviación típica. Esto ayuda a comprender la distribución de los datos.
- Distribución: El análisis de la distribución de las características puede revelar si los datos son simétricos o presentan asimetría, lo que puede afectar a la modelización.
2.2 Matriz de correlaciones
- Correlación entre características: La matriz de correlación es una herramienta importante para identificar relaciones entre características.
- Valores próximos a 1: indican una fuerte correlación positiva.
- Valores próximos a -1: indican una fuerte correlación negativa.
- Valores próximos a 0: indican una correlación escasa o nula.
- Interpretación: Por ejemplo, si el área tumoral y el perímetro están muy correlacionados, esto sugiere que un aumento de una característica puede estar asociado a un aumento de la otra.
3. Modelización predictiva
3.1 Regresión logística
- Modelo: La regresión logística es un modelo estadístico utilizado para predecir la probabilidad de un evento binario (en este caso, maligno o benigno).
- Evaluación del modelo:
- Matriz de confusión: Muestra el número de verdaderos positivos, verdaderos negativos, falsos positivos y falsos negativos. Esto ayuda a comprender la eficacia del modelo.
- Informe de clasificación: incluye métricas como la precisión, la recuperación y la puntuación F1:
- Precisión: Proporción de verdaderos positivos en relación con el número total de positivos predichos.
- Recall: Proporción de positivos verdaderos en relación con el total de positivos reales.
- Puntuación F1: media armónica de precisión y recuperación, útil para evaluar el equilibrio entre ambas métricas.
3.2 Resultados de la evaluación
- Precisión: una precisión elevada indica que el modelo predice correctamente los tumores malignos.
- Recuperación: una recuperación alta indica que el modelo es eficaz a la hora de identificar la mayoría de los tumores malignos.
- Puntuación F1: una puntuación F1 elevada indica que el modelo presenta un buen equilibrio entre precisión y recuperación.




1. Descrizione del set di dati
- Caratteristiche: Il set di dati sul cancro al seno del Wisconsin contiene 30 caratteristiche che descrivono le proprietà dei nuclei cellulari, quali:
- Raggio
- Struttura
- Perimetro
- Area
- Levigatezza
- Compattezza
- Concavità
- Numero di punti concavi
- Simmetria
- Dimensione frattale
- Classi: L'obiettivo è binario, e indica se il tumore è:
- Maligno (1)
- Benigno (0)
2. Analisi statistica
2.1 Statistiche descrittive
- Media e deviazione standard: per ogni caratteristica vengono calcolate statistiche descrittive come la media e la deviazione standard. Questo aiuta a comprendere la distribuzione dei dati.
- Distribuzione: l'analisi della distribuzione delle caratteristiche può rivelare se i dati sono simmetrici o asimmetrici, il che può influire sulla modellizzazione.
2.2 Matrice di correlazione
- Correlazione tra le caratteristiche: La matrice di correlazione è uno strumento importante per identificare le relazioni tra le caratteristiche.
- Valori prossimi a 1: indicano una forte correlazione positiva.
- Valori prossimi a -1: indicano una forte correlazione negativa.
- Valori prossimi a 0: indicano una correlazione minima o nulla.
- Interpretazione: ad esempio, se l'area del tumore e il perimetro sono altamente correlati, ciò suggerisce che un aumento di una caratteristica può essere associato a un aumento dell'altra.
3. Modellazione predittiva
3.1 Regressione logistica
- Modello: la regressione logistica è un modello statistico utilizzato per prevedere la probabilità di un evento binario (in questo caso, maligno o benigno).
- Valutazione del modello:
- Matrice di confusione: mostra il numero di veri positivi, veri negativi, falsi positivi e falsi negativi. Questo aiuta a capire l'efficacia del modello.
- Rapporto di classificazione: include metriche quali precisione, richiamo e punteggio F1:
- Precisione: proporzione di veri positivi rispetto al numero totale di positivi previsti.
- Richiamo: proporzione di veri positivi rispetto al totale dei positivi effettivi.
- F1-score: media armonica di precisione e richiamo, utile per valutare l'equilibrio tra le due metriche.
3.2 Risultati della valutazione
- Precisione: una precisione elevata indica che il modello è in grado di prevedere correttamente i tumori maligni.
- Richiamo: un richiamo elevato indica che il modello è efficace nell'identificare la maggior parte dei tumori maligni.
- F1-score: un elevato F1-score indica che il modello ha un buon equilibrio tra precisione e richiamo.
