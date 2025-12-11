# 📊 Clasificación de Tickets — Modelo de Machine Learning

## 🎯 Objetivo
Desarrollar un modelo de Machine Learning capaz de clasificar tickets de soporte de una entidad bancaria para mejorar la gestión, priorización y el tiempo de respuesta de solicitudes internas.

---

## 📁 Dataset
- **Filas:** 660  
- **Columnas:** 51 
- **Tipo:** variables categóricas y numéricas  
- **Descripción:** El dataset contiene información de tickets internos, incluyendo categoría, prioridad, tiempos, responsables y atributos operativos relacionados con el flujo de soporte.

---

## 🔧 Metodología
1. Limpieza y preprocesamiento del dataset  
2. Codificación de variables categóricas  
3. Exploración y análisis de las características  
4. Entrenamiento de múltiples modelos de clasificación  
5. Comparación de métricas  
6. Optimización del modelo seleccionado mediante Grid Search  

---

## 🧠 Modelos evaluados
- Random Forest  
- XGBoost  
- CatBoost
- LightGBM

---

## 🏆 Mejor modelo
- **Modelo final:** XGBoost 
- **Accuracy final:** ~0.98  
- **Mejora respecto al modelo base:** ≈ 2%  
- **Comentario:** XGBoost mostró el mejor equilibrio entre precisión y estabilidad en validación cruzada, manejando bien las variables categóricas y la distribución de clases del dataset.

---

## 📈 Resultados y conclusiones
- XGBoost superó consistentemente a los demás modelos en validación cruzada.  
- La optimización de hiperparámetros incrementó la precisión general del modelo.  
- Se identificaron variables clave que influyen en la clasificación de los tickets.  
- El modelo puede ser utilizado para priorizar solicitudes de soporte dentro del banco, reduciendo tiempos y mejorando la eficiencia interna.

---

## 🛠️ Tecnologías
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib / Seaborn   

---

## ▶️ Cómo ejecutar el proyecto
```bash
pip install -r requirements.txt
jupyter notebook

