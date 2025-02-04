# Header 1
## Header 2
### Header 3
#### Header 4

**bold**
*italic*
_italic_
***bold_italic***

> 1 lvl
>> 2 lvl
>>> 3 lvl
>>>> 4 lvl

`Code` can be written with backticks

```javaScript
function validateName(input){
    const regex = /^[a-zA-Zа-яА-ЯЁё\s]+$/;
    const correctValue = input.value.trim();
    if (correctValue === ''){
        showErrorMsg(input, 'Введите имя')
        return;
     }
    if (regex.test(correctValue) === false) {
        showErrorMsg(input, "Имя должно состоять из букв и пробелов");
        return;
    } 
    closeErrorMsg(input);
    return true;
}
```
```html
<link rel="stylesheet" href="./style/style.scss" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link href="https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300..800;1,300..800&display=swap" rel="stylesheet">
```

list:
+ text1
+ text2
+ text3
  + text3.1 (2 пробела)
  + text3.2

list:
1. text
2. text
3. text
    1. text (4 пробела)
    2. text


- [ ] text
- [X] text done

links: 
https://nodejs.org/en/download

[Node.js](https://nodejs.org/en/download)

Pics:
![Pic](https://images.unsplash.com/photo-1514888286974-6c03e2ca1dba?w=800&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8Y2F0fGVufDB8fDB8fHww, "catpic")

Video:
[![name](link to pic)](link to video)

Tables:
| left | center | right |
|-------|:-------:|:-------|
|text|text|text|


______

# fr-92-Project-JS

Данный проект "fr-92-Project-JS" является учебным и выполнялся командой из шести девушек по окончании курса по JavaScript в онлайн школе программирования ITGirls. Проект реализован на базе данного макета из Figma [Доставка грузов из Китая](https://www.figma.com/design/hMt8UYbzlpJuF1KmWyANU9/10_Cargo?node-id=0-1&p=f&t=6EJxAR9IXSAdYxHo-0) с некоторыми модификациями. Проект был также дополнен конвертером валют, данные для которого через API запрашиваются с ресурса [HexaRate](https://hexarate.paikama.co/).

## Технологии

- [x] HTML/CSS
- [x] Sass
- [x] JavaScript
- [x] NPM package manager
- [x] API

## Использование

После клонирования проекта на компьютер, установите npm-модули с помощью команды:

`npm install`

Запустите проект с помощью команды:

`npm run dev`

и откройте его по ссылке "local".

## Команда проекта

[AnastasiyaNS](https://github.com/AnastasiyaNS)

[Anasteishaa01](https://github.com/Anasteishaa01)

[AnnaTok0811](https://github.com/AnnaTok0811)

[irina1430](https://github.com/irina1430)

[nastyaur1997](https://github.com/nastyaur1997)

[tanakharlamova](https://github.com/tanakharlamova)
