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
