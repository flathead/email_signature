### Шаблон письма

На основе [Responsive HTML Email Signature](https://github.com/danmindru/responsive-html-email-signature).

Исходники хранятся в папке **templates/**.
Для редактирования достаточно изменить файл **conf.json**, содержащий в себе текстовые константы.

Скомпилированные файлы, готовые в использованию, находятся в папке **dist**.

Например, код подписи шаблона _hodie_ находится по пути `dist/hodie/signature-hodie.html`, а код всего письма шаблона _leesora_ - по пути `dist/leesora/full-mail-leesora.html`.

---

Установка зависимостей:

```
npm install
```

Запуск разработки с отслеживанием изменений:

```
npm start
```

Скомпилировать единожды:

```
npm run once
```
