# 📦 Análisis de Entregas Logísticas en CABA
Este proyecto surge a partir de datos reales de entregas domiciliarias con los que trabajé en una operación logística.

La idea fue entender cómo se comportan los clientes, dónde se concentran las entregas y qué oportunidades hay para mejorar la distribución o incluso armar algo propio a partir de esto.

## 🎯 Objetivo
Más que hacer un análisis técnico, el foco fue responder preguntas concretas:

¿Dónde están realmente los clientes? ¿Se pueden agrupar para optimizar rutas? ¿Hay zonas que justifican un esquema de reparto propio? ¿Se puede pensar en un modelo tipo suscripción o marketplace? 📊 Dataset

Se trabajó con un dataset anonimizado de entregas reales:

+25.000 registros ~90.000 clientes únicos Ubicados en CABA

Incluye información como dirección, coordenadas y zonas de entrega.

## 🧠 Qué hice
Limpieza y normalización de datos Eliminación de duplicados Georreferenciación de clientes Segmentación por zonas Visualización en mapas para entender distribución real

## 💡 Qué encontré
Hay zonas con muchísima concentración de entregas Se forman clusters claros que permiten pensar rutas más eficientes Hay clientes recurrentes que tienen valor comercial La distribución no es uniforme, lo que abre oportunidades para segmentar

## 📍 Visualización geográfica

### 🌎 Mapa general de clientes
![Mapa general](images/clientes_unicos_total.png)

### 📌 Zona Palermo - Belgrano
![Palermo Belgrano](images/mapa_palermo_belgrano.png)

### 📌 Zona Caballito - Almagro
![Caballito Almagro](images/mapa_caballito_almagro.png)

## 🚀 Para qué sirve esto
Este análisis no queda solo en lo descriptivo.

Se puede usar como base para:

Optimizar una operación logística existente Definir zonas de reparto Armar un esquema de entregas por suscripción Pensar un marketplace de delivery enfocado en bebidas u otros productos
