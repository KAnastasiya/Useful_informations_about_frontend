# Awesome CSS

1. [Видео-уроки (Sorax)](https://www.youtube.com/watch?v=IsZDtOYUWvk&list=PL026CCEB5125879C2 )
2. [Основы CSS (видео уроки от loftblog)](http://loftblog.ru/material/osnovy-css-urok-1/)
3. [Цикл статей (webref)](https://webref.ru/layout/magic-of-css)
4. [Учебник CSS3 (professorweb)](http://professorweb.ru/my/css/css_theory/level1/css_index.php)
5. [Интерактивные уроки (codeacademy)](https://www.codecademy.com/en/tracks/web)
6. [Интерактивные уроки (htmlacademy)](https://htmlacademy.ru/courses)
7. [D.Makfarland - Большая книга CSS3](https://vk.com/doc10903696_289804774?hash=bf04f3e08c8247c82f&dl=23b84e66991136fa80)
8. [Уроки по HTML и CSS](https://webref.ru/layout/learn-html-css)
9. [HTML5 и CSS3 на примерах](https://webref.ru/layout/html5-css3)
10. [Как верстать на HTML5 и CSS3](https://webref.ru/layout/howtocodeinhtml)
12. [HTML & CSS is hard. A friendly web development tutorial for complete beginners](https://internetingishard.com/html-and-css/)
13. [Изучаем css-селекторы в игровой форме](https://flukeout.github.io/)
14. [Псевдоселекторы в CSS3](https://www.youtube.com/watch?v=kdH-MscuiU8)
15. [8 CSS selectors DO’s and DON’Ts](https://medium.com/@aljullu/8-css-selectors-dos-and-don-ts-1e0d23fcf96c)
16. [CSS Selectors from CSS4 till CSS1](http://css4-selectors.com/selectors/)
17. Позиционирование (geekbrains): [часть 1](https://geekbrains.ru/events/203) и [часть 2](https://geekbrains.ru/events/214)
18. [Модульные сетки в HTML/CSS](https://www.youtube.com/watch?v=f2ypR_-4ka0)
19. [Изучение CSS Разметки](http://learnlayout.com/)

======

### Справочники
1. [cssreference.io](http://cssreference.io/?utm_source=forwebdev&utm_medium=announcement&utm_campaign=css-reference--shpargalka-po-rasprostranyo)
2. [webref.ru](https://webref.ru/css)
3. [w3schools.com](http://www.w3schools.com/css/css_rwd_viewport.asp)
4. [codrops](https://tympanus.net/codrops/css_reference/) 

======

### Сброс/нормализация стилей
1. [Normalize.css](https://github.com/necolas/normalize.css/) - приведение стилей всех элементов к единому отображению во всех браузерах
2. [Reset CSS](http://meyerweb.com/eric/tools/css/reset/) - полный сброс стилей для всеъ элементов
**Примечание:** *более предпочтителен 1-ый вариант*

======

### Float-ы
1. [Все о Float](http://softwaremaniacs.org/blog/2005/12/01/css-layout-float/)
2. [Очистка float-ов (clearfix)](http://webformyself.com/ochistka-plavayushhix-elementov-obzor-razlichnyx-metodov-clearfix/)
3. [Варианты «clearfix-хака» и его замен: сводная таблица](http://css-live.ru/articles-css/clearfix-block-formatting-context-methods-cheatsheet.html)
4. [The very latest clearfix reloaded](http://cssmojo.com/the-very-latest-clearfix-reloaded/)

======

### Flexbox
1. [Что такое Flexbox? (html5.by)](http://html5.by/blog/flexbox/)
2. [Полное руководство (frontender)](http://frontender.info/a-guide-to-flexbox/)
3. [Полное руководство по Flexbox (TuHub)](https://tuhub.ru/frontend/flexbox-complete-guide/ )
4. [Визуальное руководство (css-live)](http://css-live.ru/articles/vizualnoe-rukovodstvo-po-svojstvam-flexbox-iz-css3.html)
5. [A Complete Guide to Flexbox (css-tricks)](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
6. [Видео-уроки от loftblog](http://loftblog.ru/material/flexbox-css3-1-flexbox-na-praktike/)
7. [Flexbox (CodeDojo)](https://www.youtube.com/watch?v=7Lg-438gAc8&list=PLqHlAwsJRxAPs942EdJ1akeWpOg2yatiM&index=1)
8. [Flex cheatsheet (yoksel)](http://yoksel.github.io/flex-cheatsheet/)
9. [Интерактивная игра для изучения flexbox (flexboxfroggy)](http://flexboxfroggy.com/)
10. [Веселое изучение flexbox (flexbox-game)](https://preview.webflow.com/preview/flexbox-game?preview=d1a26b027c4803817087a91c651e321f&m=1)
11. [Flexbox game (flexboxdefense)](http://www.flexboxdefense.com/)
12. [Как сделать sticky footer при резиновой верстке](http://shpargalkablog.ru/2014/02/footer-bottom.html)
13. [Firefox overflow-y not working with nested flexbox](http://stackoverflow.com/questions/28636832/firefox-overflow-y-not-working-with-nested-flexbox)
14. [Flexbox Tester (Understand how to calculate the width of flex items)](https://madebymike.com.au/demos/flexbox-tester/)
15. [11 вещей которые я узнал, читая спецификацию flexbox](https://habrahabr.ru/post/329820/)
16. **Формула расчета flex-grow** (*насколько будет растянут flex-элемент относительно оставшихся flex-элементов во flex-контейнере при распределении положительного свободного пространства*): 

    (Итог.размер_1 - flex-basis_1) * flex-grow_2 = (Итог.размер_2 - flex-basis_2) * flex-grow_1, 
    *где *_1 - свойства одного flex-элемента, а *_2 - другого flex-элемента.*
    
17. **Формула расчета flex-shrink** (*насколько будет сужен flex-элемент относительно оставшихся flex-элементов во flex-контейнере при распределении отрицательного свободного пространства*): 

    (flex-basis_1 - Итог.размер_1) * flex-basis_2 * flex-shrink_2 = (flex-basis_2 - Итог.размер_2) * flex-basis_1 * flex-shrink_1, 
    *где *_1 - свойства одного flex-элемента, а *_2 - другого flex-элемента.*

18. [Flexbugs](https://github.com/philipwalton/flexbugs)

======

### Media Queries
1. [Адаптивный и мобильный дизайн с CSS3 (habrahabr)](http://habrahabr.ru/post/119127/)
2. [Медиазапросы: width против device-width (habrahabr)](https://habrahabr.ru/post/254871/)

======

### Анимации
1. [Руководство по CSS3-анимациям (frontender)](http://frontender.info/ochen-prostoe-rukovodstvo-po-css-animatsiyam/)
2. [CSS3 3D трансформации](https://html5book.ru/3d-transform/)
3. [Сoлнечная система на чистом css (2D и 3D)](https://tproger.ru/translations/solar-system-css3-3/)
4. Готовые CSS-анимации: [текста](http://daneden.github.io/animate.css/); [кнопок, диалогов, списков...](http://h5bp.github.io/Effeckt.css/), [появления картинок](http://www.minimamente.com/example/magic_animations/), [hover-эффектов](http://ianlunn.github.io/Hover/), [загрузки данных](http://projects.lukehaas.me/css-loaders/), [всплывающих подсказок](http://kazzkiq.github.io/balloon.css/), [всякого разного](http://cssanimate.com/)

======

### Полезные CSS-свойства 
1. [currentColor](http://getinstance.info/articles/css/extending-the-color-cascade-with-the-css-currentcolor-variable/) (это первая css-переменная; ее значением является значение свойства color соответствующего элемента)
2. [attr()](https://tympanus.net/codrops/css_reference/attr/) (функция, которая возвращает значение указанного атрибута соответствующего DOM-элемента)
3. [pointer-events](http://positivecrash.com/pointer-events_css/) (позволяет контролировать когда, как и может ли вообще указатель мыши взаимодействовать с элементом)
4. [background-clip](http://css-live.ru/articles-css/background-clip-use-cases.html) (позволяет обрезать "лишнюю" часть изображения (кадрировать изображение))
5. [writing-mode](https://24ways.org/2016/css-writing-modes/?ct=t(hamail_20170115)) (устанавливает направление текста)
6. [CSS3 columns](http://www.webdesignerdepot.com/2013/03/how-to-use-css3-columns/) (свойства для создания многоколончатого текстового контента (газетного образца))
7. [@-правила CSS](http://frontender.info/the-at-rules-of-css/) (@media, @keyframes, @supports...)
8. [60 FPS? Легко! pointer-events:none!](https://habrahabr.ru/post/204238/)

======

### CSS Methodologies
1. Writing modular CSS (Zell Liew): [part 1](https://zellwk.com/blog/css-architecture-1/) (BEM), [part 2](https://zellwk.com/blog/css-architecture-2/) (BEM + OOCSS +Atomic Design), [part 3](https://zellwk.com/blog/css-architecture-3/) (file structure and organization)
2. [Tame Unruly Style Sheets With These Three CSS Methodologies](https://www.sitepoint.com/tame-unruly-style-sheets-three-css-architecture-methodologies/) (BEM, SMACSS, ECSS)
3. [Способы организации CSS-кода (habrahabr)](https://habrahabr.ru/post/256109/)
4. [Methods to Organize CSS](https://css-tricks.com/methods-organize-css/)

#### Методолия БЕМ
1. [Официальная документация](https://ru.bem.info/)
2. [С чего всё начиналось и зачем это всё нужно (habrahabr)](https://habrahabr.ru/company/yandex/blog/276035/)
3. [Все о БЕМ (Игорь Зенич)](https://www.youtube.com/watch?v=kBgHdSOj33A)
4. [БЭМ и CSS предпроцессоры (nicothin)](http://nicothin.github.io/idiomatic-pre-CSS/)

#### Другие методологии
1. [Object Oriented CSS (OOCSS)](https://github.com/stubbornella/oocss/wiki)
2. [Scalable and Modular Architecture for CSS (SMACSS)](https://smacss.com/book/)
3. [Atomic Design](http://atomicdesign.bradfrost.com/table-of-contents/)
4. [Enduring CSS (ECSS)](http://ecss.io/)

======

### CSS preprocessors
*Надстройка над CSS, которая добавляет ранее недоступные возможности для CSS, с помощью новых синтаксических конструкций. Основная задача препроцессора — это предоставление удобных синтаксических конструкций для разработчика, чтобы упростить, и тем самым, ускорить разработку и поддержу стилей в проектах. CSS препроцессоры преобразуют код, написанный с использованием препроцессорного языка, в чистый и валидный CSS-код.*

1. [Почему стоит использовать препроцессоры (habrahabr)](https://habrahabr.ru/post/214143/)
2. [SASS против LESS (habrahabr.ru)](https://habrahabr/post/144309/)
3. [CSS-препроцессоры](https://www.youtube.com/watch?v=jrCr9f9bIiM&t=252s&index=1&list=PLuEo4W0EBxtVyV0ycYJVLiOvwVSZXS3Iw)

#### LESS
1. [Официальный сайт](http://lesscss.org/)
2. [Путеводитель для новичков](https://mrmlnc.gitbooks.io/less-guidebook-for-beginners/content/chapter_1/compiling-and-debugging.html)
3. [Видео-урок от loftblog](http://loftblog.ru/material/preprocessor-less-dinamicheskij-css/)
4. [LESS: программируемый язык стилей (habrahabr)](https://habrahabr.ru/post/136525/)
5. [Основы LESS (webref)](https://webref.ru/layout/less)
6. Интерактивный курс от htmlacademy: [Знакомство с LESS](https://htmlacademy.ru/courses/85) и [Примеси в LESS](https://htmlacademy.ru/courses/125)
7. [Winless - офлайн и онлайн компилятор CSS из LESS](http://winless.org/)

#### SASS/SCSS+Compass
1. [Официальный сайт](http://sass-scss.ru/install/)
2. [Изучаем SCSS (курс от codeAcademy)](https://www.codecademy.com/en/courses/learn-sass)
3. [Руководство на русском языке](http://sass-scss.ru/documentation/)
4. [Основы SCSS (webref)](https://webref.ru/layout/sass)
5. [SCSS — новая порция глазури от Sass (habrahabr)](https://habrahabr.ru/post/96417/)
6. [SCSS — немного практики (habrahabr)](https://habrahabr.ru/post/140612/)
7. Видео-уроки от loftblog: [SASS и SCSS](http://loftblog.ru/lessons/sass-scss/), [SASS и Compass. Введение](http://loftblog.ru/material/legkoe-pogruzhenie-v-sass-i-compass/), [SASS и Compass. Продолжение](http://loftblog.ru/material/vvedenie-v-sass-compass-prodolzhenie/)
8. [7 Sass techniques to help you write better code](https://www.devbridge.com/articles/7-sass-techniques-to-help-you-write-better-code/?utm_source=CSS-Weekly&utm_campaign=Issue-266&utm_medium=email) 
9. [10 Things You Probably Didn’t Know about Sass](https://hackernoon.com/10-things-you-probably-didnt-know-about-syntactically-awesome-style-sheets-d94bc5c137e6)
10. Media Queries в SASS: [Как использовать Media Queries](https://habrahabr.ru/post/156645/), [Media queries in Sass](http://thesassway.com/intermediate/responsive-web-design-part-2)
11. [Sassmeister - онлайн-редактор, поддерживающий синтаксис SASS и SCSS](http://www.sassmeister.com/)
12. [Онлайн-конвертер из SCSS в CSS](http://medialize.github.io/playground.sass.js/)

#### Stylus
1. [Официальный сайт](http://stylus-lang.com/)
2. [Библиотека примесей для stylus](http://tj.github.io/nib/)

======

### PostCss
*A tool for transforming CSS with JavaScript*

1. [Официальный сайт] (http://postcss.org/)
2. [Используем PostCSS правильно (Андрей Ситник)] (https://www.youtube.com/watch?v=qhouBGNncGQ)
3. [Using PostCSS with BEM and SUIT Methodologies] (https://webdesign.tutsplus.com/tutorials/using-postcss-with-bem-and-suit-methodologies--cms-24592)

======

### StyleLint
*A mighty, modern CSS linter that helps you enforce consistent conventions and avoid errors in your stylesheets*

1. [Официальная документация](https://github.com/stylelint/stylelint)
2. [Как и зачем линтить CSS (Андрей Ситник)](https://www.youtube.com/watch?v=geoy-41wRQw)
3. [Инспекция и причёсывание CSS](http://juwain.ru/)
4. [Stylelint в Sublime Text](https://packagecontrol.io/packages/SublimeLinter-contrib-stylelint)
5. [Плагин stylelint-scss](https://github.com/kristerkari/stylelint-scss) (линтинг scss-синтаксиса)
6. [Плагин stylelint-order](https://www.npmjs.com/package/stylelint-order) (сортировка свойств)
7. [Плагин stylelint-config-standard](https://github.com/stylelint/stylelint-config-standard) (набор правил от AirBnB)
7. [Stylelint Config Generator](https://maximgatilin.github.io/stylelint-config/?utm_source=forwebdev_twtr&utm_medium=announcement&utm_campaign=stylelint-config-generator--dialogovyy-i)

======

### Советы и полезные приемы
1. [Каскадирование и специфичность (habrahabr)](https://habrahabr.ru/post/278477/)
2. [On :not and Specificity](http://bitsofco.de/on-not-and-specificity/)
3. [Боремся со схлопыванием margin (habrahabr)](https://habrahabr.ru/post/257327/)
4. [«Загадочные отступы» между inline-элементами (css-live)](http://css-live.ru/articles/zagadochnye-otstupy-mezhdu-inlajn-blokami.html)
5. [Fighting the Space Between Inline Block Elements (css-tricks)](https://css-tricks.com/fighting-the-space-between-inline-block-elements/)
6. [Как убрать лишние отступы у img внутри блока](http://vaden-pro.ru/blog/css/lishnie-otstupy-img)
7. [Textarea. Как избавиться от отступа снизу](http://www.sql.ru/forum/1051967/textarea-i-otstup-snizu)
8. [Вставка спецсимволов в before и after](http://xiper.net/collect/html-and-css-tricks/content/insert-symbols)
9. [Несколько неочевидных фишек CSS, о которых вы могли не знать](https://medium.com/@lucyhackwrench/%D0%BD%D0%B5%D1%81%D0%BA%D0%BE%D0%BB%D1%8C%D0%BA%D0%BE-%D0%BD%D0%B5%D0%BE%D1%87%D0%B5%D0%B2%D0%B8%D0%B4%D0%BD%D1%8B%D1%85-%D1%84%D0%B8%D1%88%D0%B5%D0%BA-css-%D0%BE-%D0%BA%D0%BE%D1%82%D0%BE%D1%80%D1%8B%D1%85-%D0%B2%D1%8B-%D0%BC%D0%BE%D0%B3%D0%BB%D0%B8-%D0%BD%D0%B5-%D0%B7%D0%BD%D0%B0%D1%82%D1%8C-780e7e4876a3#.qyeo9ytga)
10. [Центрирование горизонтальное и вертикальное (learn.javascript)](https://learn.javascript.ru/css-center)
11. [Способы вертикального выравнивания (habrahabr)](https://habrahabr.ru/post/277433/)
12. [Тонкости использования селекторов аттрибутов](https://habrahabr.ru/post/85920/)
13. [Как с помощью CSS прижать footer к низу окна браузера](http://dimox.name/press_footer_bottom_with_css/)
14. [Способы обрезания многострочного текста по высоте](http://getinstance.info/articles/css/truncate-multiline-text/)
15. [Антигерой CSS-разметки – свойство «display: table»](https://htmlacademy.ru/blog/29)
16. [Как работает calc](https://bitsofco.de/how-calc-works/?ct=t(hamail_20170215))
17. [О select в разных браузерах (habrahabr)](https://habrahabr.ru/company/htmlacademy/blog/257743/)
18. [Все свойста для background](https://bitsofco.de/the-background-properties/?ct=t(hamail_20160815))
19. [Краткая запись CSS как антипаттерн](http://prgssr.ru/development/kratkaya-zapis-css-kak-antipattern.html?ct=t(hamail_20170115))
20. [What is the class sr-only used for?](http://stackoverflow.com/questions/19758598/what-is-sr-only-in-bootstrap-3)
21. [Единицы viewport против процентов](http://front-end.su/2015/10/07/viewport-units-vs-percent/)
22. [The Power of em Units in CSS](https://www.sitepoint.com/power-em-units-css/)
23. [Несколько дельных советов по CSS (habrahabr)](https://habrahabr.ru/post/273403/)
24. [8 правил для улучшения вашего CSS](http://forwebdev.ru/css/8-rules-to-improve-css/)
25. [Golden Guidelines for Writing Clean CSS](https://www.sitepoint.com/golden-guidelines-for-writing-clean-css/)
26. [Советы по написанию современного CSS](http://nicothin.pro/page/css-solutions)
27. [Коллекция практических советов и заметок по вёрстке (habrahabr)](https://habrahabr.ru/post/273471/?mobile=no)
28. [CSS для Javascript разработчика](https://learn.javascript.ru/css-for-js)
29. [50 фрагментов CSS полезных каждому дизайнеру](http://webformyself.com/50-fragmentov-css-poleznyx-kazhdomu-dizajneru/)
30. [Точки между словами на CSS](https://medium.com/@inomdzhon/dot-leaders-%D0%B8%D0%BB%D0%B8-%D1%82%D0%BE%D1%87%D0%BA%D0%B8-%D0%BC%D0%B5%D0%B6%D0%B4%D1%83-%D1%81%D0%BB%D0%BE%D0%B2%D0%B0%D0%BC%D0%B8-%D0%BD%D0%B0-css-5c56d0eaabd0#.m580zpvzz)
31. [Sorax. Конкурс верстки. Анализ работ победителей (видео)](https://www.youtube.com/watch?v=snu8Rg6iNW4)
32. [Тестирование верстки (makeup)](https://habrahabr.ru/post/277457/)
33. [Баги в браузерах. Кто виноват и что делать?](https://www.youtube.com/watch?v=K-t9FIs2WTo&feature=em-uploademail)
34. [Советы по кроссбраузерной верстке](http://www.internet-technologies.ru/articles/article_1834.html)
35. [Использование viewport-единиц в типографике](http://webbeaver.ru/future/viewport-unit/?ct=t(hamail_20160415)) 

======

### Utils
1. [Autoprefixer online](https://autoprefixer.github.io/ru/)
2. [Проверка валидности кода](http://jigsaw.w3.org/css-validator/)
3. Кривые Безье: [ресурс 1](http://cubic-bezier.com/#.17,.67,.83,.67) и [ресурс 2](http://easings.net/ru)
4. [20 CSS3 генераторов которые облегчат жизнь дизайнеру](http://beloweb.ru/novichkam/20-css3-generatorov-kotoryie-oblegchat-zhizn-dizayneru.html)
5. [Gradient Generator, Border Radius, Noise Texture и Box Shadow](http://www.cssmatic.com/gradient-generator#'\-moz\-linear\-gradient\%28left\%2C\%20rgba\%28248\%2C80\%2C50\%2C1\%29\%200\%25\%2C\%20rgba\%28241\%2C111\%2C92\%2C1\%29\%2050\%25\%2C\%20rgba\%28246\%2C41\%2C12\%2C1\%29\%2051\%25\%2C\%20rgba\%28240\%2C47\%2C23\%2C1\%29\%2071\%25\%2C\%20rgba\%28231\%2C56\%2C39\%2C1\%29\%20100\%25\%29\%3B)
6. [CSS gradient animator](https://www.gradient-animator.com/)
7. [CSS Filter Effects](http://html5-demos.appspot.com/static/css/filters/index.html)
8. [CSS clip-path maker](http://bennettfeely.com/clippy/) 
9. [Парсинг спрайтов](http://www.spritecow.com/)
10. [Specificity Online-Calculator](http://specificity.keegan.st/)
11. [nth-child tester](https://css-tricks.com/examples/nth-child-tester/)

======

### Проверка знаний
1. [w3schools.com](http://www.w3schools.com/quiztest/quiztest.asp?qtest=CSS)
2. [certification.mail.ru](https://certification.mail.ru/tests/css/start/)
3. [certification.mail.ru (повышенная сложность)](https://certification.mail.ru/tests/css-timechallenge/start/)
4. [crowdtest.org](http://crowdtest.org/ru/css)
5. [geekbrains.ru (начальный уровень)](https://geekbrains.ru/tests/2)
6. [geekbrains.ru (средний уровень)](https://geekbrains.ru/tests/17)
