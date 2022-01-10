>[Назад](../projects/ProjOne.md)

## Валидация полей
<i><small>Окружение: Chrome Версия 96.0.4664.93</small></i>
>Поле ввода "Ваш логин:"
>
   <table>
<tr><th>Название класса</th><th>Границы</th><th>Тестовыетданные внутри класса</th><th>Тестовые данные на границах</th><th>Пояснение</th></tr>
    <tr><td>Количество символов</td><td>2,30</td><td>15</td><td>1,2,3/29,30,31</td><td>Проверка количества длины символов</td></tr>
    <tr><td>Позитивная только англ</td><td>2,30 </td><td>il, ilovedyouilovedyouilovedyouyou</td><td>il, ilovedyouilovedyouilovedyouyou</td><td>Сначала позитив (по документации только англ)</td></tr>
    <tr><td>Негативная только англ</td><td>1,31</td><td>i, ilovedyouilovedyouilovedyouyoui</td><td>i, ilovedyouilovedyouilovedyouyoui</td><td>Негатив</td></tr>
    <tr><td>Заглавные англ буквы</td><td>все или частично</td><td>Iopento, openToWork</td><td>BIGWORD</td><td>Уточнить, в документации серая зона</td></tr>
    <tr><td>Специальные символы</td><td>%.;№";</td><td>I&#Need%#@</td><td>^%$#@!*&^%$#</td><td>Сначала позитив</td></tr>
    <tr><td>Цифры</td><td>1-9</td><td>Iwill1havejob</td><td>123456789</td><td>Потом негатив</td></tr>
    <tr><td>Кириллица</td><td>а...я</td><td>яваслюбилчегоже</td><td>БОЛЕЧТОЯМОГЕЩЕСКАЗАТЬ</td><td>Возьмите меня стажером</td></tr>
    <tr><td>Тире</td><td>В начале,в конце, в середине букв</td><td>I-love-QA</td><td>-Ilove, I-need, Work-</td><td>По оракулам в середине может быть пробел. Надо учтонять документацию.</td></tr>
    <tr><td>Пробел</td><td>В начале и в конце букв</td><td>(пробел)Ineed, Job(пробел)</td><td>(пробел)IopenToWork(пробел)</td><td>По оракулам должен удаляться, но надо учтонять - серая зона</td></tr>
    <tr><td>Пробел</td><td>В середине букв</td><td>I loveQA</td><td>Iopen(пробел)ToWork</td><td>Это серая зона - уточнять надо</td></tr>
    <tr><td>Точка</td><td>В начале,в конце, в середине букв</td><td>I.Love</td><td>.ILove, QA.</td><td>Попросить добавить в документацию, что точку нельзя</td></tr>
    <tr><td>NULL</td><td>Пустое поле</td><td>NULL</td><td>NULL</td><td>Должна быть описана ошибка в документации</td></tr>

</table>

>Поле ввода "Пароль:"
>
   <table>
<tr><th>Название класса</th><th>Границы</th><th>Тестовыетданные внутри класса</th><th>Тестовые данные на границах</th><th>Пояснение</th></tr>
    <tr><td>Количество символов</td><td>2,30</td><td>15</td><td>1,2,3/29,30,31</td><td>Проверка количества длины символов</td></tr>
    <tr><td>Позитивная только англ</td><td>2,30 </td><td>il, ilovedyouilovedyouilovedyouyou</td><td>il, ilovedyouilovedyouilovedyouyou</td><td>Сначала позитив (по документации только англ)</td></tr>
    <tr><td>Негативная только англ</td><td>1,31</td><td>i, ilovedyouilovedyouilovedyouyoui</td><td>i, ilovedyouilovedyouilovedyouyoui</td><td>Негатив</td></tr>
    <tr><td>Заглавные англ буквы</td><td>все или частично</td><td>Iopento, openToWork</td><td>BIGWORD</td><td>Уточнить, в документации серая зона</td></tr>
    <tr><td>Специальные символы</td><td>%.;№";</td><td>I&#Need%#@</td><td>^%$#@!*&^%$#</td><td>Сначала позитив</td></tr>
    <tr><td>Цифры</td><td>1-9</td><td>Iwill1havejob</td><td>123456789</td><td>Потом негатив</td></tr>
    <tr><td>Кириллица</td><td>а...я</td><td>яваслюбилчегоже</td><td>БОЛЕЧТОЯМОГЕЩЕСКАЗАТЬ</td><td>Возьмите меня стажером</td></tr>
    <tr><td>Тире</td><td>В начале,в конце, в середине букв</td><td>I-love-QA</td><td>-Ilove, I-need, Work-</td><td>По оракулам в середине может быть пробел. Надо учтонять документацию.</td></tr>
    <tr><td>Пробел</td><td>В начале и в конце букв</td><td>(пробел)Ineed, Job(пробел)</td><td>(пробел)IopenToWork(пробел)</td><td>По оракулам должен удаляться, но надо учтонять - серая зона</td></tr>
    <tr><td>Пробел</td><td>В середине букв</td><td>I loveQA</td><td>Iopen(пробел)ToWork</td><td>Это серая зона - уточнять надо</td></tr>
    <tr><td>Точка</td><td>В начале,в конце, в середине букв</td><td>I.Love</td><td>.ILove, QA.</td><td>Попросить добавить в документацию, что точку нельзя</td></tr>
    <tr><td>NULL</td><td>Пустое поле</td><td>NULL</td><td>NULL</td><td>Должна быть описана ошибка в документации</td></tr>

</table>