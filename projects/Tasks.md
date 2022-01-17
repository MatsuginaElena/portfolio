>[Назад](..../projects/RBD.md)


### Задачка 1

Вывести все шаги для изучения тест-анализа. Поля в результирующей таблице: learning
>> SELECT test-analysis AS learning FROM AnalysT;

### Задачка 2

Вывести названия всех шагов изучения QA (таблица Beginning).
>> SELECT begin FROM Beginning;

### Задачка 3

Вывести все имена, которые имеются в таблице (таблица Students).
>> SELECT DISTINCT FirstName FROM Students;

### Задачка 4

Вывести количество студентов (таблица Students). Поле называется quantity.
>> SELECT SUM (FirstName) AS quantity FROM Students;
