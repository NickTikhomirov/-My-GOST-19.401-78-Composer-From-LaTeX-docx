# Мой сборщик документации по ГОСТ 19.401-78 "Текст Программы" в LaTeX

+ Титульник и таблица (первая и последняя страницы) хранятся в ./docx/(вордовский документ)
+ Его надо экспортировать в pdf названием title
+ Всё остальное делает за нас латех
+ Я брал из старого проекта, поэтому там может быть несколько лишних usepackage-ов
+ Шрифт по госту в подарок -- мне не пригодился
+ У вас не соберётся, потому что 173 файла на C# сидят в gitignore
+ Простой подход: кидать файлы в ./cs/ и подключать их через мой макрос "\getcode{<имя файла без пути>}" где-то в теле после аннотации
+ Приятного использования

Это НЕ универсальный инструмент, сделанный с любовью, это моё "блин курсач сдавать через три дня"

**В лично моём проекте вышло 273 страницы, которые скомпоновали за меня автоматически из моего кода, поэтому я уже доволен**
