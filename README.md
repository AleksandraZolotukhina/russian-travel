# Проект: Путешествие по России

### Обзор
- О проекте
    - Figma
    - Какие технологии используются в проекте
    - GitHub Pages
    - Исправления
## О проекте
____
 Проект "Путешествие по России" использовался для тренировки в разработке интерфейса для разных устройств.
- Figma
<br />
Ссылка на макет в Figma: 
<br />
<https://www.figma.com/file/5S2WSbEFL6awjVWJ0NWL8Q/Sprint-3_-Russia-_-desktop-mobile?node-id=28503%3A0>

- Какие технологии используются в проекте
    - БЭМ методология и организация файловой структуры <em>Nested</em>
    - Для быстроты загрузки сайта, изображения были оптимизорованы
    - Для разработки интерфейса для разных устройств используются <em>медиа-запросы</em>
    - Оптимизация шрифтов под устройства с различными разрешениями

- GitHub Pages
<br />
Ссылка GitHub Pages: 
<br />
<https://alexandrazolotykhina.github.io/russian-travel/index.html>

- Исправления
    - блок <em>footer__list</em> заменен на список
    - создан общий класс <em>page__list</em> для сброса стилей унаследованных от браузера
    - добавлен <em>target="_blank"</em> для ссылок
    - также исправлены другие недочеты
        - исправлена бэм методология в <em>body.css</em>
        - добавлен тег <em>figure</em> и <em>figcaption</em>  в блок content
        - задан font-weight для <em>place__url-heading</em>
        - добавлен эффект наведения для смены языка в <em>header__lang-link</em>