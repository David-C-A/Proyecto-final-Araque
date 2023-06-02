## **Resumen del proyecto**

**Objetivo**
Predecir el nivel de ingles que obtendrá un estudiante en el examen Saber pro a partir de diferentes características (Si estudia virtual o presencial, si es de una institución oficial o no, si tiene acceso a un computador en su casa, etc)

**Datos utilizados**
Resultados individuales en las pruebas Saber Pro entre los años 2018 y 2021 de 1,12 millones de evaluados; con 50 características (casi todas ellas cualitativas) y resultados en los 7 componentes.

Para el entrenamiento se usaron 100.000 muestras

Disponible en: https://www.datos.gov.co/Educaci-n/Resultados-nicos-Saber-Pro/u37r-hjmu

**Características utilizadas**
 - Metodología del programa
 - Tipo de institución
 - Valor matricula (Rangos, no valores exactos)
 - Horas trabajadas por semana
 - Si la matricula es pagada o no por los padres
 - Estrato socioeconómico
 - Si se tiene acceso a un computador en casa
 - Si se tiene acceso a internet en casa
 - Si esta estudiando en este momento
 - Si tiene crédito de estudios
 - Si la familia tiene automóvil

**Métodos utilizados**
SVM, random forest y redes neuronales

**Métricas de evaluación**
F1 Score y MCC

**Resultados por método**

***SVM***
 - F1: 0,319
 - MCC: 0,168

***Random forest***
 - F1: 0,320
 - MCC: 0,153

***Red neuronal***
 - F1: 0,373
 - MCC: 0,173

**Resultado general**
No se consiguió el objetivo
(Razones por las que ocurrió esto en el documento de informe)

**Video resumen**
https://www.youtube.com/watch?v=FJWhwRu11nY
