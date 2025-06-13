# Space Invaders RL Agent 🎮🧠

Este proyecto tiene como objetivo desarrollar un agente de Aprendizaje por Refuerzo capaz de obtener una **puntuación media superior a 20 puntos** en el entorno de **Space Invaders** del entorno `Gym` de OpenAI.

## 📚 Asignatura

**Aprendizaje por Refuerzo**  
Máster en Inteligencia Artificial

## 🚀 Descripción del proyecto

Space Invaders es un clásico videojuego arcade, donde el jugador controla una nave que dispara a enemigos alienígenas que descienden en formación. El objetivo del agente es aprender a jugar de forma eficiente mediante técnicas de Aprendizaje por Refuerzo, buscando superar la media de 20 puntos.

El entorno utilizado es:
- `gym.make("ALE/SpaceInvaders-v0")`  

El agente interactúa con el entorno y aprende una política que maximiza la recompensa acumulada por episodio.

## 🛠️ Tecnologías y librerías utilizadas

- Python 3.8
- [Gym](https://www.gymlibrary.dev/)
- NumPy
- PyTorch o TensorFlow (según implementación)
- keras-rl
- Matplotlib (opcional para visualización)

## 🤖 Algoritmos explorados

Algunos de los algoritmos evaluados y/o implementados:

- DQN (Deep Q-Network)

## 🎯 Objetivo

Obtener una **puntuación media > 20** en Space Invaders, medida sobre al menos 10 episodios de evaluación tras el entrenamiento.

## 📊 Métricas de evaluación

- Puntuación media por episodio (reward)
- Curvas de recompensa durante el entrenamiento
- Evaluación de estabilidad y varianza entre ejecuciones

## 📁 Estructura del repositorio

