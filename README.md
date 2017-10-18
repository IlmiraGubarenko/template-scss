Учебный проект "Личный кабинет"
================================

### Используемые технологии

1. Сборщик проектов  Gulp.js
2. Фреймворк Bootstrap 3
3. Библиотека JavaScript - jQuery
4. scss - предназначен для упрощения создания CSS-кода

### Используемые плагины

1. jquery-ui для создания range slider
2. formstayler для стилизации элементов форм
3. scrollbar для стилизации скролла
4. datepicker - для работы с датами
5. chart - для работы с графиками
6. bpopup - для работы с модальными окнами

### Используемые шрифты и иконки

1. GOOGLE FONT - сервер для работы со шрифтами
2. Сконвертированный шрифт:
* Roboto

### Стандартные компоненты и классы

***Компоненты***
1. Стилизируем заголовки:
```
    .title 
    .page-title
    .section-title
```
2. Стилизируем стандартные кнопки:
```
    .btn-default
    .btn-action
```
3. Стилизируем таблицы:
```
    .table
```
4. Стилизируем списки:
```
    .list
```
5. Стилизируем дефолтные формы и элементы форм:
```
    .checkbox-group
    .form-control
```

***Классы***
1. Создаем флекс контейнеры
```
    .flex-container
```
2. Выравниваем элементы по горизонтали и вертикали:
```
    .justify-content-end
    .justify-content-center
    .justify-content-sb
    .justify-content-sa
    .align-items-center
    .align-items-end
    .flex-grow-default
```
3. Задаем цвет:
```
    .black-bg
    .grey-bg
    .dark-grey-bg
    .light-grey-bg
    .xs-light-grey-bg
    .orange-bg
    .orange-light-bg
    .orange-tab-bg
    .green-bg
    .light-green-bg
    .xs-light-green-bg
    .green-tab-bg
    .red-bg
    .dark-red
    .pink-bg
    .light-pink-bg
    .blue-bg
    .light-blue-bg
```
4. Стилизируем боковую панель
```
    _mobileSidebar
```
---

**Структура папок**

Название папок  | Содержание файла
----------------|----------------------
app             | Директория с готовым проектом
app/css         | Готовые стили к продакшену
app/js          | Готовый js к продакшену
app/img         | Готовые картинки к продакшену
app/fonts       | Шрифты
src             | Директория с исходными файлыми
src/scss        | Исходные стили, здесь мы пишем наши стили и они будут конвертироваться в app/css
src/js          | Исходный js будет минифицироваться и переносится в app/js
src/icons       | Папка для иконок svg

---

**Поставленные задачи для Gulp**
* Минификация css
* Добавление вендорных префиксов в css
* Автоматическое обновление браузера
* Минификация и конкатенация JavaScript
* Оптимизация картинок


