# Инструкция для работы с Markdown

## Выделение текста

Чтобы выделить текст курсивом необходимо обрамить его звёздочками (*) или знаком нижнего подчёркивания(_), например _вот так_ или *вот так*

Чтобы выделить текст полужирным, необходимо обрамить его двойными звёздочками (**) или двойным знаком нижнего подчёркивания (__). Например, **Вот так** или __Вот так__

Альтернативные способы выделения текста жирным или курсивом нужны для того, чтобы мы могли совмещать оба этих способа. Например, _текст может быть выделен курсивом и при это быть **полужирным**_

## Списки

Чтобы добавить ненумерованные списки, необходимо пункты выделить звездочкой (*) или знаком (+) Например:
* Элемент 1
* Элемент 2
* Элемент 3
+ Элемент 4

Чтобы добавить нумерованные списки, необходимо пукнты просто пронумеровать. Например:
1. Первый пукнт
2. Второй пункт 
3. Третий пункт

## Работа с изображениями

Чтобы вставить изображение в текст, достаточно написать следующее:
![Google](Google.jpg)

## Ссылки

Существует два варианта оформления ссылок.

1. Для оформления ссылок необходимо выполнить [текст ссылки](адрес ссылки "Необязательное описание"). Например:

[Google](https://www.google.ru/ "нажмёшь сюда и перейдёшь в гугл")



2. Оформление ссылки в виде сноски. Например:
 
 Чтобы оформить сноску необходимо определить её где-нибудь в документе как:
 
  [тег]: ссылка "пояснение" (см.код)

[google]: https://www.google.ru/ "Google"

И оформить изображение как ссылку на сайт. Например:
[![Google](Google.jpg)][google]

## Работа с таблицами

Для того чтобы создать таблицу мы используем (-) и (|) для разделения строк и столбцов. Так же для выравнивания текста необходимо ставить (:) Например:

| Заголовок 1 | Заголовок 2 | Заголовок 3 |
| :-----|:-----:|----:|
|текст|текст|текст|
|текст|текст|текст|
## Цитаты

Для того чтобы использовать цитаты, необходимо поставить знак (>). Можно делать вложеные цитаты(не может превышать больше 15) Например:

>Цитата
>>Цитата
>>>Цитата


