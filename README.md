 # Итоговая проверочная работа.  
<br/>

### Задание:

1. Создать репозиторий на GitHub.

2. Нарисовать блок-схему алгоритма (можно обойтись блок-схемой основной содержательной части, если вы выделяете её в отдельный метод)
3. Снабдить репозиторий оформленным текстовым описанием решения (файл README.md)
4. Написать программу, решающую поставленную задачу
5. Использовать контроль версий в работе над этим небольшим проектом (не должно быть так что все залито одним коммитом, как минимум этапы 2, 3 и 4 должны быть расположены в разных коммитах)

Задача: Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

*Примеры:*

["hello", "2", "world", ":-)"] -> ["2", ":-)"]

["1234", "1567", "-2", "computer science"] -> ["-2"]

["Russia", "Denmark", "Kazan"] -> []

<br/>

### Решение:

1. Созданный репозиторий на GitHub: https://github.com/YarosLap/cw0323.git

2. Блок-схема алгоритма лежит в папке "Trinity_block_diagram".

3. Созданный текстовое описание README.md вы сейчас читаете.

4. Программа лежит в папке "Trinity_program".

5. Коммиты созданы.

<br/>

### Описание решения:

Объявляется два массива: изначальный и второй, аналогичной длины. Далее создаём метод, в котором цикл соразмерный длине массива, внутри цикла проверка условия меньше или равно трём. Если результат проверки "да", то элемент первого массива заносится в count элемент второго массива. Переменная count, чтобы поочередно закидывать из первого массива во второй и чтобы потом не было пробелов. После присвоения переменная count увеличивается на 1 и возвращается к циклу for в котором i увеличивается на 1. И так проверяется до конца.