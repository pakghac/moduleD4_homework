# moduleD4_homework
Усовершенствоваy новостной портал. Добавлен постраничный вывод и отдельная страница с поиском /search/, чтобы пользователь мог сортировать новости по дате и имени автора.
Создана возможность создавать новые новости и статьи не только из админки, но и в самом приложении. Для этого созданы модельные формы.
Добавлены на сайт с помощью дженериков новые страницы /news/add/, а также /news/<int:pk>/edit/. На этих страницах пользователь может добавить или редактировать новости.
Добавлена страница удаления новостей /news/<int:pk>/delete/. На ней после подтверждения пользователь может удалить страницу с новостью.
