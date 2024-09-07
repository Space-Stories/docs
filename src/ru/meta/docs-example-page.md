# Пример разметки

Эта страница используется для демонстрации плагинов и стилей, доступных в этом `mdbook` экземпляре.

Лучше всего просмотреть исходный исходный код этой страницы, что вы можете сделать, используя кнопку в правом верхнем углу и нажав «Код» вместо «Предварительный просмотр» на GitHub.

## Разметка

Лучше всего посмотреть [общее руководство по разметке](https://www.markdownguide.org/getting-started/) для этого! Там много.

**жирный шрифт**

*курсив*

~~зачеркивание~~

## Шаблоны

Вы также можете передать аргументы в вызов шаблона, которые интерполируются на страницу с помощью `mdbook-template`. Изучите [их документация](https://github.com/sgoudham/mdbook-template#format) для получения дополнительной информации.

`\{\{#template {ссылка на шаблон}\}\}`

{{#template ../templates/outdated.md}}

{{#template ../templates/wip.md}}

{{#template ../templates/stub.md}}

## Предупреждения

Все доступные типы предупреждений.

Чтобы использовать предупреждение:
``````
```admonish {тип} "{текст или пусто}"
описание
```
``````

```admonish note
```

```admonish abstract
```

```admonish info
```

```admonish tip
```

```admonish success
```

```admonish question
```

```admonish warning
```

```admonish failure
```

```admonish danger
```

```admonish bug
```

```admonish example
```

```admonish quote
```

## latex

\\[ \mu = \frac{1}{N} \sum_{i=0} x_i \\]

## mermaid

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
