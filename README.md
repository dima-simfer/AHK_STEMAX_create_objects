# AHK_STEMAX_create_objects
Массовое создание объектов в ПО STEMAX Администратор используя AutoHotKey (должен быть предварительно установлен).

Скрипт добавляет нужное количество ячеек с заданным названием и выбранным шаблоном. Актуально, когда нужно создать 10-20-100 ячеек для Болида, Рубежа и т.д.

Запускать обязательно используя меню ПКМ/Run with UI Access (появится после установки AHK)

Шаг 1: создаём в STEMAX Адмнистраторе одну идеальную ячейку, полностью заполненную, с ответственными, режимами и т.д.
Шаг 2: Создаём в STEMAX Администраторе на основе этой ячейки шаблон. ВАЖНО: Название шаблона должно быть без кавычек, иначе шаблон не создастся.
Шаг 3: Пишем название нашей идеальной ячейки в фильтр сверху STEMAX Администратора, чтобы убрать ненужные группы и другие ячейки в текущей группе.
Шаг 4: Запускаем скрипт (Run with UI Access), пишем название свежесоздаваемых ячеек, название шаблона, заполняем другие поля, нажимаем кнопку ПУСК.

ВАЖНО! При нажатии кнопки "Пуск" все группы должны быть свёрнуты (кнопкой F12 или мышкой).

Время для создания карточки и применения шаблона - ставим больше, если после зоздания объекта появляется окно создания группы, или меньше, если заметно, что после создания ячейки большая пауза.
