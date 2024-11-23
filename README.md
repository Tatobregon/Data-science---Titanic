# Titanic Survival Prediction 🚢

**Autor**: Lautaro Tomás Obregón | **Email**: [lautarobregon@gmail.com](lautarobregon@gmail.com) | **Teléfono**: +54 9 351 803 8070  
## Descripción  
Este proyecto aborda la predicción de supervivencia de pasajeros del Titanic utilizando **Machine Learning**. Implementa aisis exploratorio, ingeniería de variables, balanceo del dataset y modelos de aprendizaje supervisado para llevar a cabo la tarea  

---

## Objetivos  
1. **Limpieza y análisis del dataset**: Identificación de valores nulos y patrones clave.  
2. **Ingeniería de variables**: Transformación y creación de variables relevantes.  
3. **Balanceo de clases**: Generación de muestras adicionales para equilibrar los datos.  
4. **Modelado predictivo**: Entrenamiento y evaluación de algoritmos de clasificación.  

---

## Herramientas  
- **Lenguajes**: Python  
- **Bibliotecas**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Modelos**: Random Forest

---

## Proceso  

### 1. Análisis Exploratorio  
- **Gráficos**: Supervivencia por género, clase y edad.  
- **Estadísticas**: Media, mediana, distribución de tarifas y edades.  

### 2. Ingeniería de Características  
- **Variables nuevas**:  
  - `Pclass_Sex`: Combinación de clase y género.  
  - `Categoria_edad`: Rango etario.  
  - `Cuota_por_pasajero`: Proporción del precio del ticket por integrante de familia.  
- **Transformaciones matemáticas**: Generación de nuevas muestras equilibradas para sobrevivientes.  

### 3. Modelos  
- **Random Forest**: Modelo principal optimizado con búsqueda de hiperparámetros.  
- **Otros**: Comparación con regresión logística y Gradient Boosting.  

### 4. Evaluación  
- **Métricas**: accurracy, matriz de confusión, curvas de aprendizaje.  
- **Resultados**:  
  - Precisión del mejor modelo: **87%**  
  - Métricas balanceadas (igual cantidad de 0 y 1).  

---

## Contacto  

📧 [lautarobregon@gmail.com](mailto:lautarobregon@gmail.com)  
📱 +54 351 803 8070  
🌍 Córdoba, Argentina  

---

**Nota**: Este proyecto forma parte de mi portafolio como estudiante de Inteligencia Artificial y Ciencia de Datos. ¡Contribuciones y feedback son bienvenidos!  
