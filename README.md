# rzdtask

Запустить проект: npm run serve
<br>
Получаю 100 строк с открытой апи, поля body и userId не использую
<br>
Тип получаемых данных:
```
[
  {
    "userId": 1,
    "id": 1,
    "title": "title",
    "body": "body"
  },
]
```
Для вывода таблицы сделал компонент Table
<br>
Поиск по таблице осуществляется по полю Title
<br>
Добавление в localStorage не стал делать, по тз этого нет
и смысла в этом тоже нет, там не хранят такое количество данных

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
