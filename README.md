Для начала работы нужно установить npm и bower компоненты. Для этого ввести в командную строку с корне проекта:
npm install
bower install

Команды:

gulp - запускает основной задачи на сборку проекта, сервер и отслеживение изменения файлов в директории /src/
    включает в себя:
    gulp build - сборка проекта
    gulp webserver - запуск сервера на основе файлов в директории /build/
    gulp watch - задача на отслеживение изменения файлов в директории /src/

gulp clean - чистка папка build

gulp sprite - сборка спрайтов (можно запускать параллельно работе основной задачи)


Готовые элементы

modal - для открытия модалки нужна ссылка вида <code><a href="#name"></a></code> и класс "open_modal". Будет открыта модалка с id="name" в обертке "#overlay"
select - заменяет стандартный селект. Для этого используем шаблон из components/select.html
Классы: .select-default - пункт выбранный по умолчанию; .selected - текущий выбранный пункт
scrollto - весим на элементы <code><a href="#element" class=".j-scroll-to"></a></code> и плавно скролим до элемента c id="element"

Сторонние плагины лежат в папке /src/plugin и при неободимости инклудтся в файлах main.js и main.less
<ul>
    <li>owl.carousel - <a href="https://owlcarousel2.github.io/OwlCarousel2/docs/started-welcome.html">Документация</a></li>
    <li>jquery.cycle - <a href="http://jquery.malsup.com/cycle/options.html">Документация</a></li>
</ul>

