# Mon Vieux Grimoire

## Comment lancer le projet ?

### Avec npm

Faites la commande `npm install` pour installer les dépendances puis `npm start` pour lancer le projet.

Le projet a été testé sur node 19.

## Structure du projet

```
.
├── .eslintrc.json
├── .gitignore
├── Dockerfile
├── README.md
├── babel-plugin-macros.config.js
├── package-lock.json
├── package.json
├── backend
│   ├── .env
│   ├── app.js
│   ├── package-lock.json
│   ├── package.json
│   ├── server.js
│   ├── controllers
│   │   ├── book.js
│   │   └── user.js
│   ├── images
│   │   ├── gabon-flag-grunge-texture-260nw-2085087193.webp1755513810176.undefined
│   │   ├── images_(3).png1755513967708.png
│   │   ├── teÌ leÌ chargement_(3).jpeg1755220536389.jpg
│   │   ├── teÌ leÌ chargement_(3).jpeg1755514204038.jpg
│   │   └── terrain1_jsl.jpeg1755514101469.jpg
│   ├── middleware
│   │   ├── auth.js
│   │   └── multer-config.js
│   ├── models
│   │   ├── Book.js
│   │   └── User.js
│   └── routes
│       ├── book.js
│       └── user.js
├── public
│   ├── favicon.ico
│   ├── index.html
│   ├── logo192.png
│   ├── logo512.png
│   ├── manifest.json
│   └── data
│       └── data.json
└── src
    ├── App.css
    ├── App.jsx
    ├── App.test.js
    ├── index.css
    ├── index.js
    ├── logo.svg
    ├── reportWebVitals.js
    ├── setupTests.js
    ├── components
    │   ├── BackArrow
    │   │   └── BackArrow.jsx
    │   ├── Books
    │   │   ├── BestRatedBooks
    │   │   │   ├── BestRatedBooks.jsx
    │   │   │   └── BestRatedBooks.module.css
    │   │   ├── BookForm
    │   │   │   ├── BookForm.jsx
    │   │   │   └── BookForm.module.css
    │   │   ├── BookInfo
    │   │   │   └── BookInfo.jsx
    │   │   ├── BookItem
    │   │   │   ├── BookItem.jsx
    │   │   │   └── BookItem.module.css
    │   │   └── BookRatingForm
    │   │       ├── BookRatingForm.jsx
    │   │       └── BookRatingForm.module.css
    │   ├── Footer
    │   │   ├── Footer.jsx
    │   │   └── Footer.module.css
    │   ├── Header
    │   │   ├── Header.jsx
    │   │   └── Header.module.css
    │   └── ScrollToTop
    │       └── ScrollToTop.jsx
    ├── images
    │   ├── Logo.png
    │   ├── Logo.svg
    │   ├── add_file.png
    │   ├── book_add.jpg
    │   ├── book_delete.png
    │   ├── home_banner.jpg
    │   └── map_footer.png
    ├── lib
    │   ├── common.js
    │   ├── customHooks.js
    │   └── functions.jsx
    ├── pages
    │   ├── AddBook
    │   │   ├── AddBook.jsx
    │   │   └── AddBook.module.css
    │   ├── Book
    │   │   ├── Book.jsx
    │   │   └── Book.module.css
    │   ├── Home
    │   │   ├── Home.jsx
    │   │   └── Home.module.css
    │   ├── SignIn
    │   │   ├── SignIn.jsx
    │   │   └── SignIn.module.css
    │   └── updateBook
    │       ├── UpdateBook.jsx
    │       └── UpdateBook.module.css
    └── utils
        └── constants.js
