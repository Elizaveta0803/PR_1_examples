# Скраппинг на Python

Этот репозиторий содержит два скрипта Python для извлечения и анализа данных из различных источников: первый скрипт для работы с данными в формате Excel с использованием библиотек `requests`, `pandas` и `openpyxl`, а второй скрипт для парсинга данных из веб-страницы с использованием библиотеки `requests`, `pandas` и `BeautifulSoup`.

## Расположение заданий
Все задания распологаются в этом репозитории в папке `src`. А также в каждом оглавлении по описанию работ встроена ссылка на `Google Colab`.

## Используемые библиотеки:

- `requests`: Для выполнения HTTP-запросов и получения данных с сервера.
- `pandas`: Для работы с данными в форме таблицы.
- `openpyxl`: Для работы с файлами Excel формата .xlsx.
- `BeautifulSoup`: Для парсинга HTML-кода веб-страницы.

## Используемые сервисы
- `Google Colab`: Среда выполнения кода.

## [Первая работа](https://colab.research.google.com/drive/1QA4R8kJdEqUhdybiWGUHX-8BlL8FL_CX?usp=sharing):
### Описание
Данная работа была выполнена по предоставленному примеру.

### Основные шаги:
#### Парсинг данных с веб-страницы:
1. Используется библиотека `requests` для получения HTML-кода веб-страницы.
2. С помощью `BeautifulSoup` происходит парсинг HTML-кода и извлечение нужной информации.
3. Результаты анализа веб-страницы могут быть сохранены или выведены на экран.

#### Работа с API:
1. Выполняется HTTP-запрос к API с использованием `requests`.
2. Полученные данные в формате JSON сохраняются в файл "Sample.json".
3. Данные из файла загружаются обратно и выводятся на экран.

## [Вторая работа](https://colab.research.google.com/drive/1x3-u1Sj7fvyQ76FUFbX_S73ps3k2dYtB?usp=sharing):
### Описание
Этот скрипт осуществляет парсинг данных о бондах с веб-страницы [Smart-lab.ru](https://smart-lab.ru/q/bonds/) с использованием `requests` и `BeautifulSoup`. Он собирает информацию о бондах и сохраняет ее в формате CSV.

### Основные шаги:
1. Загрузка веб-страницы с данными о бондах с помощью библиотеки `requests`.
2. Парсинг HTML-кода с помощью `BeautifulSoup`.
3. Извлечение информации из таблицы на веб-странице.
4. Запись данных в CSV-файл.

## [Третья работа](https://colab.research.google.com/drive/1ZCT1a1xuQC0uv-2aDUvRBBu0mjJhRRoR?usp=sharing):
### Описание
Этот скрипт загружает данные из Excel-файла, предоставленного [Росстатом](https://rosstat.gov.ru), и фильтрует их по определенным критериям. Затем он записывает отфильтрованные данные в два CSV-файла: "Индексы_видов_деятельности_по_ОКВЭД2_в_Российской_Федерации_за_2023г" и "Топ_10_индексов_производства_по_отдельным_видам_экономической_деятельности_по_Российской_Федерации_за_2023г".

### Основные шаги:
1. Загрузка Excel-файла с помощью библиотеки `requests`.
2. Чтение данных из файла с использованием `openpyxl`.
3. Фильтрация и обработка данных с помощью библиотеки `pandas`.
4. Запись результатов в CSV-файлы.

## Возможные трудности:
1. **Изменения формата данных:** Если формат данных в Excel-файле или на веб-странице изменится, потребуется обновление кода для корректной обработки нового формата.
2. **Обработка ошибок:** Необходимо учитывать возможные сбои сети или ошибки при загрузке данных из внешних источников.

Оба скрипта представляют собой примеры использования Python для извлечения, обработки и анализа данных из различных источников.

## Возможные улучшения:

1. **Обработка исключений:** Добавление дополнительной обработки исключений для более точного контроля над ошибками, которые могут возникнуть в процессе загрузки или обработки данных.

2. **Оптимизация скорости:** При работе с большими объемами данных или при парсинге большого количества веб-страниц может потребоваться оптимизация кода для повышения скорости выполнения операций.

3. **Улучшение анализа данных:** Дополнительные шаги по анализу и визуализации данных могут быть полезны для получения более глубокого понимания информации, содержащейся в исходных данных.

4. **Расширение функциональности:** Добавление новых возможностей, таких как автоматизация регулярного обновления данных, интеграция с другими источниками данных или создание интерактивных отчетов.

## Заключение:

Эти скрипты представляют собой примеры использования Python для работы с данными из различных источников. Непрерывное совершенствование и доработка кода помогут обеспечить более эффективную и надежную обработку информации, что может быть полезным для различных проектов и задач анализа данных. Важно также помнить о соблюдении правил использования данных, предоставленных сторонними сервисами, и обеспечении безопасности при работе с внешними источниками данных.
