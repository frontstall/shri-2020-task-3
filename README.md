# Задание 3. Найдите ошибки

Ход мыслей:
- в файле server.js увидел ошибку типизации, открыл доку, посмотрел
допустимые параметры, передал подходящий
- там же увидел ошибку типизации property.key.loc, вспомнил сигнатуру объекта property, поправил
- стили не подтянулись, открыл девтулз вебвью, увидел ошибку, посмотрел в доке схему, поправил
- пошёл в стили, увидел там селектор по классу, поправил на селектор
по тегу
- html не подставляется в body, обложился консоль.логами, выяснил, что
колбек replace не срабатывает, подебажил регулярку в сервисе теста регулярок, поправил квантифаеры
- подгрузил свои стили и скрипты
- в консоли сервера увидел, что в парсер передаётся строка адреса. Поискал по цепочке функций, где это происходит, поменял свойство на метод, получающий содержимое файла
- обход дерева начал работать, но ошибок не возникало (я использовал тестовый файл с помещенными туда багами). Разобрался с алгоритмом, у меня в решении второго таска похожий - обход дерева с колбэком, который выполняет сайдэффект: наполняет заранее определенный аккумулятор. Заметил, что побочных эффектов нет, обнаружил concat вместо push.
- Стало понятно, что проверка наличия поля 'block' работает некорректно.
Не придумал ничего лучше, как сделать проверку с помощью утиной типизации, заработало.
- Потестил изменение настроек, заметил, что при выборе типа уведомления "Error" подчеркивает синей линией вместо красной. Поправил.