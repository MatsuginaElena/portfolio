[Назад](../projects/ProjOne.md)

## Таблицы

<table>
<tr><td colspan="2" align="center">Students</td></tr>
</table>

| id  | firstname | lastname      | wherefrom |
|-----|-----------|---------------|-----------|
| 1   | Рюрик     | Рюрикович     | Область   |
| 2   | Олег      | Вещий         | Деревушка |
| 3   | Игорь     | Рюрикович     | Иваново   | 
| 4   | Ольга     | Игоревна      | Городок   |
| 5   | Святослав | Ольгович      | Новгород  | 
| 6   | Ярополк   | Святославович | Москва    | 

____
<table>
<tr><td colspan="2" align="center">Courses</td></tr>
</table>

| id  | title             | 
|-----|:------------------|
| 1   | QA                | 
| 2   | DevOps            | 
| 3   | DatabaseEngineer  | 
| 4   | Developer         | 
| 5   | QC                | 
| 6   | SystemAdmin       | 

____
<table>
<tr><td colspan="2" align="center">CourseContent</td></tr>
</table>

| id  | lesson                        | course_id |
|-----|:------------------------------|:----------|
| 1   | Чек-листы                     | 1         |
| 2   | Баг-репорты                   | 1         |
| 3   | Тест-кейсы                    | 1         |
| 4   | Запросы БД                    | 3         |
| 5   | Командная строка              | 6         |
| 6   | DevTools                      | 6         |
| 7   | Цикл-ПО                       | 4         |
| 8   | Анализ требований             | 4         |
| 9   | Декомпозиция требований       | 2         |
| 10  | Диаграмма связей              | 2         |
| 11  | Блок схема                    | 5         |
| 12  | Серые зоны                    | 5         |
| 13  | Функциональное тестирование   | 1         |
| 14  | Нефункциональное тестирование | 4         |

>CONSTRAINT Course_id FOREIGN KEY (course_id) REFERENCES Courses(id)


____
<table>
<tr><td colspan="2" align="center">StudentsCourses</td></tr>
</table>

| student_id | course_id | 
|------------|:----------|
| 1          | 1         | 
| 1          | 5         | 
| 2          | 3         | 
| 2          | 4         | 
| 3          | 6         | 
| 4          | 6         | 
| 4          | 1         | 
| 5          | 6         | 
| 5          | 2         | 
| 6          | 1         | 

<hr/> 

>CONSTRAINT Course_id FOREIGN KEY (course_id) REFERENCES Courses(id)
> 
>CONSTRAINT Student_id FOREIGN KEY (student_id) REFERENCES Students(id)





>> ## <b> [Задачи к таблицам](../projects/Tasks.md)</b>







