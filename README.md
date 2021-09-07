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
*Пример как вывести данные в таблицу*
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
_ВАЖНО! Количество перечисляемых столбиков данных должно совподать с колличеством столбиков в шапке таблици_
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
_ВАЖНО! Родительский блок должен быть типа FLEXBOX для корректного отображения всех стилей, а так же обязательным параметром является высота родительского болка, ее можно указывать в ('%', 'hv', 'px' и др)_
____
_Пример родительского блока:_
![2QPnis88tVk](https://user-images.githubusercontent.com/50780255/132330180-606abf4d-9b7a-42a7-864f-8f97c0fe2bd2.jpg)
![WnTSYays7_M](https://user-images.githubusercontent.com/50780255/132330644-c9f27870-4248-440e-a446-859177e09916.jpg)


