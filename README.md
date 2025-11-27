# hotel-prediction-app
🏨 Predicción de Cancelación de Reservas de Hotel

Aplicación web interactiva basada en Machine Learning para predecir la probabilidad de que una reserva de hotel sea cancelada. Este proyecto fue desarrollado como parte del Proyecto Final de la materia de Data Science.

🔗 Demo en Vivo

Puedes probar la aplicación funcionando aquí:
[https://hotel-prediction-app-rdfjcmu53cpsgj8zbgjbo4.streamlit.app/]


📋 Descripción del Proyecto

El objetivo de esta herramienta es ayudar a la gestión hotelera a anticipar cancelaciones. El usuario ingresa características de la reserva (como días de anticipación, tipo de depósito, número de huéspedes, etc.) y el modelo devuelve la probabilidad de riesgo.

Características Principales:

Interfaz Amigable: Desarrollada con Streamlit para una fácil interacción.

Modelo Predictivo: Utiliza un modelo de XGBoost entrenado con miles de datos históricos.

Resultados en Tiempo Real: Cálculo inmediato de la probabilidad de cancelación.

🧠 Detalles Técnicos

El proyecto siguió un flujo completo de Ciencia de Datos:

EDA (Exploratory Data Analysis): Limpieza y análisis de correlaciones.

Modelado (PF_2): Se compararon algoritmos clásicos (Regresión Logística, SVM, Random Forest, XGBoost).

Deep Learning (PF_3): Se experimentó con Redes Neuronales (MLP, DNN, LSTM) para contrastar resultados.

Selección del Modelo: El modelo XGBoost fue seleccionado por obtener el mejor balance (F1-Score ~83%) y eficiencia computacional.

Despliegue (PF_4): Implementación web usando Streamlit.

🛠️ Instalación y Uso Local

Si deseas correr este proyecto en tu propia computadora:

Clonar el repositorio:

git clone [https://github.com/MoisesBustillos/hotel-prediction-app.git](https://github.com/TU_USUARIO/hotel-prediction-app.git)
cd hotel-prediction-app


Instalar dependencias:
Asegúrate de tener Python instalado y ejecuta:

`pip install -r requirements.txt`


Ejecutar la aplicación:

`streamlit run streamlit_app.py`


📂 Estructura del Repositorio

`streamlit_app.py`: Código principal de la interfaz web.

`modelo_hotel_booking.sav`: Archivo binario con el modelo entrenado.

`requirements.txt`: Lista de librerías necesarias para ejecutar el proyecto.

`PF_2_HOTEL_BOOKING_PREDICTOR.ipynb`: Notebook con el análisis, entrenamiento y evaluación de modelos.

👨‍💻 Autor

* Moisés Aarón Bustillos Sandoval

* Matrícula: 361352

* Carrera: Ingeniería en Ciencias de la Computación

* Materia: Data Science

* Facultad: Facultad de Ingeniería
