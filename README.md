# 24.1 Вьюсеты и дженерики

_____

### Основное задание

* Создайте новый Django-проект, подключите DRF в настройках проекта.

* Создайте следующие модели:

Пользователь:
все поля от обычного пользователя, но авторизацию заменить на email;
телефон;
город;
аватарка.
Модель пользователя разместите в приложении users

Курс:
название,
превью (картинка),
описание.
Урок:
название,
описание,
превью (картинка),
ссылка на видео.

* Опишите CRUD для моделей курса и урока. Для реализации CRUD для курса используйте Viewsets, а для урока -
  Generic-классы.

Для работы контроллеров опишите простейшие сериализаторы.


_____

###  * Дополнительное задание

Реализуйте эндпоинт для редактирования профиля любого пользователя на основе более привлекательного подхода для личного
использования: Viewset или Generic.

______

### Критерии выполнения заданий

* Результат задания залили в github.com и сдали в виде ссылки на репозиторий.

______