# TWL - (Triple Web Library)

**Таблицы**
![eR0bcrtGmlg](https://user-images.githubusercontent.com/50780255/132317499-7eb4ef2e-6732-4c1b-bba3-6bb195e69b70.jpg)

# GetStarted
*CDN -* 
```html
        <link rel="stylesheet" href="https://raw.githack.com/thepetruha/TWL/main/style.css">
```

*Простой пример того как просто вы можете установить нужные вам столбики*
```html
    <div class="header-tb">
      <span>ID</span>
      <span>Name</span>
      <span>Type</span>
      <span>Delate</span>
     </div>
```

*Для загрузки данных просто через шоблонизатор в цикле выводите данные в "content-tb"
 ВАЖНО! Количество перечисляемых столбиков данных должно совподать с колличеством столбиков в шапке таблици
*
```html
    <div class="scroll-tb">
        <div class="content-tb">
            <span>1</span>
            <span>dfdfdfdfdfdfdffd</span>
            <span>dff</span>
            <span>dfdfdfdfdfdfdffd</span>
        </div>
    </div>
```

*Полный код таблицы*
```html 
   <body>
        <div class="tb">
            <div class="header-tb">
                <span>ID</span>
                <span>Name</span>
                <span>Type</span>
                <span>Delate</span>
            </div>
            <div class="scroll-tb">
                <div class="content-tb">
                    <span>1</span>
                    <span>dfdfdfdfdfdfdffd</span>
                    <span>dff</span>
                    <span>dfdfdfdfdfdfdffd</span>
                </div>
            </div>
        </div>
    </body>
```
