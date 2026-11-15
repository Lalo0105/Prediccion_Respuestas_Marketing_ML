# *Prediccion de Respuesta a Ofertas de Marketing*


## *Autoras*
Luisa Fernanda Doria Yabrudy
Yarilis Mileth Garcia Gómez

## *Objetivo y Contexto*
Las empresas gastan mucho dinero en campañas de marketing que la mayoría de clientes ignoran. Nuestro objetivo es entender qué características distinguen a los clientes que sí aceptan una oferta, para poder dirigir mejor esas campañas y ahorrar costos. Por otro lado, queremos saber como se comportan los clientes más valiosos para las empresas basandonos en el historial de sus gastos en diferentes productos por categoria, esto ayudaria a las empresas a identificar a los clientes con mayor volumen de consumo y cuales son sus intereses reales.

## *Descripción del Dataset*
Para el desarrollo del proyecto, utilizamos un dataset público *Customer Personality Analysis*, publicado en Kaggle por *Akash Patel*.
El proposito original de la base de datos es realizar análisis y segmentación de clientes mediante técnicas de claustering. Sin embargo, para la realización de este proyecto, adaptamos su enfoque y reformulamos el problema como una tarea de aprendizaje supervisado, utilizando modelos de clasificación y regresión.

## *Modelos de Machine Learning usados*
A partir de la información demográfica, el comportamiento de compra y la respuesta a campañas de marketing, desarrollamos modelos con 2 objetivos diferentes:

### Modelos de clasificación: 
para predecir si un cliente aceptará o no una campaña de marketing, tomando como variable objetivo Response (0: no acepta, 1: acepta)
* Gaussian Naive Bayes
* Decision Tree Classifier
* Random Forest Classifier
* Support Vector Machine

### Modelos de regresión
Se utilizaron para estimar el gasto total de cada cliente, a partir de sus características demográficas y comportamiento de compra
* Decision Tree Regressor
* Random Forest Regressor
* Support Vector Regression

## *Enlaces*
* Video:
* Notebook: https://colab.research.google.com/drive/1xqMkvvCAN62NxP2cn54q3LsVf3EFNTD8?usp=sharing
* Dataset: https://raw.githubusercontent.com/Lalo0105/Marketing-Campaign/refs/heads/main/marketing_campaign.csv
* Presentación: 
