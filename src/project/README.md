# Проект

Необходимо реализовать telegram-бота, которому пользователь может отправить текст статьи, а в ответ получить краткое содержание (summary) и картинку, сгенерированную на основе статьи.
- У пользователя должна быть возможность с помощью клавиатуры выбрать вариант составления summary: краткое или подробное
- У пользователя должна быть возможность с помощью клавиатуры выбрать стиль картинки: рисунок, реалистичный, черно-белый

Пример работы с ботом:
```
Бот: Привет! Пришли мне текст статьи
Пользователь: <text>
Бот: [Краткий пересказ] [Подробный пересказ]
Пользователь: [Краткий пересказ]
Бот: Выбери стиль картинки [Рисунок] [Реалистичный] [Черно-белый]
Пользователь: [Реалистичный]
Бот: <result>
```

### Дополнительные задания

- Вместо текста пользователь может прислать ссылку на статью
- Вместе с пересказом и картинкой, бот должен прислать набор тегов (тем), к которым относится статья. Для реализации этой задачи нужно воспользоваться классификатором (https://yandex.cloud/ru/docs/foundation-models/concepts/classifier/)