### Grunt.js
*Инструмент для сборки JavaScript-проектов*

1. [Официальный сайт](http://gruntjs.com/getting-started)
2. [Приступая к работе с Grunt (webref.ru)](https://webref.ru/dev/grunt-getting-started)
3. [Быстрая настройка (habrahabr.ru)](https://habrahabr.ru/post/244725/)
4. [Автоматизация для самых ленивых (видео от loftblog)](http://loftblog.ru/material/avtomatizaciya-dlya-samyx-lenivyx-vmeste-s-grunt-js/)
5. [Обзор от Sorax](https://www.youtube.com/watch?v=Cxo1vVI9--E)
6. [Grunt 0.4: система сборки для фронтенд-разработчиков](http://nano.sapegin.ru/all/grunt-0-4)
7. [Считаете, что Grunt Вам не нужен?](http://frontender.info/grunt-is-not-weird-and-hard/)
8. [Using Jade and Grunt to Speed Up HTML Production](http://www.sitepoint.com/using-jade-and-grunt-to-speed-up-html-production/)

##### Полезные плагины:
|         Плагин         |         Назначение плагина, его возможности        |
| ---------------------- | -------------------------------------------------- |
| [grunt-htmllint](https://www.npmjs.com/package/grunt-htmllint) | Проверка html-файлов на соответствие стандарту |
| [autoprefixer](https://www.npmjs.com/package/grunt-autoprefixer) | Автоматически расставляет префиксы к CSS-свойствам, исходя из статистики [caniuse](http://caniuse.com/) |
| [ucss](https://www.npmjs.com/package/ucss) | Анализирует HTML-код и находит все неиспользуемые и дублирующиеся стили |
| [less](https://github.com/gruntjs/grunt-contrib-less) | Компилирует CSS из LESS |
| [cssmin](https://github.com/gruntjs/grunt-contrib-cssmin) | Минимизирует CSS |
| [grunt-babel](https://www.npmjs.com/package/grunt-babel) | Конвертирует JavaScript ES2015 в более старую версию |
| [concat](https://github.com/gruntjs/grunt-contrib-concat) | Конкатанация js-файлов |
| [uglify](https://www.npmjs.com/package/gulp-uglify) | JavaScript-компрессор |
| [grunt-eslint](https://www.npmjs.com/package/grunt-eslint) | Проверяет js-файлы на соответствие стандарту |
| [load-grunt-tasks](https://www.npmjs.com/package/load-grunt-tasks) | Быстрое подключение плагинов |
| [grunt-newer](https://www.npmjs.com/package/grunt-newer) | Перекомпиляция только измененных файлов |
| [grunt-jade](https://www.npmjs.com/package/grunt-jade) | Компиляция HTML из Jade |
| [grunt-contrib-pug](https://www.npmjs.com/package/grunt-contrib-pug) | Компиляция HTML из Jade |
| [grunt-jsdoc](https://www.npmjs.com/package/grunt-jsdoc) | Генерация документации в HTML-формате из комментариев в JavaScript-коде |

*Больше плагинов см. [тут](https://habrahabr.ru/post/251157/)*

======

### Gulp.js
*Инструмент для сборки JavaScript-проектов*

1. [Официальный сайт](http://gulpjs.com/)
2. [Скринкаст по Gulp (learn.javascript.ru)](https://learn.javascript.ru/screencast/gulp)
3. [Руководство для самых маленьких](https://www.youtube.com/watch?v=vW51JUVT66w)
4. [Видео от loftblog](http://loftblog.ru/material/gulp-js-rabotaem-s-css-concat-minify-rename-notify-watch-dest/)
5. [Автоматизация работы с Gulp](https://webref.ru/dev/automate-with-gulp)

##### Полезные плагины:

|         Плагин         |         Назначение плагина, его возможности        |
| ---------------------- | -------------------------------------------------- |
| [gulp-pug](https://github.com/jamen/gulp-pug/blob/master/gulpfile.js) | Преобразование pug-файлов в html-файлы |
| [gulp-htmlhint](https://github.com/bezoerb/gulp-htmlhint) | Проверка html-файлов на соответствие code style |
| [htmlhint-stylish](https://www.npmjs.com/package/htmlhint-stylish) | Стили, на соответствие которым проверяются html-файлы |
| [*gulp-sass](https://github.com/dlmanning/gulp-sass) | Преобразование sass-файлов в css-файлы |
| [*gulp-scss](https://www.npmjs.com/package/gulp-scss) | Преобразование scss-файлов в css-файлы |
| [gulp-uncss](https://github.com/ben-eb/gulp-uncss) | Удаление из css-файлов стилей, отсутствующих в html-файлах |
| [gulp-autoprefixer](https://www.npmjs.com/package/gulp-autoprefixer) | Автогенерация селекторов, специфичных для различных браузеров. Подробнее см. [здесь](http://itsurface.ru/gulp-autoprefixer/) |
| [gulp-csslint](https://www.npmjs.com/package/gulp-csslint) | Проверка css-файлов на коррестность |
| [gulp-cssnano](https://www.npmjs.com/package/gulp-cssnano) | Конкатанаци и минификация css-файлов |
| [gulp-csscomb](https://www.npmjs.com/package/gulp-csscomb) | Сортировка стилей и их форматирование. О конфигурировании этого плагина см. [тут](https://github.com/csscomb/csscomb.js/blob/master/doc/options.md). Интерактивное создание csscomb.json доступно [здесь](http://csscomb.com/config)  |
| [gulp-sourcemaps](https://www.npmjs.com/package/gulp-sourcemaps) | Создает source map |
| [gulp-rename](https://www.npmjs.com/package/gulp-rename) | Переименование файлов |
| [gulp-imagemin](https://www.npmjs.com/package/gulp-imagemin) и [imagemin-pngquant](https://www.npmjs.com/package/imagemin-pngquant) | Оптимизация картинок |
| [imagemin-pngquant](https://www.npmjs.com/package/imagemin-pngquant) | Оптимизация png-файлов | 
| [imagemin-jpeg-recompress](https://www.npmjs.com/package/imagemin-jpeg-recompress) | Оптимизация jpg-файлов | 
| [gulp.spritesmith](https://www.npmjs.com/package/gulp.spritesmith) | Создание спрайтов |
| [gulp-svg-sprites](https://www.npmjs.com/package/gulp-svg-sprites) | Создание scg-спрайтов |
| [browser-sync](https://www.npmjs.com/package/browser-sync) | Запуск локального сервера и применение изменений в проекте налету |
| [del](https://www.npmjs.com/package/del) | Удаление файлов и каталогов |
| [gulplog](https://www.npmjs.com/package/gulplog) | Логирование для gulp и его плагинов|
| [gulp-cache](https://www.npmjs.com/package/npm-cache) | Чистка cache | 
| [gulp-notify](https://www.npmjs.com/package/gulp-notify) | Уведомление о возникающих ошибках во всплывающем окне |
| [gulp-plumber](https://www.npmjs.com/package/gulp-plumber) | Применение обработчика ошибок для всех .pipe() |
| [gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | Упрощение подключения плагинов в gulpfile.js |
| [gulp-sync](https://www.npmjs.com/package/gulp-sync) | Управление последовательностью выполнения задач |
| [gulp-stylus](https://www.npmjs.com/package/gulp-stylus) | Конвертер из препроцессора stylus в css |
| [gulp-base64](https://www.npmjs.com/package/gulp-base64) | Конвертация изображений в base64 и их встраивание в css |
| [gulp-to-base64](https://www.npmjs.com/package/gulp-to-base64) | Конвертация изображений и аудио в base64 и их запись в json-файл |
| [gulp-data](https://www.npmjs.com/package/gulp-data) | Подготовка из json-формата объекта с данными, которые могут быть скормлены другим плагинам для их использования |
| [json-loader](https://www.npmjs.com/package/json-loader) | Загрузка данных [из json в js](http://stackoverflow.com/questions/33650399/es6-modules-implementation-how-to-load-a-json-file) |

*Предварительно необходимо установить на компьютер Ruby и Sass. Подробнее об этом см. в репозитории [https://github.com/KAnastasiya/SublimeText3](Sublime Text3).*

======

### WebPack
*Утилита для сборки бандлов и оптимизации модулей JavaScript и др. ресурсов для фронтенда*

1. [Официальный сайт](https://webpack.github.io/docs/)
2. [Скринкаст (learn.javascript.ru)](http://learn.javascript.ru/screencast/webpack)
3. [Beginner’s guide to Webpack](https://medium.com/@dabit3/beginner-s-guide-to-webpack-b1f1a3638460#.kedf78td0)
4. [Пакуем как боги](http://frontender.info/packing-the-web-like-a-boss/)
5. [Видео о об использовании WebPack на реальном проекте](https://www.youtube.com/watch?v=uSYN9Fign-s)
6. [Презентация по Webpack (babakhanov)](https://babakhanov.github.io/lets-webpack/#/)
7. [CommonJS в Webpack](https://webpack.github.io/docs/commonjs.html)
8. [Babel в Webpack (модуль babel-loader)](https://github.com/babel/babel-loader)
9. [Пример моего конфига для Webpack 2](https://github.com/KAnastasiya/Webpack_2)

#### Webpack 2
- [Официальная документация](https://webpack.js.org/concepts/)
- [Видео от loftblog](https://www.youtube.com/playlist?list=PLbZerpEHZ8s0GgEcddz186-xRs8X0t0rA)
- [Набор видео от Ihatetomatoes (англ)](https://www.youtube.com/playlist?list=PLkEZWD8wbltnRp6nRR8kv97RbpcUdNawY)

##### Полезные загрузчики:

|             Загрузчик             |         Назначение и возможности        |
| --------------------------------- | --------------------------------------- |
| [pug-loader](https://github.com/pugjs/pug-loader) и [pug-load](https://github.com/pugjs/pug-load) | Загрузка pug-файлов. Также в проекте должен быть установлен [пакет для работы с самим pug](https://www.npmjs.com/package/pug) |
| [style-loader](https://github.com/webpack/style-loader) | Резервная обработка css-файлов |
| [css-loader](https://github.com/webpack/css-loader) | Загрузка css-файлов |
| [sass-loader](https://github.com/jtangelder/sass-loader) и [node-sass](https://github.com/sass/node-sass) | Загрузка scss-файлов |
| [less-loader](https://github.com/webpack/less-loader) |  Загрузка lESS-файлов. *Предварительно в проект нужно установить LESS (выполнить команду `npm install less`)* |
| [stylus-loader](https://github.com/shama/stylus-loader) | Загрузка styl-файлов |
| [autoprefixer-loader](https://www.npmjs.com/package/autoprefixer-loader) | Авторастановка вендорных-префиксов в css |
| [postcss-loader](https://github.com/postcss/postcss-loader) | PostCss-загрузчик |
| [url-loader](https://www.npmjs.com/package/url-loader) | Помещает графику до некоторого размера в виде data:uri, а свыше этого размера выносит в отдельный файл |
| [file-loader](https://www.npmjs.com/package/file-loader) | Загрузка файлов |
| [json-loader](https://www.npmjs.com/package/json-loader)| Загрузка json-файлов |
| [babel-loader](https://www.npmjs.com/package/babel-loader) | Преобразование es6 в 'обычный' javascript |
| [eslint-loader](https://github.com/MoOx/eslint-loader)| Проверка js-файлов на соответствие стандартам |
| [resolve-url-loader](https://github.com/bholloway/resolve-url-loader) | Разрешает относительные пути в операторах url() на основе исходного файла. |
| [svg-sprite-loader](https://www.npmjs.com/package/svg-sprite-loader) | Создание и использование svg-спрайтов |
| [image-webpack-loader](https://github.com/tcoopman/image-webpack-loader) | Загрузка изображений |

##### Полезные загрузчики PostCss:

|             Загрузчик             |         Назначение и возможности        |
| --------------------------------- | --------------------------------------- |
| [postcss-load-plugins](https://www.npmjs.com/package/postcss-load-plugins) | Загрузчик postcss-плагинов (из файла настроек) |
| [postcss-cssnext](https://github.com/MoOx/postcss-cssnext) | Позволяет использовать возможности CSS4 уже сегодня |
| [postcss-flexbugs-fixes](https://github.com/luisrudge/postcss-flexbugs-fixes) | Содержит bugfix для flexbox |
| [postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | Прописывает настройки font-face самостоятельно |
| [postcss-assets](https://github.com/assetsjs/postcss-assets) | Позволяет упростить указание размеров картинок |
| [postcss-property-lookup](https://github.com/simonsmith/postcss-property-lookup) | Создает ссылки на другие свойства |
| [postcss-browser-reporter](https://github.com/postcss/postcss-browser-reporter) | Отображение ошибок в браузере |
| [postcss-use](https://github.com/postcss/postcss-use) | Позволяет подключать postcss-плагины к отдельным файлам |
| [doiuse](https://github.com/anandthakker/doiuse) | Проверяет css-код по CanIUse |
| [postcss-bem](https://www.npmjs.com/package/postcss-bem) | Автоматическое именованеи классов по БЕМ. О настройке плагина см. [тут](https://webdesign.tutsplus.com/tutorials/using-postcss-with-bem-and-suit-methodologies--cms-24592) |
| [stylelint](https://github.com/stylelint/stylelint/blob/master/docs/user-guide/postcss-plugin.md) | Линтер stylelint |

##### Полезные плагины:
|              Плагин               |         Назначение и возможности        |
| --------------------------------- | --------------------------------------- |
| *NoErrorsPlugin|  Не дает перезаписать скрипты при наличии в них ошибок |
| *OccurrenceOrderPlugin | Минимизирует id, которые используются webpack для подгрузки чанков и прочего |
| DefinePlugin | Определение констант и выражений внутрь кода |
| ProvidePlugin | Анализ исходников и автоматическое создание import директив |
| [html-webpack-plugin](https://www.npmjs.com/package/html-webpack-plugin) | Генерация html по шаблону |
| [extract-text-webpack-plugin](https://www.npmjs.com/package/extract-text-webpack-plugin) | Конкатанация нескольких css-файлов |
| [webpack-merge](https://www.npmjs.com/package/webpack-merge) | Позволяет объединять массивы и объекты, в новый объект |
| [stylelint-webpack-plugin](https://www.npmjs.com/package/stylelint-webpack-plugin) | Линтинг (проверка на соответствие стандартам) стилей |
| [jsdoc-webpack-plugin](https://www.npmjs.com/package/jsdoc-webpack-plugin) | Генерация документации о скриптах проекта на основании комментариев к коду |

* 
- Для Webpack 2 вместо NoErrorsPlugin используется NoEmitOnErrorsPlugin
- Для Webpack 2 OccurrenceOrderPlugin предустановлен, то есть в webpack.config.js его можно не включать 
*

##### Другое:
|              Плагин               |         Назначение и возможности        |
| --------------------------------- | --------------------------------------- |
| [webpack-dev-server](https://www.npmjs.com/package/webpack-dev-server) | Локальный сервер для разработки |
| [webpack-hot-middleware](https://www.npmjs.com/package/webpack-hot-middleware) | "Гарячая" перезагрузка локального сервера |
| [webpack-stream](https://www.npmjs.com/package/webpack-stream) | Запуск webpack как потока для его удобной интеграции, например, с gulp |
| [vinyl-named](https://www.npmjs.com/package/vinyl-named) | Позволяет задавать файлам свои названия |

*Предварительно должен быть установлен [node.js](https://nodejs.org/en/)*

======

### Package management
*Инструменты для автоматизации установки, обновления, конфигурации и удаления библиотек*

##### NPM
1. [Официальный сайт](https://www.npmjs.com/) 
2. [For Beginners](https://www.impressivewebs.com/npm-for-beginners-a-guide-for-)

##### Yarn
3. [Официальный сайт](https://yarnpkg.com/en/)
4. [Видео от monsterlessons](http://monsterlessons.com/project/lessons/yarn-paketnyj-menedzher-ot-facebook) - менеджер пакетов от facebook

======

### Git
*Распределённая система управления версиями*

1. [Git для новичков (loftblog)](http://loftblog.ru/material/git-dlya-novichkov-1-osnovy/)
2. [Git для новичков](http://pcottle.github.io/learnGitBranching/)
3. [Как быстро работать с GIT](https://geekbrains.ru/events/218)
4. [Обучающий курс от codeacademy](https://www.codecademy.com/learn/learn-git)
5. [Книга "О Git"](http://howtodoit.com.ua/wp-content/uploads/2014/02/progit.ru_.pdf)
6. [githowto](https://githowto.com/)
7. [try Git](https://try.github.io/levels/1/challenges/1)
8. [Git. Коллекция самых популярных вопросов](http://firstaidgit.ru/#/)
9. [Git Tips](https://github.com/Imangazaliev/git-tips/blob/master/README.md)
10. [Советы по написанию коммитов (habrahabr)](https://habrahabr.ru/company/Voximplant/blog/276695/)
11. [GitKraken](https://www.gitkraken.com/) - кроссплатформенное приложение для контроля версий

======

### GitHub
*Крупнейший веб-сервис для хостинга IT-проектов и их совместной разработки. Основан на системе контроля версий Git*

1. [Как начать работать с GitHub: быстрый старт (habrahabr)](https://habrahabr.ru/post/125799/)
2. [Git & GitHub - работа под Windows](https://www.youtube.com/watch?v=SfSYrebXLDE)
3. [GitHub. Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
4. [Great README](https://medium.com/code-the-world/writing-a-great-readme-written-by-daniel-bader-4a02d1edc7a#.6uceset1o)
5. [Хостинг на GitHub (gh-pages)](https://htmlacademy.ru/blog/99-github-as-hosting)
6. [GitHub Gist - хранение и повторное использование кода](https://www.youtube.com/watch?v=fUUXus8gGk0)
7. [Невидимые друзья вашего github-репозитория](https://habrahabr.ru/company/eastbanctech/blog/323760/) 
