# rutube
Краткое описание решения:

Мы представляем модель для перевода речи на видео в речь на иностранном языке. Для решения этой задачи команда использовала алгоритм из нескольких пунктов:

1)Захват звука из видео и его сохранение в отдельный файл

2)Преобразование аудио в текст

3)Перевод текста с использованием системы машинного перевода.

4)Конвертирование переведенного текста в речь.

Технические особенности:

Python, MoviePy, WhisperX, NLLB

Уникальность:

Уникальность нашего решения состоит в том, что вместо создания новых моделей преобразования аудио в текст и его перевода на другой язык, мы использовали уже обученные на это модели, вместо создания и обучения собственных. Это говорит о том, что точность перевода речи на видео в речь на иностранном будет выше, чем у только что созданной модели.
