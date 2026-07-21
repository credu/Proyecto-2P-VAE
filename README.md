# Proyecto 2P VAE

**Enlace del paper:** [https://arxiv.org/abs/2102.03082](https://arxiv.org/abs/2102.03082)

## Descripción del Proyecto
Este proyecto aplica los conceptos de *transfer learning* y adaptación de dominio utilizando un modelo de Autoencoder Variacional (VAE). Toma como referencia el artículo *"Achieving Explainability for Plant Disease Classification with Disentangled Variational Autoencoders"*, el cual propone una arquitectura VAE para la clasificación y explicabilidad de enfermedades en plantas.

## Objetivo
El objetivo principal del proyecto es adaptar un modelo VAE pre-entrenado hacia un problema/dominio concreto mediante *fine-tuning* o adaptación de dominio. Tal como lo establece la rúbrica, se busca realizar una **comparación cuantitativa estricta antes vs. después**, contrastando el desempeño del modelo base sin adaptar (evaluado de forma *zero-shot* en el nuevo dominio) frente al modelo adaptado, para determinar: *¿Cuánto mejora el modelo tras el proceso de adaptación?*

## Integrantes:
- Mendoza Navarro Jesus Jeampool
- Torres Feijoo Karen Jaqueline
- Garcia Figueroa Justyn Gabriel
- Troya Riofrio Daniel Moises
- Alvarez Sanchez Jose Alejandro

## Ejecución en Google Colab
Puede probar el código utilizando Google Colab con el siguiente enlace:

**[Abrir Notebook en Google Colab](https://drive.google.com/file/d/1pnlMIT0mIAfoQUFibXBO6J5spDFetNb4/view?usp=sharing)**

> **Nota:** Para la ejecución del codigo es necesario configurar el entorno de ejecución para que utilice una **GPU (T2/T4)**.
