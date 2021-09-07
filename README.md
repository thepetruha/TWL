# TWL - (Triple Web Library)

**Таблицы**
![eR0bcrtGmlg](https://user-images.githubusercontent.com/50780255/132317499-7eb4ef2e-6732-4c1b-bba3-6bb195e69b70.jpg)

# Get Started
*CDN - вставте данный тег со свойствами в тела документа HTML* 
```html
        <link rel="stylesheet" href="https://raw.githack.com/thepetruha/TWL/main/style.css">
```
____

*Простой пример того как просто вы можете установить нужные вам столбики*
```html
    <div class="header-tb">
      <span>ID</span>
      <span>Name</span>
      <span>Type</span>
      <span>Delate</span>
     </div>
```
____
*Для загрузки данных просто через шоблонизатор в цикле выводите данные в "content-tb"*
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
__ВАЖНО! Количество перечисляемых столбиков данных должно совподать с колличеством столбиков в шапке таблици__
____
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
__ВАЖНО! Родительский блок должен быть типа FLEXBOX для корректного отображения всех стилей, а так же обязательным параметром является высота родительского болка, ее можно указывать в ('%', 'hv', 'px' и др)__
![HnYwcDdj5qg](https://user-images.githubusercontent.com/50780255/132329968-3761a12b-3de2-4b7f-8891-cfbf7f3fb17e.jpg)
![_wwe4cV2ao0](https://user-images.githubusercontent.com/50780255/132329980-70915cfd-6405-4ace-b20c-fdc5b9b7ffb5.jpg)

