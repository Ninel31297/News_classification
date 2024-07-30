Проект: ТГ-бот определения категории новости по её тексту, предоставленному пользователем
Ссылка на бота: 

Описание
Этот проект посвящен созданию и обучению языковой модели n-gram и последующего использования этой модели для многоклассовой классификации текстов новостей по категориям.

Моделирование
Было реализовано 4 разных варианта языковой модели:
- unigram
- unigram_bigram
- bigram
- trigram

Создание ТГ-бота
Используем библиотеку aiogram (ver. 3.10.0)
Основные команды:
/start- Вывести приветственное сообщение с описанием команд бота
/model - Вывести список доступных моделей в виде кнопок. Доступные модели ('unigram', 'unigram_bigram', 'bigram', 'trigram')
/generate - Отдать тэг для отправленной в бот новостной статьи
/checkmodel - Вывести загруженную в данный момент модель
/help - Вывести список доступных команд
