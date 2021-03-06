# Классификация музыкальных композиций по жанру
Целью данного пректа явлется создание модели, способной с хорошей точностью определить музыкальный жанр композиции. Обучение происходит на датасете GTZAN, где 10 популярных музыкальных жанров представлены композициями по 30 секунд, помимо самих композиций имеются спектрограммы и статистические данные для композиции целиком и для трехсекундных кусочков.

## Структура проекта:
* папка CNN: содержит ноутбуки с обучением модели CNN. 
В ноутбуке CNN_GTZAN_preprocessing описаны шаги предобработки данных, в ноутбуке CNN_GTZAN_experiments - обучение самой модели.
* папка Baseline: содержит ноутбуки с обучением базовых моделей (kNN, SVM, CatBoost). Есть два ноутбука с данными по разным длинам последовательностей, в котором содержатся примеры работы алгоритмов с seed=42, построены графики и выведенны названия файлов, классифицированных неправильно. В третьем - подсчет усредненных метрик для разных seed.
* папка RNN: содержит ноутбук с RNN моделью и примером обучения.
 ### Ссылка на датасет:
 https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification
