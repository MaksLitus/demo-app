##  🚀 Завдання

Головним завданням є створення сторінки з можливістю переглядати інформацію про створіння з серіалу Рік та Морті. Як користувач я повинен мати можливість перегляду всіх створінь, детальну інформацію про обраного персонажа, мати можливість використовувати фільтр, аби швидше знайти конкретного персонажа з усього списку запропонованих. Також мої дії на сайті повинні бути записані в історію, яку я згодом можу переглядати.
<br>

## 📎 Посилання

**Макет**: [Figma](https://www.figma.com/file/OC5G3NeqSS4pZZlHP6BN9Z/New-Test-Incode-2023?type=design&node-id=101-394&mode=design&t=ugycEw1dvyCbuEnn-0)

**API документація**: [Docs](https://rickandmortyapi.com/documentation)

<br>

## 🛠 Технології

⚡️ **Основа**

- ```TypeScript```
- ```React``` 

⚡️ **State менеджер та middleware**

- ```Redux Toolkit```
- ```Redux Thunk```

⚡️ **Роутінг**

- ```React Router```

⚡️ **Робота із запитами**

- ```GraphQL```

⚡️ **Обробка форм (на вибір)**

- ```Formik``` 
- ```React Hook Form```


⚡️ **UI бібліотеки (на вибір)**

- ```Material UI```
- ```Ant Design```

⚡️ **Стилізація (на вибір)**

- ```styled-component```
- ```Стилізація методами вибраної UI бібліотеки``` 
- ```SASS/SCSS/LESS modules```

⚡️ **Валідація та форматування коду**

- ```ESLint``` 
- ```Prettier``` 

> Можете використовувати лише ESLint (для валідації та форматування), або в поєднанні з Prettier.

> Усі бібліотеки мають бути актуальної версії.

<br>

## 👩‍💻 Технічні аспекти

Сайт повинен мати 2 сторінки: **Home** - якиа містить контент, який буде описаний нижче(та промальований в Фігмі), та сторінку детального огляду, на яку ми потрапляємо при натисканні на ім'я створіння. 
На основній сторінці особливу увагу треба приділити списку всіх створінь, фільтру, пагінації на fab.
У правій нижній частині екрану завжди повинен бути Fab, у якому будуть 2 опції: **History** - відкриває Drawer у якому записана історія пошуку с фільтра (записується вона сюди с параметрами, за якими був здійснений пошук), після перезавантаження сторінки данні не повинні зникнути. **Download** - звантажувати .csv файл зі створіннями(лише ті, що знаходяться на конкретній сторінці в пагінації), що потрапили під параметри пошуку фільтру.

Блок з фільтром повинен мати select з параметрами: **Character**, **Location**, **Episode**. Обираючи один із них(або декілька) під блоком з'являються відповідні поля, за якими можемо робити фільтрацію, параметри для кожного з розділів select можна побачити у документації. Та наприкінці повинна знаходитися кнопка пошуку, яка розпочне запит на отримання створінь, та запише критерії пошуку(лише ті, які були заповнені) в історію.

При натисканні на ім'я створіння повинен бути перехід на іншу сторінку з детальним описом цього персонажу, яку саме інформацію про нього виводити ви можете обрати самі. Також ця дія повинна бути записана до історії. Буде достатньо "Передивився інформацію що до ***ім'я персонажу***". Також на сторінці детального виду кнопка **Download**, що знаходиться в Fab повинна бути неактивна.
 
Всі запити роблять через Rest api документації, та обов'язково з використанням redux.
<br>


## 📌 Порядок виконання завдання

* Виконайте завдання з використанням технологій та дотриманням усіх пунктів описаних вище
* Розмістить виконанне тестове завдання у своєму git репозиторії (є гарною практикою робити комміти частіше, ніж один за все виконання 😉).
* Зробіть деплой виконаного проекту. Можна використати GitHub або Firebase, але список цим не обмежений. (Цей пункт не обовʼязковий, але буде плюсом)
* Повідомте про виконання завдання, та надайте посилання на git репозиторій та лінку на задеплоєний проект (якщо цей пункт було виконано)

🖥  Happy hacking!
