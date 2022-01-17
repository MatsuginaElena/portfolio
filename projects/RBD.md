>[Назад](../portfolio/RBD.md)

## Таблицы

<table>
<tr><td valign="top">
<table>
<tr><td colspan="2" align="center">Beginning</td></tr>
<tr><td>id</td><td>begin</td></tr>
    <tr><td>1</td><td>чек-листы</td></tr>
    <tr><td>2</td><td>баг-репорты</td></tr>
    <tr><td>3</td><td>тест-кейсы</td></tr>
    <tr><td>4</td><td>запросы БД</td></tr>
    <tr><td>5</td><td>командная строка </td></tr>
    <tr><td>5</td><td>DevTools</td></tr>
</table>
</td> <td>
<table>
<tr><td colspan="2" align="center">AnalysT</td></tr>
<tr><td>id</td><td>test-analysis</td></tr>
    <tr><td>1</td><td>цикл задачи</td></tr>
    <tr><td>2</td><td>анализ требований</td></tr>
    <tr><td>3</td><td>декомпозиция требований</td></tr>
    <tr><td>4</td><td>диаграмма связей</td></tr>
    <tr><td>5</td><td>блок-схема</td></tr>
    <tr><td>6</td><td>серые зоны и поиск требований</td></tr>
    <tr><td>7</td><td>функциональное тестирование</td></tr>
    <tr><td>8</td><td>нефункциональное тестирование</td></tr> 
</table>
</td> <td>
<table>
<tr><td colspan="4" align="center">Students</td></tr>
<tr><td>id</td><td>FirstName</td><td>LastName</td><td>Кукушки</td></tr>
    <tr><td>1</td><td>Иван</td><td>Иванов</td><td>Энгельс</td></tr>
    <tr><td>2</td><td>Петр</td><td>Петров</td><td>Воронеж</td></tr>
    <tr><td>3</td><td>Василий</td><td>Васильев</td><td>Самара</td></tr>
    <tr><td>4</td><td>Иван</td><td>Петров</td><td>Санкт-Петербург</td></tr>
    <tr><td>5</td><td>Петр</td><td>Иванов</td><td>Москва</td></tr>
    <tr><td>6</td><td>Василий</td><td>Петров</td><td>Мурманск</td></tr>
    <tr><td>7</td><td>Петр</td><td>Васильев</td><td>Пятигорск</td></tr>
    <tr><td>8</td><td>Иван</td><td>Васильев</td><td>Заполярный</td></tr> 
</table>
</td></tr>
</table>

<hr/> 

# Задачка 1

Вывести все шаги для изучения тест-анализа. Поля в результирующей таблице: learning
>> SELECT test-analysis AS learning FROM AnalysT;
 
 # Задачка 2

Вывести названия всех шагов изучения QA (таблица Beginning).
>> SELECT begin FROM Beginning;

# Задачка 3

Вывести все имена, которые имеются в таблице (таблица Students).
>> SELECT DISTINCT FirstName FROM Students;

# Задачка 4

Вывести количество студентов (таблица Students). Поле называется quantity.
>> SELECT SUM (FirstName) AS quantity FROM Students;






