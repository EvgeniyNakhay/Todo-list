# TODO List

Требования к проекту (бизнес логика) - какие функции проект должен выполнять (ЧТО должен проект выполнять, а не КАК):

1. Получить данные с сервера, отрисовывать их на странице.
2. Через форму создавать новые задачи, с отправкой запроса на сервер.
   Выбор пользователя из списка доступных.
3. Изменять статус завершенности по чекбоксу.
4. Удалять задачи.

UI (каким мы представляем себе интерфейс - то, с чем будет работать пользователь): 0. Шапка с название проекта.

1. Форма: текстовое поле, select для выбора пользователей и кнопка.
2. Список всех задач.
3. Задача:
   - Текст
   - Чекбокс
   - Крестик для удаления

Шаги:

0. Базовая разметка и стили.
1. Получение задач и пользователей с сервера.
2. Отрисовать задачи на странице.
3. Добавить пользователей в выпадающий список.
4. Логика добавления задачи.
5. Логика изменения статуса.
6. Логика удаления.
7. Информирование об ошибках.
