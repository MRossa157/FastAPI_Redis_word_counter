# FastAPI_Reddis_word_counter
Тестовое задание на Python разработчика.

## Задание
Приложение:

предоставляет эндроинт загрузки и отправки построчно в топик брокера сообщений исходных данных вида {"datetime": "15.11.2023 15:00:25.001", "title": "Very fun book", "text": "...Rofl...lol../n..ololo..." } с интервалом 3с

получает исходных данные из топика брокера сообщений

вычисляет количество вхождений буквы "Х" в строках текста из поля "text"

сохраняет результат в БД

предоставляет эндроинт для получения результата из БД в виде [{"datetime": "15.11.2023 15:00:25.001", "title": "Very fun book", "x_avg_count_in_line": 0.012}, {"datetime": "18.01.2023 12:00:25.001", "title": "Other very fun book", "x_avg_count_in_line": 0.032} ]

где x_avg_count_in_line -- среднее значение количества вхождений по каждому из загруженых текстов
