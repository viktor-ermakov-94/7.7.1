SF_D4.4

1. Усовершенствовать ваш новостной портал. Добавить постраничный вывод и отдельную страницу с поиском /search/, чтобы пользователь мог сортировать новости по дате и имени автора.
2. Необходимо иметь возможность создавать новые новости и статьи не только из админки, но и в самом приложении. Для такой возможности необходимо создать модельные формы.
3. Необходимо добавить на сайт с помощью дженериков новые страницы /news/add/, а также /news/<int:pk>/edit/. На этих страницах пользователь может добавить или редактировать новости.
4. Добавьте страницу удаления новостей /news/<int:pk>/delete/. На ней после подтверждения пользователь может удалить страницу с новостью.

Что не получилось, это перенаправление с форм создания, редактирования и удаления постов на форму post_list с сохранением результатов поиска. То есть при возвращении на неё после создания, например, нового поста, она открывается всегда со сброшенным фильтром.
