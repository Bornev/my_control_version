# Инструкция по языку MarkDown

## Стилизация текста

Обычный текст набираем как есть.

Новая строка.

### Жирный

Для выделения текста жирным нужно использовать две звёздочки ** или два нижних подчёркивания __

**жирный текст**

### Курсив

Для выделения текста курсивом нужно использовать одну звёздочку * или нижнее подчёркивание _

*Курсив*

### Жирный курсив

Для выделения текста сразу обоими стилями нужно использовать три звёздочки *** или три нижних подчёркивания

***Текст жирным курсивом***

___Текст жирным курсивом___

### Зачёркнутый 

Чтобы зачеркнуть текст, нужно использовать две тильды ~~.

~~Зачёркнутый текст~~

### Подчёркнутый

В синтаксисе Markdown нет встроенного способа подчеркнуть текст. Но если ваш редактор поддерживает HTML, то можно использовать теги:

<u>Подчёркнутый текст</u>


## Цитирование в языке MarkDown

> Первый уровень цитирования
>> Второй уровень

## Списки
### Ненумерованный список 
* Элемент 1
* Элемент 2

### Нумерованный список 
1. Первый элемент нумерованного списка.
2. Второй элемент.

## Web ссылки
Текст [пример ссылки]("http.example."com" "Всплывающая подсказка")

## Картинки 

Изображения в Markdown оформляются по принципу, схожему с принципом оформления ссылкок, только перед квадратными скобками нужно поставить восклицательный знак: ![текст](путь к изображению). Здесь также можно сделать всплывающую подсказку.

![Изображение](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/1920px-Markdown-mark.svg.png "Логотип Markdown")
Также можно вставлять картинки из локального хранилища
![кот](teftelka.jpg "cat")