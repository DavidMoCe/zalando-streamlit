# Clothing Classification - Fashion MNIST 👕👗

## 🌍 Choose Your Language / Elige tu idioma:
- [English](#english-)
- [Español](#español-)

---

## English 🇬🇧

This repository contains an application built with [Streamlit](https://streamlit.io/) that uses a deep learning model to classify images of clothing into categories from the Fashion MNIST dataset.

You can access the app via the following link:
🌐 [Zalando on Streamlit](https://zalando-david.streamlit.app/)

## Features ✨

- **Model:** Based on TensorFlow/Keras, trained on the Fashion MNIST dataset.
- **User Interface:** Streamlit allows uploading an image of clothing and obtaining a real-time prediction.
- **Preprocessing:** The image is converted to grayscale, colors are inverted, and contrast is adjusted to fit the model's expected format.

## Supported Categories 🧥👖
The model can classify clothing into the following categories:

1. T-shirt/Top
2. Pants
3. Sweater
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Boots

## Requirements 📋

Make sure you have the following installed before running the application:

- Python 3.8 or higher
- TensorFlow
- Streamlit
- Pillow
- NumPy

You can install the dependencies by running:

```bash
pip install -r requirements.txt
```

## Usage 🚀

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/fashion-mnist-classification.git
   cd fashion-mnist-classification
   ```

2. **Run the application:**
   ```bash
   streamlit run app.py
   ```

3. **Upload an image:** Upload a clothing image in JPG or PNG format to be classified.

## How It Works 🛠️

1. **Model Loading:** The `fashion_mnist.keras` file contains the pre-trained model.
2. **Image Upload:** The user can upload an image in JPG or PNG format.
3. **Preprocessing:**
   - The image is converted to grayscale.
   - Colors are inverted (so clothing appears white on a black background).
   - Resized to 28x28 pixels.
   - Pixel values are normalized between 0 and 1.
4. **Prediction:** The processed image is passed to the model, which predicts the clothing category.
5. **Result:** The predicted category is displayed along with the preprocessed image.

## License 📄

This project is licensed under the MIT License. See the [`LICENSE`](https://github.com/DavidMoCe/zalando-streamlit/blob/main/LICENSE.txt) file for details.

---

## Español 🇪🇸

Este repositorio contiene una aplicación desarrollada con [Streamlit](https://streamlit.io/) que utiliza un modelo de aprendizaje profundo para clasificar imágenes de prendas de vestir en las categorías del dataset Fashion MNIST.

Puedes acceder a la aplicación en el siguiente enlace:  
🌐 [Zalando en Streamlit](https://zalando-david.streamlit.app/)

## Características ✨

- **Modelo:** Basado en TensorFlow/Keras, entrenado en el dataset Fashion MNIST.
- **Interfaz de usuario:** Streamlit permite cargar una imagen de una prenda y obtener la predicción en tiempo real.
- **Preprocesamiento:** La imagen se convierte a escala de grises, se invierten los colores y se ajusta el contraste para adaptarla al formato esperado por el modelo.

## Categorías soportadas 🧥👖
El modelo puede clasificar prendas en las siguientes categorías:

1. Camiseta/Top
2. Pantalón
3. Suéter
4. Vestido
5. Abrigo
6. Sandalia
7. Camisa
8. Zapatilla
9. Bolso
10. Botas

## Requisitos 📋

Asegúrate de tener instalado lo siguiente antes de ejecutar la aplicación:

- Python 3.8 o superior
- TensorFlow
- Streamlit
- Pillow
- NumPy

Puedes instalar las dependencias ejecutando:

```bash
pip install -r requirements.txt
```

## Uso 🚀

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/tu-usuario/clasificacion-fashion-mnist.git
   cd clasificacion-fashion-mnist
   ```

2. **Ejecuta la aplicación:**
   ```bash
   streamlit run app.py
   ```

3. **Sube una imagen:** Carga una imagen en formato JPG o PNG de una prenda para que sea clasificada.

## Cómo funciona 🛠️

1. **Carga del modelo:** El archivo `fashion_mnist.keras` contiene el modelo previamente entrenado.
2. **Carga de imagen:** El usuario puede subir una imagen en formato JPG o PNG.
3. **Preprocesamiento:**
   - La imagen se convierte a escala de grises.
   - Se invierten los colores (para que las prendas sean blancas sobre fondo negro).
   - Se redimensiona a 28x28 píxeles.
   - Se normalizan los valores de los píxeles entre 0 y 1.
4. **Predicción:** La imagen procesada se pasa al modelo, que predice la clase de la prenda.
5. **Resultado:** Se muestra la categoría predicha junto con la imagen preprocesada.

## Licencia 📄

Este proyecto está bajo la Licencia MIT. Consulta el archivo [`LICENSE`](https://github.com/DavidMoCe/zalando-streamlit/blob/main/LICENSE.txt) para más detalles.
