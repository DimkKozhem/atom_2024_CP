# Контроль и управление изменениями в тендерных закупках

## Описание кейса

Мы создали решение для контроля и управления изменениями в тендерных закупках, позволяющее анализировать и сопоставлять требования с использованием локальных моделей LLM. Данное решение включает продвинутые методы обработки текста с применением промптинга, обеспечивая высокую точность в выявлении соответствия между требованиями и спецификациями.

## Преимущества решения

- Использование моделей на CPU и GPU, что позволяет значительно ускорить обработку данных.
- Сокращение времени обработки одной пары документов с 1 минуты на CPU до 4,5 секунд на GPU.

## Запуск

- Для запуска на **GPU** используйте файл `FULL_LAUNCH.ipynb`(итоговое решение).
- Для запуска на **CPU** используйте файл `besline_Atom.ipynb`.
- Разбитие документов на разделы и детекция отедльно по разделам с последующей агрегацией SplitTextBySentence_1_4.ipynb

## Зависимости
В файле requirements.txt перечислены все необходимые зависимости они будут установлены с помощью команды:

```pip install -r requirements.txt```

## Документация 
Документация  расположена в папке ```docs```

## Дополнительная информация

Подробное описание решения доступно по [ссылке](https://docs.google.com/document/d/14I6Dg6L9visXgy657yeqg7ntPKrdW7B3zrYLNjTVPxY/edit?tab=t.0).
