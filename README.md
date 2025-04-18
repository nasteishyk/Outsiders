# PawMate

**PawMate** — це онлайн-платформа, створена з метою допомогти безпритульним тваринам знайти турботливий дім. Наш сайт об'єднує людей, які прагнуть змінити життя тварин на краще — через волонтерство, донати, усиновлення або поширення інформації.

---

## Основний функціонал

- **Знайти друга**  
  Розділ для перегляду карток тварин із фільтрами за видом, віком, станом здоров’я та типом установи.

- **Знайти дім**  
  Форма для тих, хто хоче передати тваринку до притулку.

- **Стати волонтером**  
  Анкета для охочих долучитися до нашої команди та допомагати безпосередньо.

- **Блог**  
  Інформаційні статті, поради та новини про ініціативи, розіграші та всиновлення.

- **Контакти**  
  Реалізовано як якір у футері головної сторінки (`index.html#contacts`).

---

## Склад проєкту та використані технології

Проєкт складається з кількох взаємопов’язаних HTML-сторінок, які об’єднані спільним дизайном, структурою та стилістикою.

### Структура сайту

- **Головна сторінка (`index.html`)**  
  Містить загальну інформацію про проєкт, модальні вікна для входу та реєстрації, секцію "Про нас" і якір "Контакти".

- **Знайти друга (`find-a-friend.html`)**  
  Сторінка з фільтрами, сіткою карток тварин та формою для запиту.

- **Знайти дім (`find-a-home.html`)**  
  Форма передачі тваринки до притулку.

- **Стати волонтером (`become-a-volunteer.html`)**  
  Форма подачі заявки на волонтерство.

- **Блог (`blog.html`, `blog-read-more.html`)**  
  Розділ із порадами, історіями та інформаційними статтями.

- **Сторінка тварини (`cat-luna.html`)**  
  Приклад персонального профілю тваринки.

### Використані технології

- **HTML5**  
  Семантична розмітка сторінок, адаптована під сучасні браузери.

- **CSS3**  
  Власні стилі із застосуванням:
  - кастомних шрифтів через Google Fonts;
  - декоративних елементів (лапки, фон тощо);
  - гнучких макетів (flex/grid);
  - модальних вікон з розмиттям фону (`backdrop-filter`).

- **Formspree**  
  Для обробки форм без серверної частини (наприклад, подання волонтерських заявок).

- **Відповідальний дизайн**  
  Сторінки адаптовано під різні розміри екранів (десктоп, планшет, мобільні).

---

## Автори

- @nasteishyk — Анастасія  
- @4Alina — Аліна  
- @Sophiks — Софія