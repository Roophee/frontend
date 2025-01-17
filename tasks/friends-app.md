[![MIT Licensed][icon-mit]][license]
[![Awesome][icon-awesome]][awesome]
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![Telegram][icon-chat]][chat]

# Friends App

Створіть невеличку сторінку пошуку друзів у соціальних мережах з картками користувачів,
пошуком, сортуванням та фільтрацією їх за віком, прізвищем, ім'ям,
або чим завгодно, за допомогою [Random User API](https://randomuser.me) :)

## Приклади

Це *приклад*. Ви повинні стилізувати свою програму так, як хочете.

Зробіть це особистим. Зробіть це красивим. Зробіть це ідеальним, а потім пишайтеся тим, що ви зробили.

![image](https://i.imgur.com/5tcpqcY.png)

Реалізуйте наведені нижче приклади користування.

## Як користувач, я хотів би

- бачити список карток користувачів на сторінці, картки повинні бути гарно стилізовані з фотографією користувача, ім'ям, віком, номером телефону, можливо, з іншою інформацією користувача, яку ви бачите в інформаційній картці юзера
- шукати, ввівши ім’я в поле пошуку, і одразу побачити фільтрацію на сторінці
- сортувати картки за іменем/віком та за алфавітом (A-Z/Z-A)
- фільтрувати друзів за віком, іменами, будь-якими іншими параметрами
- бачити модні іконки та крутий дизайн з тінями, градієнтами, жовтим шрифтом на синьому фоні тощо. Використання шаблону цілком прийнятне

## Якщо ви відчуваєте, що можете зробити роботу краще - зробіть

Зауважте, що це додаткова частина завдання. Ви можете реалізувати будь-що зі списку нижче.

### Будьте як Дуров і

- додайте пагінацію до прокручування
- сортуйте не тільки за прізвищем і віком, а й за датою реєстрації
- фільтруйте за місцем розташування та електронною поштою
- створить гарний дизайн, який підходить для мобільних пристроїв - responsive/fluid/elastic/будь-що
- використовуйте async/awaits для обробки асинхронних дій

### Будьте як Цукерберг і

- додайте підтримку адресного рядка, що означає, що користувач повинен бачити стан фільтрів і сортування в URL
- використовуючи свої знання ООП, розділіть свій додаток на різні частини, наприклад: `FriendsList`, `FiltersContainer` тощо.
- за допомогою модулів ES6 створіть веб-сайт на основі frontend-компонентів

## Ви можете

- використовувати всі `Array.methods`, які ви знаєте :)
- спробувати розібратися з асинхронною інкапсуляцією даних у request/response. Спробуйте логіку callbacks у дії
- зрозуміти різницю між синхронними та асинхронними network запитами
- дізнатися параметри та запити в дії
- використовувати `fetch` та/або `XMLHttpRequest`. Але *НЕ* jQuery. Поганий jQuery, поганий! Ніхто не любить jQuery!`¯\_(ツ)_/¯`
- зрозуміти плюси і мінуси імутабельності даних на прикладі копій масивів
- спробувати key/mouse events форм, керувати ними, вмикати та вимикати їх

## Речі, які вам допоможуть

- Ми вважаємо, що для цього завдання вам потрібно буде використовувати promises ;)
- [Основы XMLHttpRequest](https://learn.javascript.ru/xmlhttprequest) - ви
  можете використовувати `XMLHttpRequest` для надсилання запитів на веб-сервер;
  [Method Fetch замена XHR](https://learn.javascript.ru/fetch) - Ви можете використовувати `fetch` як кращий інструмент для надсилання запитів.
- [Randomuser api with awesome simple examples and docs](https://randomuser.me) -
  _ви можете використовувати один із цих API для отримання даних для вашого веб-сайту_;
- [URL API](https://developer.mozilla.org/en-US/docs/Web/API/URL) - ви можете використовувати
  це для роботи з URL;
- Подивіться на  [Array methods on learn.javascript.ru](https://learn.javascript.ru/array-methods) і на [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)
- [Manipulating the browser history](https://developer.mozilla.org/en-US/docs/Web/API/History_API) -
  ви повинні знати, як працювати з історією браузера.

Коли ви завершите завдання, пушніть свій код у репозиторію GitHub і опублікуйте
його використовуючи [GitHub Pages](https://pages.github.com).

Після завершення виконайте наступне:
1. Для цього завдання вам знадобиться review коду:
   - Для студентів курсу **Frontend 2022**: будь ласка, дотримуйтесь [цих інструкцій](https://github.com/kottans/frontend-2021-homeworks/blob/master/README.md)
   - Для студентів **p2p course**: будь ласка, дотримуйтесь [цих інструкцій](https://github.com/kottans/frontend-2019-p2p/blob/master/CONTRIBUTING.md)
1. Чудова робота! Діліться своїми досягненнями з іншими –
   опублікувати повідомлення в [course channel][chat]:
   `Friends App — #done` (або `Friends App — #p2p_done` якщо ви студент курсу p2p) і додайте посилання до свого репо. **Цей крок важливий, оскільки він допомагає наставникам відстежувати ваш прогрес!**

## Готово?

__Congratulations! 🎉__

- [ ] Ви виконали всі обов’язкові завдання?
- [ ] Перевірені практичні завдання та
      PR змержені в
      [frontend-2021-homeworks](https://github.com/kottans/frontend-2021-homeworks)
      repo `master`?

Ви закінчили __Stage 0__ курсу!

Розмістіть святкову наклейку або танцювальний GIF
у [course channel][chat].

... і ще невелика річ.
[Вкажіть себе серед тих, хто закінчив Stage 0 курсу](../students/stage0-finishers.md).

⤴️ Повернутися до [Contents](../contents.md)


[icon-chat]: https://img.shields.io/badge/chat-on%20telegram-blue.svg
[icon-mit]: https://img.shields.io/badge/license-MIT-blue.svg
[icon-awesome]: https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg

[license]: https://github.com/Kottans/web/blob/master/LICENSE.md
[awesome]: https://github.com/sindresorhus/awesome#front-end-development
[chat]: https://t.me/joinchat/CX8EF1JmLm9IM6J6oy2U7Q
