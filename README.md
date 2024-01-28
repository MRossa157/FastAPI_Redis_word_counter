# FastAPI_Redis_word_counter
Тестовое задание на Python разработчика.

## Задание
Приложение:

предоставляет эндпоинт загрузки файла

вычисляет количество вхождений буквы "Х" в строках текста

сохраняет результат в БД (Redis)

предоставляет эндпоинт для получения результата из БД в виде [{"datetime": "15.11.2023 15:00:25.001", "title": "Very fun book", "x_avg_count_in_line": 0.012}, {"datetime": "18.01.2023 12:00:25.001", "title": "Other very fun book", "x_avg_count_in_line": 0.032} ]

где x_avg_count_in_line -- среднее значение количества вхождений по каждому из загруженых текстов
