<p align="center">
  <img src="https://github.com/AlexandrNizkovskih/AlexandrNizkovskih/blob/main/Banner.png?raw=true" alt="Portfolio Banner" width="100%">
</p>

# Проекты в области машинного обучения и нейронных сетей

Репозиторий с реализованными проектами в области нейронных сетей, машинного обучения и искусственного интеллекта.

---

## Проекты по компьютерному зрению (Computer Vision, CV)

> Классификация изображений, детекция объектов, сегментация, OCR.

<br>

| Проект | Описание | Стек технологий |
|:-------|:---------|:----------------|
| [Object Detection in Video Streams (YOLO)](https://github.com/AlexandrNizkovskikh/yolo-video-object-detection)| Сравнительный анализ производительности моделей YOLO на видеопотоках с применением оптимизаций (Batch Inference, FP16). | Python, OpenCV, Ultralytics YOLO, FiftyOne, NumPy |
| [Stanford Dogs Breed Classification](https://github.com/AlexandrNizkovskikh/stanford-dogs-breed-classification) | Классификация пород собак с использованием EfficientNetV2B0 и аугментацией данных. | Python, TensorFlow, Keras, Matplotlib |
| [Face and Eye Detection (OpenCV)](https://github.com/AlexandrNizkovskikh/face-eye-detection-opencv) | Распознавание лиц и глаз с использованием каскадов Хаара в OpenCV и визуализация результатов. | Python, OpenCV, Matplotlib |
| [Lung Radiograph Segmentation (U-Net)](https://github.com/AlexandrNizkovskikh/lung-xray-segmentation-unet) | Сегментация снимков лёгких с использованием архитектуры U-Net и аугментацией медицинских данных. | Python, TensorFlow, Keras, NumPy |
| [Cats vs Dogs Classification (MobileNet)](https://github.com/AlexandrNizkovskikh/cats-vs-dogs-classification) | Классификация изображений кошек и собак с использованием предобученной модели MobileNet и аугментации данных. | Python, TensorFlow, Keras, Matplotlib |
| [Traffic Signs Detection (YOLOv11)](https://github.com/AlexandrNizkovskikh/yolov11-traffic-signs-detection) | Дообучение модели YOLOv11 для детекции дорожных знаков и инференс на реальных видео. | Python, Ultralytics, TensorBoard, OpenCV |

---

## Проекты по обработке естественного языка (Natural Language Processing, NLP)

> Классификация текстов, суммаризация, генерация текста, перевод.

<br>

| Проект | Описание | Стек технологий |
|:-------|:---------|:----------------|
| [Text Classification with BERT](https://github.com/AlexandrNizkovskikh/bert-text-classification) | Классификация текстов с использованием BERT, очистка данных и визуализация матрицы ошибок. | Python, Hugging Face Transformers, Datasets, Scikit-learn, Matplotlib |
| [Russian News Headline Generation](https://github.com/AlexandrNizkovskikh/russian-news-headline-generation) | Генерация заголовков новостей на русском языке с использованием модели GPT на корпусе Lenta.ru. | Python, Hugging Face Transformers, Datasets, Scikit-learn, Pandas |
| [Russian Literature Text Classification](https://github.com/AlexandrNizkovskikh/russian-literature-text-classification) | Классификация текстов русских писателей с использованием эмбеддингов Navec и нейронной сети на Keras. | Python, Keras, TensorFlow, Razdel, Navec |
| [Sentiment Analysis (IMDB Dataset)](https://github.com/AlexandrNizkovskikh/imdb-sentiment-analysis) | Классификация отзывов о фильмах с использованием простой нейронной сети и регуляризации. | Python, Keras, NumPy, Matplotlib |
| [Text Classification with AutoML](https://github.com/AlexandrNizkovskikh/text-classification-automl) | Автоматический подбор архитектуры нейронной сети для задачи классификации саркастических заголовков. | Python, TensorFlow, AutoKeras, KerasTuner |

---

## Проекты по кластеризации и аналитике данных
> Анализ данных, сегментация пользователей, выявление скрытых закономерностей.

<br>

| Проект | Описание | Стек технологий |
|:-------|:---------|:----------------|
| [Customer Segmentation (Mall_Customers)](https://github.com/AlexandrNizkovskikh/customer-segmentation-mall-customers/tree/main) | Сегментация клиентов с использованием KMeans, стандартизация данных, визуализация результатов и оценка качества кластеризации. | Python, Scikit-learn, Plotly, Pandas, NumPy, Matplotlib |

---

## Проекты с большими языковыми моделями (LLM) и интерфейсами
> Разработка решений на базе локальных LLM, оптимизация моделей, векторный поиск, взаимодействие через API.

<br>

| Проект | Описание | Стек технологий |
|:-------|:---------|:----------------|
| [AI Assistant: Индексация и ответы через локальную LLM](https://github.com/AlexandrNizkovskikh/ai-assistant-llm-indexing) | ИИ-помощник для поиска информации по книгам с использованием локальной модели Saiga Mistral 7B и векторных индексов. | Python, Hugging Face Transformers, LlamaIndex, LangChain, FAISS, Saiga Mistral 7B |
| [LLM Tracing with Phoenix](https://github.com/AlexandrNizkovskikh/llm-tracing-with-phoenix) | Трассировка и мониторинг взаимодействия с LLM с помощью Arize Phoenix и OpenTelemetry. | Python, Arize Phoenix, OpenTelemetry, mistralai, NLTK |
| [Dialogue Assistant (Saiga Mistral 7B)](https://github.com/AlexandrNizkovskikh/dialogue-assistant-llm) | Построение диалогового ассистента на базе локальной русскоязычной LLM-модели через PEFT и Transformers. | Python, Transformers, PEFT, Torch |
| [Knowledge Graph Assistant (LlamaIndex + Local LLM)](https://github.com/AlexandrNizkovskikh/knowledge-graph-assistant) | Построение графовой базы знаний и интеграция локальной LLM через PEFT и Gradio для диалогового взаимодействия. | Python, LlamaIndex, Hugging Face, PEFT, Gradio |
| [Tiny Transformer (WebQuestions)](https://github.com/AlexandrNizkovskikh/tiny-transformer-webquestions) | Создание компактной трансформерной модели для обработки вопросов и предсказания ответов. | Python, TensorFlow, TensorFlow Datasets |

---

## Проекты по обработке аудио (Audio Processing)

> Распознавание речи, генерация речи, классификация звуков.

<br>

| Проект | Описание | Стек технологий |
|:-------|:---------|:----------------|
| [Voice Assistant (ASR, LLM, TTS)](#) | Голосовой помощник, объединяющий распознавание речи, генерацию текста через LLM и синтез речи. | Python, Vosk, Hugging Face Transformers, gTTS, FFmpeg |
| [Speech Recognition under Noisy Conditions](#) | Оценка качества распознавания речи на чистых и зашумлённых аудиофайлах с расчётом WER, CER, BLEU, Levenshtein. | Python, SpeechRecognition, pydub, nltk |

---

## Проекты по обработке временных рядов (Time Series Forecasting)
> Прогнозирование данных, анализ временных рядов, предсказание трендов.

<br>

| Проект | Описание | Стек технологий |
|:-------|:---------|:----------------|
| [Stock Price Forecasting (Conv1D)](#) | Прогнозирование котировок акций с помощью сверточной нейронной сети на временных рядах. | Python, TensorFlow, Keras, scikit-learn |

---

## Веб-приложения и интерфейсы для моделей
> Разработка веб-интерфейсов для взаимодействия с ML/AI решениями.

<br>

| Проект | Описание | Стек технологий |
|:-------|:---------|:----------------|
| [Interactive Neural Network Builder](#) | Веб-приложение для загрузки данных, создания нейронных сетей и обучения моделей через интерфейс Streamlit. | Python, Streamlit, H2O, Keras, TensorFlow |

---

## Проекты по генерации музыки и аудио (Music Generation)
> Генерация музыкальных композиций на основе нейронных сетей и синтеза аудио.

<br>

| Проект | Описание | Стек технологий |
|:-------|:---------|:----------------|
| [Classical Music Generation (LSTM)](#) | Генерация классической музыки на основе MIDI-файлов с использованием LSTM-сетей и синтеза аудио. | Python, TensorFlow, Keras, Music21, FluidSynth |

---

## Проекты по усиленному обучению (Reinforcement Learning, RL)

> Обучение агентов через взаимодействие с окружением.

<br>

| Проект | Описание | Стек технологий |
|:-------|:---------|:----------------|
| [DDPG and PPO Implementation](#) | Реализация и сравнение алгоритмов DDPG и PPO в задачах управления в непрерывном пространстве действий. | Python, PyTorch, Gymnasium, Matplotlib |
| [Pac-Man RL Agent (Random Search & Hill Climbing)](#) | Обучение агента играть в Pac-Man на основе стратегий случайного поиска и восхождения на вершину. | Python, Gymnasium, MoviePy |
| [Monte Carlo Control (MountainCar)](#) | Реализация метода Монте-Карло с ε-жадной стратегией в задаче обучения агента в среде MountainCar. | Python, Gymnasium, Torch |
| [Dueling DQN (MountainCar)](#) | Реализация Dueling DQN агента с буфером воспроизведения и ε-жадной стратегией в задаче MountainCar. | Python, Gymnasium, PyTorch |

---

## Проекты по оптимизации нейросетей (Model Optimization)

> Квантизация, прюнинг, дистилляция моделей, ускорение инференса.

<br>

| Проект | Описание | Стек технологий |
|:-------|:---------|:----------------|
| [Hyperparameter Optimization (Genetic Algorithm)](#) | Оптимизация гиперпараметров нейронной сети для классификации изображений с помощью генетического алгоритма. | Python, TensorFlow, Keras, NumPy, Pandas |

---

## Контакты

- 📧 Email: alexandr.nizkovskih@mail.r

---

