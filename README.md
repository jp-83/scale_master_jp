# scale_master
# https://github.com/soulmare/scale_master/

DEMO: https://soulmare.github.io/scale_master/

Web application for drawing analog meter scales
JavaScript driven, all client-side browser application, creates printable vector scale faces for analog meters etc.

# ----------------------------------------------------------


О ПРОГРАММЕ Scale Master

Scale Master - это браузерное JavaScript приложение, простой векторный редактор, позволяющий создавать шкалы для аналоговых измерительных приборов. Может работать без интернета - для этого достаточно скачать архив с исходным кодом, распаковать, и окрыть в браузере файл index.html.

Программа некоммерческая, поэтому наличие свободного времени на ее доработку прямо зависит от заинтересованности пользователей, а также от других причин.


СИСТЕМНЫЕ ТРЕБОВАНИЯ

Наличие современного браузера (IE пока не тестировался). Соединение с интернет необязательно.


КАК СОЗДАТЬ ШКАЛУ

На демо-странице программы можно увидеть набор нарисованных с ее помощью шкал, на основе которых можно создавать свои собственные. Или можно создать новую шкалу с чистого листа, добавляя на нее нужные элементы.

Интерфейс программы напоминает обычные векторные графические редакторы. Слева находится список объектов с кнопками для управления ими. Порядок объектов в списке влияет на их перекрытие при наложении друг на друга. При выборе объекта вокруг него появляется рамка, а справа отображается список свойств. Если рабочая область в фокусе, стрелки клавиатуры двигают объект.

Готовую шкалу можно скачать в удобном формате. SVG подходит, если изображение потом нужно загрузить в векторный графический редактор для доработки. Только этот формат является родным для программы, и такой файл можно будет в нее снова загрузить для редактирвоания. PNG подходит для печати или обработки растровыми редакторами. Чтобы распечатать шкалу в соответствии с выбранным размером, нужно чтобы совпадало разрешение экспорта с разрешением при печати. Это может быть, например, 300ppi (или dpi). Если изображение занимает весь лист, возможно понадобится убрать поля для правильного масштаба.


ПОМОЩЬ ПРОЕКТУ

При желании помочь развитию проекта, предлагается следующее:
- Сообщения об ошибках в работе программы с подробным описанием
- Коррекция языковых ошибок в интерфейсе, а также его перевод на новые языки. Образец языкового файла - lang/ru.json. Английского файла полного нет - этот язык принят оригинальным, и часть строк находится в исходном коде. Планируется также документация на русском и английском языках.
- Предложения по улучшению программы
- Присылка шкал, выполненных на основе распространенных форматов измерительных головок, приборов и т. п.
- Материальное содействие. Если программа понравилась, но помогать с ее развитием нет времени или желания - это один из вариантов содействия.

БЛАГОДАРНОСТЬ
- Использован JsViews MVVM фреймворк, которому желаю дальнейшего развития.
- Взяты небольшие функции из векторного редактора SVG-Edit
- Несколько шкал из примеров взяты в рисовалке шкал автора Starichok, опубликованной на forum.cxem.net


с уважением,
Александр Болоховецкий
soulmare@gmail.com
