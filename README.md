# Scale Master
## [ONLINE DEMO](https://soulmare.github.io/scale_master/)

Web application for creating printable analog meter scales.

## ----------------------------------------------------------

## О ПРОГРАММЕ Scale Master
Scale Master - это браузерное JavaScript приложение, простой векторный редактор, позволяющий создавать шкалы для аналоговых измерительных приборов. Изображения шкал создаются в формате SVG, с которым работают многие графические редакторы.

Для работы без интернет соединения нужно скачать архив с исходным кодом, распаковать его и окрыть в браузере файл index.html.

Программа некоммерческая, поэтому наличие свободного времени на ее доработку прямо зависит от заинтересованности пользователей, а также от других причин.

## СИСТЕМНЫЕ ТРЕБОВАНИЯ
Наличие современного браузера (IE пока не тестировался). Соединение с интернет необязательно.


## КАК СОЗДАТЬ ШКАЛУ
Через меню можно открыть один из примеров и доработать его под собственные нужды. Или же, создать новую шкалу с чистого листа, добавляя нужные элементы с помощью кнопки "Создать объект" на левой панели.

Интерфейс программы напоминает векторные графические редакторы. Слева находится список объектов с кнопками для управления ими. Порядок объектов в списке влияет на их перекрытие при наложении друг на друга. При выборе объекта вокруг него появляется рамка, а справа отображается список свойств. Если рабочая область в фокусе, стрелки клавиатуры двигают объект. Изменение масштаба - прокруткой колесика при зажатой клавише Ctrl.

Готовую шкалу можно скачать в удобном формате. SVG подходит, если изображение потом нужно загрузить в векторный графический редактор для доработки. Только этот формат является родным для программы, и такой файл можно будет в нее снова загрузить для редактирвоания. PNG подходит для печати или обработки растровыми редакторами. Чтобы распечатать шкалу в соответствии с выбранным размером, нужно чтобы совпадало разрешение экспорта с разрешением при печати. Это может быть, например, 300ppi (или dpi). Если изображение занимает весь лист, возможно понадобится убрать поля для правильного масштаба.

## ПОМОЩЬ ПРОЕКТУ
- Сообщения об ошибках в работе программы
- Коррекция языковых ошибок в интерфейсе, а также его перевод на новые языки. Образец языкового файла - lang/ru.json. Английского файла полного нет - этот язык принят оригинальным, и часть строк находится в исходном коде.
- Предложения по улучшению программы и практическое участие в проекте.
- Присылка шкал, выполненных на основе распространенных форматов измерительных головок, приборов и т. п.

## ИСПОЛЬЗОВАННЫЕ ПРОЕКТЫ
- JsViews MVVM фреймворк.
- Взяты небольшие функции из векторного редактора SVG-Edit
- Несколько шкал в примерах взяты из рисовалки шкал автора Starichok, опубликованной на forum.cxem.net
- Иконки и стили кнопок от jQuery UI


автор:

Александр Болоховецкий

soulmare@gmail.com
