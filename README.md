[<img src="https://img.shields.io/badge/made%20by-Nightmare-blue" align="right"/>](https://github.com/qnightmare/)
___
## [<img src="https://img.shields.io/badge/⁘-Lesson%201-green" height="30" />](https://github.com/qnightmare/today-i-lerned/edit/main/README.md#lesson-1)  [![Typing SVG](https://readme-typing-svg.herokuapp.com?color=F7F7F7&background=3499D4&vCenter=true&width=750&height=30&lines=+~+Main+git+command)](https://git.io/typing-svg)
  `git config --list` - виводить список настройок *git*  
  `git config user.name` - додає імя користувача з *github*  
  `git config user.email` - додає email з *github*  
  `git config --global credential.helper cache` - кешує облікові данні  
  `git log --all --graph --oneline --decorate` - показує історію комітів по всіх гілках  
  --- `-p` - відображає зміни в кожному файлі  
  `git init`        - ініціалізація репозиторію в поточній папці  
  `git status`      - відображає стан файлів (змінені чи не змінені, чи є untruck файли і тд)  
  `git add <name>`  - додає файл для відстеження git  
  `git add .`       - додає всі файли у папці для відстеження в git. Обережно, може додати лишнього, якщо нема файлу git ignore  
  `git rm dirname/somefile.js` - видаляє файл і індекс  
  `git rm dirname/*.html` - видаляє фали по масці  
  `git mv dir1/somefile.js dir2` - переміщує або переіменовує, по анології з терміналом  
  `git diff` - показує різницю  
  `git diff --staged` - показує підготовлені зміни  
  `git show <hash>` - перегляд коміта  
   `git commit -m "<commit name>"` - зберігає файл у git зі змінами як поточний  
  `git branch`      - створює нову паралельну гілку (бранч) з файлами  
  `git branch -d existing_branch_name` - видаляє гілку після злиття, зі збереженням історії. флаг `-D` - видаляє примусово незвертаючи уваги на конфлікти  
  `git branch -a` - списов видалених гілок  
  `git checkout <name>` - вказує з якою гілкою (бранчем) ми хочемо працювати  
  `git checkout -b <branch-name>` - створює нову гілку і одразу переходить на неї  
  `git revert <hash>` - віткатує проект до цього коміта і створює новий коміт. Але можна це виконати лише з останнім комітом  
  `git merge <name>` - вказує з якою гілкою (бранчем) ми хочемо працювати  
  `git merge --abort` - у випадку конфлікту відміняє мерж і відновлює файли  
  `git merge existing_branch_name` - злиття двох гілок  
  `git merge --no-ff existing_branch_name` - створить комміт злиття двох гілок 
  --- `--graph` - видає графік в форматі ASCII, що відображає структуру розгалуження історії комітів. В поєднанні з флагами `--oneline` i `--decorate`спрощує розуміння того, до якої гілки відноситься кожен комміт  
  `git rebase <name>` - переміщує один коміт в інший  
  `git remote add <name> <url>` - зтворює нове підключення до віддаленого репозиторію  
  `git remote -v` - Список віддалених подключень до інших репозиторіїв включаючи їх URL адреси *(команда синхронізації)*  
  `git fetch <remote>` - завантажує всі файли і комміти і гілки з віддаленого репозиторію в локальний  
  `git fetch origin foo` - git піде у віддалену гілку foo, візьме всі коміти, яких немає локально і закине в локальну гілку o/foo.  
  `git push https://<GITHUB_ACCESS_TOKEN>@github.com/<GITHUB_USERNAME>/<REPOSITORY_NAME>.git` - відправка у віддалений репозиторій  
  `git push -u origin new_branch` - Передати нову гілку в віддалений реозиторій, вказавши імя репозиторію і імя локальної гілки  
  `git push --delete origin existing_branch` - видалити гілку у віддаленому репозиторії  
  `git pull <remote_name>.git` - завантаження з віддаленого репозиторію  
      --- `--verbose` - відображає детальну інформацію по завантажених файлах  
  `git checkout <назва гілки> HEAD^` - переходить на попередній коміт відносно поточного (чим більше символів `^` тим вище по гілці ми перемістимося. Замість HEAD можна використати назву бранчу.  
  `git checkout <назва гілки> HEAD~4` - замінить команду `git checkout <назва гілки> HEAD^^^^` - це потрібно у випадку якщо потрібно піднятися на багато кроків в гору по гілці  
  `git checkout -b <назва локальної гілки що стежить за віддаленою main> o/main` - ?           Інший спосіб вказати за якою віддаленою гілкою слідкувати -- просто використовувати опцію git branch -u `git branch -u o/main foo`
  `git push origin main` буквально перекладається як: Піди в гілку, що називається "main" в моєму репозиторії, візьми всі коміти, піди у віддалений "main", що називається "origin". Додай ті коміти, яких немає в цій гілці і надрукуй, що саме ти зробив.  
  `git remote show origin` - відображає детальну інформацію про віддалений репозиторій  
  `git reset` - відновлює файли при конфлікті злиття до стабільного стану  
  `git push origin <source>:<destination>` - Для того, щоб в одному аргументі <place> вказати і місце звідки і куди, треба їх просто розділити двокрапкою:  
  > У *VS Code* при редагуванні підключених до *git* файлів зеленим кольором позначаються нові стрічки, а синім стрічки в яких відбулися зміни. Червоним позначаються видалені
  ---

## [<img src="https://img.shields.io/badge/⁘-Lesson%202-green" height="30" />](https://github.com/qnightmare/today-i-lerned/edit/main/README.md#lesson-2) [![Typing SVG](https://readme-typing-svg.herokuapp.com?color=F7F7F7&background=3499D4&vCenter=true&width=750&height=30&lines=+~+Main+terminal+command,+start+github)](https://git.io/typing-svg)
### *Термынальні команди*  
  `cd <name>` - перехід до каталогу що знаходиться в поточному каталозі  
  `cd </name/name1...>` - перехід до каталогу за певним шляхом  
  `cd` - перехід до домашнього каталогу  
  `..` - перехід на каталог вище  
  `ls`             - список файлів у папці  
  `ls -a`           - список файлів у папцІ, включаючи приховані  
  `tree`           - структура файлів і папок  
  `mkdir <name>` - створити директорію в поточному каталозі  
  `touch <name.***>` - створити файл *(.\*\*\* - розширення файлу)*  
  `cp <name.***> <name2.***>` - копіює файл *name.\*\*\** в поточний каталог з назвою *name2.\*\*\**  
 --- `./<name.***>` - поточний каталог  
---  `../<name.***>` - каталог вище  
`mv <name.***> ../<name.***>` - перемістити файл на каталог вище  
`cat > imiafaila.txt` - створює файл і дозволяє писати в нього інформацію прямо з консолі  *CTRL+D* - закінчує редагування
`cat imiafaila.txt` - дозволяє побачити вміст файлу  
`cat filename.txt | more` - перегляд великих файлів  
--- також командою `cat` можна обєднувати два файли  

## [<img src="https://img.shields.io/badge/⁘-Lesson%203-green" height="30" />](https://github.com/qnightmare/today-i-lerned/edit/main/README.md#lesson-2) [![Typing SVG](https://readme-typing-svg.herokuapp.com?color=F7F7F7&background=3499D4&vCenter=true&width=750&height=30&lines=+~+HTML+base+command)](https://git.io/typing-svg)
### *Мінімальний набір плагінів VS Code*  
  - Auto Close Tag  
  - Auto Rename Tag  
  - EditorConfig for VS Code  
  - Highlight Matching Tag  
  - HTML Preview  
  - Live Server  

### *Структура HTML документа:*
  ```HTML
  <!DOCTYPE html>  
  <html>  
  <head>  
  <title>  
  <bod>
  ```
### *Коментарі в HTML*  
  - \<\!-- текст коментаря --\>  
  ### *Основні елементи HTML*  
  `<input>` - поле вводу  
  `<div>` - універсальний контейнер для потокового контенту  
  `<h1>-<h6>` - заголовки документу. Можуть використовуватися тільки 1 раз на сторінку. Використовуються парсером пошукувика для визначення головної інформації при пошуку  
  `<a>` - створення посилання або якоря  
  `<span>` - основний рядковий контейнер, використовується для групування елементів тексту в цілях стилізації  
  `<img>` - визначає зображення  
  `<ul>` - неномерований список  
  `<ol>` - нумерований список  
### *Семантика:*  
  `<main>` - Призначений для основного вмісту документу. Вміст повинен бути унікальним, і не включати типові блоки як от \<header\>, \<foter\>, \<nav\>, \<aside\>, форми пошуку і тд.  
  `<section>` - Задає розділ документа, може застосовуватися для блоку новин, контактної інформації, розділів тексту, вкладок у діалоговому вікні та ін. Розділ зазвичай містить заголовок. Допускається вкладати один елемент <section> (від англ. section - розділ) всередину іншого  
  `<menu>` - виступає контейнером для тега <command> та створення меню  
  `<aside>` - є частиною документа, чий вміст лише опосередковано пов'язані з основним вмістом документа. Найчастіше представлений у вигляді бічної панелі, виносок або міток  
  `<nav>` - визначає окрему секцію документа, призначення якої позначення посилань навігації (як усередині поточного документа, і ведучих іншу сторінку). Як приклад такої секції можна навести меню, якірні посилання  
 ### *Універсальні атрибути:*
  `accesskey` - дозволяє отримати доступ з допомогою сполучення клавіш  
  `class` - визначає імя класу, яке дозволяє повязати тег зі стильовим оформленням  
  `contenteditable` - повідомляє, що елемепнт доступний для редагування користувачем  
  `contextmenu` - встановлює контекстне меню для елементу  
  `dir` - вказує напрямок тексту (з ліва на право чи навпаки)  
  `hidden` - приховує вміст елементу від перегляду  
  `id` - вказує імя стильового ідентифікатора  
  `lang` - браузер використовує значення цього параметру для правильного відоюраження національних символів  
  `spellcheck` - вказує браузеру проводити перевірку граматики і правопису чи ні  
  `style` - застосовується для визначення стилю елементу за допомогою CSS  
  `tabindex` - вказує порядок отримання фокусу при переході між елементами за бопомогою клавіші TAB  
  `title` - описує вміст документу у вигляді спливаючої підказки  
  
  
  
## [<img src="https://img.shields.io/badge/⁘-Lesson%204-green" height="30" />](https://github.com/qnightmare/today-i-lerned/edit/main/README.md#lesson-2) [![Typing SVG](https://readme-typing-svg.herokuapp.com?color=F7F7F7&background=3499D4&vCenter=true&width=750&height=30&lines=+~+Main+terminal+command,+start+github)](https://git.io/typing-svg)
### *CSS*  
  ul {
    -webkit-column-count: 3;
    -moz-column-count: 3;
    column-count: 3;
}
    
    `transition: <property> <duration> <timing-function> <delay>;`
  
```HTML
<p> fff</p> 
```

___
[<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/github.svg' alt='github' height='40'>](https://github.com/https://github.com/qnightmare)  [<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg' alt='linkedin' height='40'>](https://www.linkedin.com/in/https://www.linkedin.com/in/volodymyr-vysotskyi/)  
