# 🤖 Robotrader COIL – Machine Learning Trading Bot

Este proyecto fue desarrollado en el marco del **COIL (Collaborative Online International Learning)** entre la Universidad Católica Luis Amigó (Colombia) y la Universidad de Monterrey (México).  
El objetivo fue construir un **robot de trading** que, usando **Machine Learning en Python (scikit-learn)**, tome decisiones de **compra, venta o mantener** sobre acciones de **Apple Inc. (AAPL)** y maximice el rendimiento acumulado.

---

## 📂 Estructura del Repositorio
- **Coil_instrucciones_sp24.pdf** → lineamientos oficiales del proyecto.  
- **Ideas- Robotrader.docx** → documento inicial con la planeación y metodología.  
- **EntregaSemana2.ipynb** → análisis del problema y plan inicial.  
- **Entrega3.ipynb** → metodología y resultados preliminares.    
- **Robotrader entrega final.ipynb** → notebook final con backtesting y conclusiones.  
- **Proyecto COIL.zip** → entrega final comprimida (respaldo).  

---

## 🔎 Contenido del Proyecto
1. **Análisis de Datos Históricos**  
   - Precios de cierre de Apple Inc. (AAPL), 2021–2023.  
   - Visualización de tendencias, volatilidad y medias móviles.  

2. **Preprocesamiento**  
   - Limpieza de datos.  
   - Normalización y selección de características.  

3. **Modelado**  
   - Algoritmos probados: regresión, árboles de decisión, RandomForest.  
   - Señales de trading basadas en predicciones de precio y análisis técnico (RSI, Bollinger, ADX, etc.).  

4. **Backtesting**  
   - Simulación de decisiones en el conjunto de prueba.  
   - Cálculo del rendimiento acumulado.  
   - Comparación contra estrategia *buy and hold*.  

5. **Conclusiones**  
   - El robot fue capaz de tomar más de 20 decisiones en el test set, cumpliendo los requisitos del COIL.  
   - Se identificaron métricas de rendimiento y limitaciones del modelo.  
   - Recomendaciones para optimizar en trabajos futuros.  

---

## 🛠️ Tecnologías utilizadas
- **Python** (Pandas, NumPy, scikit-learn, Matplotlib, Seaborn)  
- **Jupyter Notebook**  
- **Machine Learning aplicado a series temporales**  

---

## 📣 Autor
**Miguel Gallego Álvarez**  
✉️ miguelgallego2020@gmail.com  
