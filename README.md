# frost-warning-agents
Documentar el sistema híbrido de IA  Sintetizar metodología para predicción de heladas  Servir como guía replicable para investigadores
# agents.md

## 🎯 Propósito del Agente
Desarrollar un sistema híbrido de inteligencia artificial para **predicción temprana de heladas** en los Andes peruanos, integrando datos satelitales MODIS LST con modelos de machine learning y deep learning en Google Earth Engine.

---

## 📥 Entradas
- **Datos satelitales:** MODIS LST (nocturnos).  
- **Datos meteorológicos:** Estaciones SENAMHI (temperatura mínima).  
- **Variables geoespaciales:** Altitud, cobertura vegetal, topografía.  

---

## ⚙️ Procesos
1. **Preprocesamiento en Google Earth Engine (GEE):**
   - Extracción de series MODIS LST.
   - Corrección y filtrado de nubes.
   - Vinculación con estaciones SENAMHI.

2. **Modelado híbrido:**
   - **Machine Learning:** Random Forest, XGBoost.
   - **Deep Learning:** LSTM, ConvLSTM.
   - **Evaluación:** r², RMSE, Accuracy.

3. **Análisis espacial:**
   - Mapas de riesgo por altitud (> 4,000 m a.s.l.).
   - Identificación de zonas críticas (puna, pastizales altoandinos).

---

## 📊 Comparativa de Modelos

| Modelo        | Tipo            | Accuracy | RMSE (°C) | Ventajas principales |
|---------------|-----------------|----------|-----------|----------------------|
| Random Forest | ML Ensemble     | 85.2%    | 2.4       | Robusto, interpretable |
| XGBoost       | ML Ensemble     | 87.5%    | 2.1       | Manejo eficiente de datos tabulares |
| LSTM          | Deep Learning   | 89.3%    | 2.0       | Captura dependencias temporales |
| ConvLSTM      | Deep Learning   | **91.7%**| **1.8**   | Mejor desempeño, modela espacio-tiempo |

---

## 📤 Salidas
- **Predicciones de heladas:** 48–72 horas de anticipación.  
- **Mapas de riesgo territorial:** Zonas críticas > 4,000 m a.s.l.  
- **Sistema replicable:** Bajo costo, escalable, reproducible.  

---

## 🌍 Aplicaciones
- **Agricultura:** Alertas tempranas para cultivos sensibles.  
- **Ganadería:** Prevención de pérdidas en pastoreo altoandino.  
- **Gestión pública:** Planes de adaptación climática y resiliencia.  

---

## 👥 Autores
- First Author1  
- Second Author2  

---

## 📚 Referencias
- MODIS Land Surface Temperature (NASA).  
- Google Earth Engine (GEE).  
- SENAMHI (Perú).  

---

## 🔑 Palabras clave
Frost Prediction · Artificial Intelligence · Google Earth Engine · Andes · Climate Adaptation
