#  Итоговая работа
`Задание:`Выбрать из массива строк те строки, длинна которых меньше или равна трем

`Решение:` решаем используя три метода.
1. Метод **Array** - запрашивает у пользователя любые значения и заполняет ими создаваемый массив
2. Метод **PrintArray** - распечатывает заданный массив
3. Метод **MinArray** - создает новый массив, состоящий из элементов созданного ранее массива, длина которых меньше или равна трем.

Боле подробно о третьем методе, 
- сначала, в цикле, подсчитываем сколько в первом массиве элементов, длина которых меньше или равна трем. Это количество будет длинной нового массива;
- далее создаем новый массив с длинной, которую мы определили на первом цикле;
- во втором цикле записываем в созданный массив те элементы из старого массива, длинна которых меньше или равна трем;
- возвращием этот заполненный массив.