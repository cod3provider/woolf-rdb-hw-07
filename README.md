*********************** UA

1. Напишіть SQL-запит, який для таблиці orders з атрибута date витягує рік, місяць і число.
   Виведіть на екран їх у
   три окремі атрибути поряд з атрибутом id та оригінальним атрибутом date (всього вийде 5 атрибутів).

2. Напишіть SQL-запит, який для таблиці orders до атрибута date додає один день. На екран виведіть атрибут id,
   оригінальний атрибут date та результат додавання.

3. Напишіть SQL-запит, який для таблиці orders для атрибута date відображає кількість секунд з початку відліку (
   показує його значення timestamp). Для цього потрібно знайти та застосувати необхідну функцію. На екран виведіть
   атрибут
   id, оригінальний атрибут date та результат роботи функції.

4. Напишіть SQL-запит, який рахує, скільки таблиця orders містить рядків з атрибутом date у межах між 1996-07-10 00:
   00:00 та 1996-10-08 00:00:00.

5. Напишіть SQL-запит, який для таблиці orders виводить на екран атрибут id, атрибут date та JSON-об’єкт {"id": <
   атрибут id рядка>, "date": <атрибут date рядка>}. Для створення JSON-об’єкта використайте функцію.




*********************** EN

1. Write an SQL query that extracts the year, month, and day from the 'date' attribute in the 'orders' table. Display
   them on the screen in three separate attributes alongside the 'id' attribute and the original 'date' attribute (total
   of 5 attributes).

2. Write an SQL query that adds one day to the 'date' attribute in the 'orders' table. Display the 'id' attribute, the
   original 'date' attribute, and the result of the addition on the screen.

3. Write an SQL query that displays the number of seconds from the beginning of the epoch for the 'date' attribute in
   the 'orders' table (displaying its timestamp value). To achieve this, you need to find and apply the necessary
   function. Display the 'id' attribute, the original 'date' attribute, and the result of the function's operation on
   the screen.

4. Write an SQL query that counts how many rows the 'orders' table contains with the 'date' attribute within the range
   between '1996-07-10 00:00:00' and '1996-10-08 00:00:00'.

5. Write an SQL query that outputs the 'id' attribute, the 'date' attribute, and a JSON object {"id": <row's id
   attribute>, "date": <row's date attribute>} for the 'orders' table. Utilize a function to create the JSON object.
