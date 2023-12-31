### **Автоматизация попарного тестирования фильтров выбора товара интернет магазина**

К**раткое описание проекта**

Имитировать выбор пользователем тех или иных фильтров чекбоксов для проверки работы функционала веб приложения

**Цели проекта** 

Создать инструмент, который должен будет сократить время на тестирование фильтров, позволит проводить проверки при увеличении их количества (фильтров), а также проверять новые категории товаров в случае их добавления. Существующий функционал инструмента автоматизации можно будет расширить в случае если это потребуется, например будет добавлен новый вид фильтров.

**Роль в разработке**

Участвовал в проекте в качестве тестировщика автоматизатора

**Выполненные задачи**

- Реализовал [возможность аутентификации](https://github.com/DimaSannikov/Graduation_project/blob/main/auth_wb.py) пользователя при тестировании без необходимости постоянного ввода логина и пароля, а также ожидания СМС кода от [Wildberries](https://www.wildberries.ru/)
- Разработал [функционал](https://github.com/DimaSannikov/Graduation_project/blob/main/pairwise_list_create.py) позволяющий собирать в список имена фильтров и использовать этот [список](https://github.com/DimaSannikov/Graduation_project/blob/main/translate_for_pict.txt) для генерации [наборов попарных тестов](https://github.com/DimaSannikov/Graduation_project/blob/main/pairwise.txt) с помощью [Pairwise Pict Online](https://pairwise.yuuniworks.com/)
- Разработал [функционал](https://github.com/DimaSannikov/Graduation_project/blob/main/testing_lists.py) который позволяет сопоставить имена фильтров интернет магазина и [списка требуемых проверок](https://github.com/DimaSannikov/Graduation_project/tree/main/testlists)
- Создал [инструмент](https://github.com/DimaSannikov/Graduation_project/blob/main/checkboxes_test.py) который позволяет осуществлять попарные проверки фильтров выбора товара интернет магазина Wildberries

**Достигнутые цели**

Был создан инструмент автоматизации цель которого сократить время требуемое на тестирование фильтров выбора товара интернет магазина. Данный инструмент можно использовать для любой категории товара веб приложения. На данный момент функционал инструмента автоматизации достаточен для того чтобы проверять существующую логику работы фильтров выбора товара в веб приложении. Представленный инструмент позволяет проверять работоспособность фильтров в случае появления новой категории товаров, увеличении количества списков фильтров.

[Видео работы инструмента автоматизации](https://drive.google.com/file/d/1mnTt2INzASYLVOaZHL8HckRoR2y640tX/view?usp=sharing)