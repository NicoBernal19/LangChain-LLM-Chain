# LangChain-LLM-Chain

## Hecho por: Nicolas Bernal

Este proyecto es una implementación básica de una cadena de lenguaje utilizando LangChain y un modelo de lenguaje de OpenAI (GPT-4). El objetivo es demostrar cómo se pueden utilizar las herramientas de LangChain para interactuar con modelos de lenguaje y realizar tareas como la traducción de texto.

## Componentes

El proyecto consta de los siguientes componentes principales:

Instalación de Dependencias: Se utiliza la biblioteca langchain para interactuar con el modelo de lenguaje.

![image](https://github.com/user-attachments/assets/fea96d31-4a08-49de-9f8e-06be48a1af86)

Configuración de la API de OpenAI: Se solicita al usuario que ingrese su clave API de OpenAI para autenticar las solicitudes.

![image](https://github.com/user-attachments/assets/ad88cca3-6442-464e-959c-b798d39ecc62)

Inicialización del Modelo: Se inicializa un modelo de chat utilizando init_chat_model con el proveedor openai.

![image](https://github.com/user-attachments/assets/89a4c046-5113-4cbc-bb8b-cea03159df89)

Interacción con el Modelo: Se demuestra cómo enviar mensajes al modelo y recibir respuestas, incluyendo la traducción de texto (en este caso de ingles a italiano).

## Diagrama

![image](https://github.com/user-attachments/assets/2e36dd06-59d1-4cf6-a529-8dc7faab04ad)

## Instalacion y Ejecucion

Toma el archivo .ipynb y usalo para cargar el notebook en colab.

### Instala las dependencias:

- pip install langchain
- pip install -qU "langchain[openai]"

### Configura la API de OpenAI

Necesitas configurar tu clave API de OpenAI, en este caso nosotros recibimos la clave de parte del profesor.

### Sigue las instrucciones del Notebook

Ejecuta el resto de celdas del notebook para que el programa funcione correctamente.

## Ejemplo en accion

![image](https://github.com/user-attachments/assets/7fc81b4d-73b3-4a97-859a-c94ac2b6b1ae)
