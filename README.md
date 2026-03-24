# IX-SierraGorda-Fragmentacion_Conectividad
# Monitoreo de Conectividad Biocultural: Corredor del Jaguar

### Sierra Gorda Hidalguense, México 🇲🇽
Este repositorio contiene el flujo de trabajo geoespacial para la delimitación de corredores biológicos funcionales para el jaguar (*Panthera onca*). 
Integra **Machine Learning (Random Forest)**, **Índices de Salud Forestal (NBR)** y **Ecología del Paisaje**.

## 🚀 Metodología IX
1. **Detección:** Clasificación de coberturas en GEE con resolución de 30m.
2. **Diagnóstico:** Identificación de degradación silenciosa vía NBR.
3. **Análisis:** Cuantificación de fragmentación en R (TCA, ENN, COHESION).
4. **Espacialización:** Generación de capas de "Fricción y Área" para QGIS.

## 📊 Hallazgos Clave
- **Nodos Principales:** Identificados mediante parches > X hectáreas de área núcleo.
- **Piedras de Paso (Stepping Stones):** Parches pequeños con alto vigor fotosintético estratégicos para la conectividad.

## 🛠️ Cómo usar este repositorio
1. Abre el notebook de R en Google Colab.
2. Sube tu raster de clasificación.
3. Ejecuta el script maestro para obtener los reportes estadísticos y mapas de métricas.
