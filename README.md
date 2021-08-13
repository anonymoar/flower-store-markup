# flower-store-markup
Project for HTML Academy marathon

## Layout

[Design in Figma](https://www.figma.com/file/HdU7VTV6uNdHyuvDrffeKC/%D0%9C%D0%B0%D1%80%D0%B0%D1%84%D0%BE%D0%BD-2021?node-id=0%3A1)
<details>
<summary>Picture</summary>
  
![Layout PNG if U don't want to open it in Figma](https://user-images.githubusercontent.com/45916811/129426180-985f6c0f-2a63-4936-8e4f-8e8b02e18b90.png)
  
</details>

## Specification

### Общие технические требования

- Стандарты вёрстки: HTML, CSS, прогрессивное улучшение.
- Сетка: определена в макете.
- Адаптивность вёрстки: нет.
- Используемые фреймворки: нет.
- Типографика: частично определена в макете, прочее — на усмотрение разработчика.
- Используемые шрифты: `Montserrat`, `Playfair Display`. Шрифт есть на Google Fonts.
- Различные состояния интерактивных элементов стилизуются на рассмотрения разработчиков

### Обязательные требования

- Контентная область центрируется и не может быть уже макетной ширины. Фоны, которые упираются в края макета, должны тянуться на всю страницу.
- Блок карты: достаточная реализация — обычное изображение.
- Карточки с букетами (свадебные букеты, букеты с пионами, выбрать букет) являются ссылками и должны вести на страницу каталога.
- Слайдер в разделе «Популярные букеты» реализовывать не нужно.
- Логотип — это ссылка на главную страницу.

## Сriteria

При вёрстке проекта мы рекомендуем опираться на приведённые ниже критерии. Именно по ним будет проводиться  разбор домашних заданий наставниками.
Базовые критерии охватывают наиболее важные требования к проекту и проверяют основные знания и навыки.
Дополнительные критерии проверяют внимательность к деталям и оценивают проект с точки зрения шлифовки его качества и оптимизации.

### Basic criteria

#### Разметка

- Выполнена HTML-разметка всех страниц и всех элементов на страницах
Критерий требует, чтобы все страницы проекта и все элементы на этих страницах были свёрстаны.
- Все стили проекта написаны и подключены в одном файле
Все стили страниц должны находиться в едином файле. Исключением является файл `normalize.css` и стили с Google Fonts.
- Стилевой файл подключён внутри `<head>`
Подключение стилевых файлов должно производиться внутри `<head>`.
- Грубые ошибки в разметке отсутствуют
  - Ссылки должны быть сделаны тегом `<a>`.
  - Элементы со строчным боксом по умолчанию не должны быть использованы для создания крупных сеточных блоков.
  - Для построения сетки должны использоваться элементы, которые по умолчанию являются потоковыми (в том числе секционными), а не фразовыми.
  - Абзацы должны быть сделаны тегами `<p>`.
Если в макете текст разделен на несколько абзацев, то в разметке каждый такой абзац должен быть обёрнут в соответствующий тег. Недопустимо использовать `<br>` для разбиения текста на абзацы.
  - Семантические теги `<header>`, `<footer>`, `<section>` и другие должны быть использованы правильно.
- Документ проходит проверку на валидность

#### Стилизация

- Раскладка блоков на странице сделана на флексах и гридах
Гриды используются для основных структурных блоков страницы (шапка, главный контент, подвал) и для создания колонок в контенте страниц.
Для остальной раскладки используются флексы: навигация, карточки, Использование гридов для основных структурных блоков и флексов для всех остальных — это рекомендация, а не требование. Главное — разумно использовать возможности и флексов, и гридов.
- В CSS отсутствует `!important`
- Подключены правильные шрифты, их размеры, высота строк, цвет и толщина равны соответствующим параметрам в макетах и техническом задании. В проекте должны использоваться именно те шрифты, которые указаны в макете. При этом их размеры, высота строк, цвета, и жирность должны быть равны соответствующим параметрам в макетах и техническом задании.
Примечание: Если в макете высота строки для однострочного текста указана без учёта появления второй строки (например, для создания отступа), то следовать параметрам макета буквально не нужно. Высоту строки нужно оставить унаследованную от глобальных стилей, а отступ сделать с помощью `margin` или `padding`, в зависимости от ситуации.
   - При подключении шрифтов с Google Fonts, если в проекте используются несколько разных шрифтов, их нужно подключать с помощью одной ссылки.
   - При локальном подключении шрифтов необходимо использовать два формата — `WOFF2` и `WOFF`.
- Указаны альтернативные варианты шрифта и тип семейства в конце перечисления `font-family`.
Альтернативный веб-безопасный шрифт и тип семейства необходимо указывать, чтобы в случае отсутствия основного шрифта изменения внешнего вида шрифтов на странице были минимальны.
Список веб-безопасных шрифтов можно посмотреть здесь: http://www.cssfontstack.com/.
- При наполнении контентом (как в макете) элементы каждой страницы соответствуют макету

#### Разное

- В корне документа имеются папки css, img, js или аналогичные. Главная страница имеет название `index.html`. В названиях и расширениях файлов нет заглавных букв и пробелов, использованы только латинские символы
- Единообразное написание и форматирование кода в HTML и CSS
- Выбран подходящий формат изображений
- Проект соответствует техническому заданию

### Extra criteria

#### Разметка
- У всех изображений в теге `<img>` прописан размер
Должны быть указаны действительные размеры картинок без указания единиц измерения. Размеры должны быть указаны в виде целого числа — 100, 213, а не дробного — 100.5, 213.25.
- Использовано минимально возможное количество HTML-элементов (нет лишних элементов)
В разметке должно быть использовано минимально возможное количество элементов. Не должно быть лишних обёрток и блоков, которые используются для оформления и могут быть заменены на псевдоэлементы.
- Телефоны размечены ссылками с протоколом tel
Мобильные и десктопные браузеры вызывают системные приложения для звонков (сотовый звонок, Skype, Facetime и другие) при клике по ссылке с протоколом tel, по аналогии с протоколом mailto, который открывает почтовый клиент.
```
<a href="tel:88005558628">8 800 555-86-28</a>
```

#### Стилизация

- Использован `normalize.css`
Для выполнения этого критерия должен быть использован файл `normalize.css`.
Верно: файл `normalize.css` подключается отдельным файлом перед основным файлом стилей. Стили в файле `normalize.css` нельзя изменять и дополнять.
- Для стилизации не использованы `#id`
Для стилизации объектов лучше использовать селекторы по классам. Использовать `id` для стилизации недопустимо.
- Нет вложенности селекторов больше двух
Длинные цепочки селекторов усложняют код и его поддержку. Хорошим подходом считается использовать вложенность не больше двух уровней.
- Для блока, у которого есть фоновое изображение, прописан фоновый цвет, который соответствует преобладающему цвету изображения (пока изображение не загружено, страница выглядит похоже на макет)
Такой метод используется для перестраховки, как и в случае со шрифтом. В этом случае, если фоновое изображение не загрузится, на заднем фоне останется преобладающий цвет.
- Файл стилей представлен в двух вариантах: с форматированием и минимизированный, к странице подключён минимизированный
- Нет глобальных стилей тегов
Для задания стилей используются только селекторы по классам или вложенные селекторы.
