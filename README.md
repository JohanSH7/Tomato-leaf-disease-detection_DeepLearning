# 🍅 Tomato Leaf Disease Detection - Deep Learning Project

Este proyecto utiliza técnicas de **Deep Learning** para diagnosticar enfermedades en hojas de tomate a partir de imágenes.  
Se desarrolla un modelo de **red neuronal convolucional (CNN)** capaz de clasificar imágenes en **10 categorías** diferentes, correspondientes a enfermedades específicas o a hojas saludables.

## 🌱 Contexto
Las enfermedades en cultivos de tomate representan una amenaza significativa para la producción agrícola y la seguridad alimentaria.  
Mediante el uso de IA, este proyecto busca ofrecer una herramienta escalable que pueda ser integrada en aplicaciones móviles, sistemas de drones o estaciones inteligentes de monitoreo agrícola.

## 🎯 Objetivo
Construir y entrenar un modelo CNN que clasifique correctamente imágenes de hojas de tomate en una de las siguientes clases:

- **Tomato___Bacterial_spot**
- **Tomato___Early_blight**
- **Tomato___Late_blight**
- **Tomato___Leaf_Mold**
- **Tomato___Septoria_leaf_spot**
- **Tomato___Spider_mites Two-spotted_spider_mite**
- **Tomato___Target_Spot**
- **Tomato___Tomato_Yellow_Leaf_Curl_Virus**
- **Tomato___Tomato_mosaic_virus**
- **Tomato___healthy**

## 📦 Dataset
- **Fuente**: [Kaggle - Tomato Leaf Disease Detection](https://www.kaggle.com/datasets/kaustubhb999/tomatoleaf/)
- **Cantidad**: 11,000 imágenes en total (formato `.jpg`, resolución 256x256 píxeles).
- **Distribución**:
  - Entrenamiento: 10,000 imágenes (1,000 por clase).
  - Validación: 1,000 imágenes (100 por clase).
- **Balance**: El dataset está completamente balanceado entre clases.

## ⚙️ Metodología
- **Modelos evaluados**:
  - ResNet-50
  - MobileNetV3
  - InceptionV3
  - VGG16 (modelo con mejor desempeño)
- **Aumentos de datos**: Rotaciones, desplazamientos, zooms, flips, contraste y brillo aleatorios, para mejorar la generalización.
- **Optimización**:
  - Función de pérdida: `categorical_crossentropy`
  - Optimizador: `Adam`
- **Evaluación**:
  - Accuracy global
  - Métricas por clase: Precision, Recall, F1-Score
  - Matriz de confusión
  - Gráficas de evolución de precisión y pérdida (`loss`)

## 🎥 Video de presentación
Para conocer más detalles del proyecto, puedes ver el video explicativo en YouTube, donde mostramos los datos, el código, el proceso de entrenamiento y los resultados finales:

🔗 [Ver video en YouTube](https://www.youtube.com/watch?v=qrI-pqzGsrM)

## 👥 Integrantes
- **Ana María Vega Angarita**  
  Estudiante  
  Departamento de Ingeniería de Sistemas  
  Universidad de Antioquia  
  ana.vega@udea.edu.co

- **Maritza Tabarez Cárdenas**  
  Estudiante  
  Departamento de Ingeniería de Sistemas  
  Universidad de Antioquia  
  maritza.tabarezc@udea.edu.co

- **Johan Sebastian Henao Cañas**  
  Estudiante  
  Departamento de Ingeniería de Sistemas  
  Universidad de Antioquia  
  johan.henao1@udea.edu.co

## 📈 Impacto esperado
- Reducción de errores humanos en la detección de enfermedades.
- Aceleración en el monitoreo de cultivos agrícolas.
- Prevención de pérdidas económicas mediante la detección temprana.
- Cobertura de enfermedades críticas relevantes para la industria del tomate.

## 📚 Referencias
- [Dataset en Kaggle](https://www.kaggle.com/datasets/kaustubhb999/tomatoleaf/)
- [Curso Deep Learning - R. Ramos](https://rramosp.github.io/2021.deeplearning/content/M04.html)
