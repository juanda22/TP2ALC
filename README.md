# TP2ALC

Segundo trabajo practico de la materia Algebra Lineal Computacional el cual trata sobre el reconocimiento automatico de dígitos manuscritos  utilizando descomposición en valores singulares (SVD), aplicada sobre imágenes de la base de datos MNIST.

El objetivo principal es implementar un sistema de clasificación de imágenes de dígitos manuscritos (del 0 al 9) utilizando:
- Técnicas de álgebra lineal, especialmente SVD (Singular Value Decomposition)
- Un conjunto de imágenes ya clasificadas (entrenamiento, mnist_train.csv)
- Un conjunto de imágenes sin clasificar (testeo, mnist_test.csv)

La SVD es una herramienta poderosa de la teoría de matrices. Permite descomponer una matriz en tres componentes:
A = UΣVᵗ, donde:
- U: contiene los autovectores de AAᵗ
- Σ: matriz diagonal con valores singulares (raíz de los autovalores de AᵗA)
- V: contiene los autovectores de AᵗA
Esta descomposición permite extraer características importantes (modos principales) de las imágenes para reducir la dimensionalidad y mejorar la clasificación.

Los archivos .csv no se adjuntaron ya que son demasiado grandes. 
