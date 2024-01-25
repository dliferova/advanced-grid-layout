# Flexible Layout for M.Mind Photo Library

![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)

This project is demo of creating flexible layout for catalog of the store of images "M.Mind" with using Grid.

Main goal of working on a project was to write a column layout that doesn’t explicitly declare the number of rows or columns,
but automatically creates them based on somewhat loose instructions and the provided content.

[Check the demo](https://main--tubular-hamster-122d12.netlify.app)

---

## How to run locally

* install dependencies

```js
npm install
// or
yarn
```
* start local server via Vite
```js
npm run dev
// or
yarn dev
```

---

## Features

- layout's child containers take up all remaining space or adjust to the sizes of their content


- by [using automatic filling]((https://css-tricks.com/snippets/css/complete-guide-grid/#aa-grid-auto-flow)), 
was created the layout where cards of various sizes was placed without empty cells. The browser was handle everything automatically. 


- use function [repeat() combined with keyword auto-fill](https://css-tricks.com/snippets/css/complete-guide-grid/#aa-the-repeat-function-and-keywords). 
"auto-fill" fills the row with as many columns as it can fit. 
So it creates implicit columns whenever a new column can fit, because it’s trying to fill the row with as many columns as it can. 
The newly added columns can and may be empty, but they will still occupy a designated space in the row.

---

## Linkes 

[The Best Complete Guide to CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

[Auto-Sizing Columns in CSS Grid](https://css-tricks.com/auto-sizing-columns-css-grid-auto-fill-vs-auto-fit/)
