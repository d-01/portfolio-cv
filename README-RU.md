Язык: [en](README.md) | ru

# Портфолио

*Компьютерное зрение / ИИ*

1. [Система оптического распознавания паспортных данных с помощью нейросетей](#passport-ocr)
1. [Система ИИ для определения эмоции пользователя с помощью веб-камеры](#webcam-emotion-recognition)
1. [Обучение нейросетевой модели ИИ для консольной игры Ping-Pong](#pong-ai)

<a id="passport-ocr"></a>

## Система оптического распознавания паспортных данных с помощью нейросетей

*2022-12*

![passport-ocr](img/passport-ocr.jpg)

* [github.com/d-01/passport-ocr-test](https://github.com/d-01/passport-ocr-test)
* Распознавание выполняется в 3 этапа:
  1. Локализация страницы паспорта на изображении
  1. Детектирование текстовых полей
  1. Распознавание символов
* Не требует установки, работает полностью в среде Google Colab ([открыть](https://colab.research.google.com/drive/1c3nP5v1tXdU9bPQe59H3ZFRu5TWkMCcU)).
* Технологии: python, opencv, pillow, OCR, tensorflow, keras, numpy, cnn

<a id="webcam-emotion-recognition"></a>

## Система отслеживания эмоций с помощью веб-камеры

*2022-01*

<p align="center"><img src="img/6.jpg" style="zoom: 67%;" /></p>

* [github.com/d-01/webcam-emotion-recognition](https://github.com/d-01/webcam-emotion-recognition)
* Работает с веб-камерой, отслеживает положение лица и определяет эмоцию.
* Не требует установки, работает полностью в среде Google Colab ([открыть](https://colab.research.google.com/drive/1cvAZvsXXbZHi--QFNJDfTJEGB1JapKvo?usp=sharing)).
* Технологии: python, tensorflow, keras, opencv, cnn, mobilenet, fer, facial expression recognition, valence-arousal, face detection, dlib, google colab, javascript, html canvas

<a id="pong-ai"></a>

## Обучение нейросетевой модели ИИ для консольной игры Ping-Pong

*2021-09*

<p align="center"><img src="img/4.png" style="zoom:67%;" /></p>

* [Открыть](https://d-01.github.io/static/jupyter-export/pong-ai.html) Jupyter Notebook
* [Видео](img/pong-q-learning-demo.mp4)
* Обучение нейросети для игры в ping-pong используя изображение с экрана (raw-pixel data).
* Технологии: RL, reinforcement learning, tensorflow, gym, Q-learning, DQN, replay buffer

