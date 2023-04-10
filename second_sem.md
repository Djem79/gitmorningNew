# Создание туториала по GIT

## Как создать репозиторий


**Чтобы создать локальный репозиторий напишите следующую команду в терминал:**
```fix
git init
```

## Как добавить файл на отслеживане

**Добавить файл на отслеживание необходимо сделать следующее:

- Прописать команду git add .

** Для фиксации изменений

``` Команда git commit -m "" где в ковычках необходимо обозначить изменения``` 

** Чтобы открыть новую ветку нужно сделать следующее

- Прописать команду git branch
- Для удаления ветки git branch -d и название ветки

** Чтобы преместиться из одной ветки в другую необходимо:

- Прописать git checkout

** Для объединения веток

``` Необходимо прописать git merge```

# Краткое руководство по Маркдауну

## Заголовки


























## Таблицы

В чистом Маркдауне нет синтаксиса для таблиц, а в GFM
есть.

First Header | Second Header
------------- | -------------
Content Cell | Content Cell
Content Cell | Content Cell

Для красоты можно и по бокам линии нарисовать:

| First Header | Second Header |
| ------------- | ------------- |
| Content Cell | Content Cell |
| Content Cell | Content Cell |

Можно управлять выравниванием столбцов при помощи
двоеточия.

| Left-Aligned | Center Aligned | Right Aligned |
|:------------- |:---------------:| -------------:|
| col 3 is | some wordy text | **$1600** |
| col 2 is | centered | $12 |
| zebra stripes | are neat | ~~$1~~ |

Внутри таблиц можно использовать ссылки, наклонный,
жирный или зачеркнутый текст.

Для всего остального есть обычный HTML


## Исходный код
В чистом Маркдауне блоки кода отбиваются 4 пробелами в
начале каждой строки.
Но в GitHub-Flavored Markdown (сокращенно GFM) есть
более удобный способ: ставим по три апострофа (на букве
Ё) до и после кода. Также можно указать язык исходного
кода.
```html
<nav class="nav nav-primary">
  <ul>
    <li class="tab-conversation active">
      <a href="#" data-role="post-count"
class="publisher-nav-color" data-nav="conversation">
        <span class="comment-count">0
комментариев</span>
        <span class="comment-count-
placeholder">Комментарии</span>
</a> </li>
    <li class="dropdown user-menu" data-role="logout">
      <a href="#" class="dropdown-toggle" data-
toggle="dropdown">
<span class="dropdown-toggle-wrapper">
          <span>
            Войти
          </span>
</span>
        <span class="caret"></span>
      </a>
</li> </ul>
</nav> ```
Самое приятное, что в коде не нужно заменять угловые
скобки `< >` и амперсанд `&` на их html-сущности

## Списки
