# JS
<details> 
  <summary> <b> HW_1 </b> </summary>
<pre> 1. Создать переменную “item_1” </pre>
<pre> 2. Присвоить переменной item_1 цифру 5.</pre>
<pre> 3. Вывести в консоль item_1. </pre>
<pre> 4. Создать переменную “item_2” </pre>
<pre> 5. Присвоить переменной item_2 цифру 3. </pre>
<pre> 6. Вывести в консоль item_2. </pre>
<pre> 7. Создать переменную “item_3” </pre>
<pre> 8. Присвоить переменной item_3 сложение item_1 и item_2. </pre>
<pre> 9. Вывести в консоль item_3. </pre>
<pre> 10. Создать переменную “item_4” </pre>
<pre> 11. Присвоить переменной item_4 строку “Yolochka” </pre>
<pre> 12. Вывести в консоль item_4. </pre>
<pre> 13. Вывести в консоль сложение item_3 и item_4. </pre>
<pre> 14. Вывести в консоль умножение item_3 и item_4. </pre>
<pre> 15. Создать переменную “item_5” </pre>
<pre> 16. Присвоить переменной item_5 переменную item_3 </pre>
<pre> 17. Создать переменную item_6. </pre>
<pre> 18. Создать переменную item_6_type </pre>
<pre> 19. Присвоить переменной item_6 значение 15 </pre>
<pre> 20. Присвоить переменной item_6_type тип переменной item_6 </pre>
<pre> 21. Вывести в консоль тип данных item_6 в виде ——  “item_6 == ”  item_6,  
 “item_6_type == ”  item_6_type ——  </pre>
<pre> 22. Создать переменную item_7 и в ней преобразовать item_6 в String. </pre>
<pre> 23. Создать переменную item_7_type </pre>
<pre> 24. Присвоить переменной item_7_type тип переменной item_7 </pre>
<pre> 25. Вывести в консоль тип данных item_7 в виде ——  “item_7 == ”  item_7, 
 “item_7_type == ”  item_7_type ——  </pre>
<pre> 26. Создать переменную “age_1” и присвоить ей значение 10 </pre>
<pre> 27. Создать переменную “age_2” и присвоить ей значение 18 </pre>
<pre> 28. Создать переменную “age_3” и присвоить ей значение 60 </pre>
<pre> 29. Создать if в котором будите проверять значение переменной age_1 </pre>
<pre> 30. Если age_1 < age_2, вывести в консоль “You don’t have access cause your age is ” + 
age_1 +  “ It’s less than ” + age_2 </pre>
<pre> 31. Если age_1 >=  age_2 и age_1 <  age_3, вывести в консоль “Welcome  !” </pre>
<pre> 32. Если age_1  > age_3, вывести в консоль “Keep calm and look Culture channel”. </pre>
<pre> 33. Иначе выводите “Technical work”. </pre>
## 
  <details>
<summary> <b> HW_1* Задания с разным количеством звездочек:) </b> </summary> 
<pre> 1*: Преобразовать написанный код в 26-33 пунктах в функцию, принимающую на вход возраст.
### Пример: const checkAge = function(age) {
### Ваши преобразования
### }
### Вывести в консоль результат работы функции с возрастами 17, 18, 61 
</pre>
### 2*:
### Преобразовать задание 1* таким образом, чтобы первым делом в функции проверялся тип данных. И если он не Number - кидалась ошибка.

### 3**:
### Преобразовать 2* таким образом, чтобы значение '2' (строка в которой лежит ТОЛЬКО ЦИФРА) пропускалось, преобразовываясь в number

### 4***:
### Преобразовать задание 3* таким образом, чтобы возраст вводится используя функцию prompt в привязанной верстке
</details>
##
## HW_2
### 1. Написать скриптик, который сосчитает и выведет результат от возведения 2 в степень 10, начиная со степени 1
###
### 1*. Преобразовать 1 задачу в функцию, принимающую на вход степень, в которую будет возводиться число 2
###
### 2. Написать скрипт, который выведет 5 строк в консоль таким образом, чтобы в первой строчке выводилось :), во второй :):) и так далее
### Пример в консоли:
### :)
### :):)
### :):):)
### :):):):)
### :):):):):)
###
### 2*. Преобразовать 2 задачу в функцию, принимающую на вход строку, которая и будет выводиться в консоль (как в условии смайлик), а также количество строк для вывода 
### e.g. function printSmile(stroka, numberOfRows)
###
### 3**.  Написать функцию, которая принимает на вход слово. Задача функции посчитать и вывести в консоль, сколько в слове гласных, и сколько согласных букв.
### e.g. function getWordStructure(word)
### В консоли: 
### Слово (word) состоит из  (число) гласных и (число) согласных букв
###
### Проверки: 'case', 'Case', 'Check-list'
###
### 4**. Написать функцию, которая проверяет, является ли слово палиндромом
### e.g. function isPalindrom(word)
###
### Проверки: 'abba', 'Abba'
</details>
##
## HW_3
### Task 1.
###
### Написать функцию, которая найдет и выведет в консоль юзеров, зарегистрированных 09.10.2021 и 10.10.2021). Массив в task1.txt
### 
### Task 2*
### 
### Откройте в VSCode task2.json файл. Скопируйте из него JSONку, вставьте в свой код (присвоив в переменную).
### 
### Дан массив объектов. Каждый объект является идентификационной карточкой человека. Нам нужно хранить только уникальные значения в этом массиве. Реализуйте функцию, ### которая будет выполнять эту работу.
### 
### Task 2*** Реализуйте считывание JSONки из файла task2.json с помощью, например, модуля fs. для дальнейшего использования в функции, описанной в задании
### 
### Task 3**
### В файле task3.txt найдете структуру компании и задания, необходимые выполнить.
### 
### Примечание: ВСЕ задания выполнять не обязательно, если вам люто сложно. Но ПЕРВОЕ - прям надо всем:)
### 
### Task 4****
### 
### В файле task4.txt вы найдете разноуровневый массив объектов. Очень похожий на массив из 3го задания, только количество вложенностей может быть не ограничено. 
### 
### Задание: написать функцию: 
### 
### Функция строит древовидный список компании.
### При ее вызове в консоль должен вывестись список подразделений компании с указанием количества сотрудников и с соблюдение вложенности подразделений.
##
## HW_ Massive
### Нужно написать функцию, которая принимает на вход два массива.
### Суть: функция убирает из массива А все значения, которые представлены в массиве Б, сохраняя нормальный порядок в массиве А
###
### Пример: arrayDiff([1,2],[1]) == [2]
### 
### Значения, находящиеся в массиве Б, и встречающиеся в массиве А  должны быть удалены
### 
### Пример: arrayDiff([1,2,2,2,3],[2]) == [1,3]
### 
### В выходном массиве пустых ячеек быть не должно, т.е. смещать надо элементы после удаления:)
##
## HW_Strings_2_Num
###
### В этой задаче мы хотим преобразовать строку в целое число. Строки просто представляют числа словами.
### 
### Примеры:
###
### "one" => 1
### "twenty" => 20
### "two hundred forty-six" => 246
### "seven hundred eighty-three thousand nine hundred and nineteen" => 783919
### Дополнительные примечания:
###
### Минимальное количество "ноль" (включительно)
### Максимальное количество, которое должно поддерживаться, составляет 1 миллион (включительно)
### "AND" в примере "one hundred and twenty-four" не обязательно, в одних случаях присутствует, а в других нет.
### Валидировать входящее число на то, что это число не нужно.
