# 4-evaluacion-traductor

### Mi repositorio: https://github.com/AnaGarciaDelAlamo/4-evaluacion-traductor.git

En esta parte se evalúa el rendimiento del traductor Alemán-Inglés. 
Se cargan y preparan los tokenizadores para los textos de alemán e inglés.
Las secuencias de frases en alemán, se codifican y se rellenan para garantizar que tengan la misma longitud antes de ser usadas como entrada para el modelo.
Se usa el modelo entrenado para generar predicciones de frases traducidas, convirtiendo las secuencias de entrada en frases de salida en inglés.
La calidad de las traducciones se mide usando BLEU, que compara las frases traducidas con las originales. Se calculan y muestran las puntuaciones BLEU-1, BLEU-2, BLEU-3 y BLEU-4, que evalúan la precisión de las traducciones con diferentes niveles de n-gramas.
