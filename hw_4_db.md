## Домашнее задание 4

**Тема: базы данных**

**Дедлайн: четверт 7.11 23:59**

**Важное: работы принимаются строго в ipynb (не скрипт, не скрипт в ячейке ipynb)**

**Данные**

Датафрейм, полученный вами на книге по вашему выбору в домашнем задании на морфологию + виз. В нём должны быть колонки для слова, леммы, части речи и всех граммем для существительных, прилагательных и глаголов. (Можно взять файл из семинара по визуализации с распарсенным текстом Толстого - `tolstoy.csv`. Лежит и в папке с дз тоже.)

**Задание**

Создать новую базу данных из датафрейма. В ней должно быть несколько таблиц. В главной таблице будет колонка с первичным ключом wordId для каждой слофоформы, колонка со словоформой и колонка с леммой. И две отдельные таблицы по частям речи: одна для существительных, одна для глаголов. В таблице для существительных должен быть ключ nounId совпадающий по значениям с ключом wordId из главной таблицы для существительных. Также в таблицы для существительных должны быть все колонки граммем, свойственных существительным и на них должно стоять ограничение IS NOT NULL. То есть все разборы должны быть полными. Аналогичная схема для таблицы с глаголами.


Пункты:

1. Создать главную таблицу в новой базе данных.
  - (Сначала сократите датафрейм. Удалите из него все части речи кроме глаголов и существительных.)
  - wordId как первичный ключ для каждой словоформы
  - колонки word и lemma

(Для пунктов 2 и 3 стоит написать общую функцию)

2. Создать таблицу с глаголами в той же базе данных
  - использованы все граммемы глаголов
  - запрещены нулевые значения
  - verbId соответствует значениям wordId для глаголов в главной таблице

3. Создать таблицу с существительными в той же базе данных
  - использованы все граммемы существительных
  - запрещены нулевые значения
  - nounId соответствует значениям wordId для существительных в главной таблице

4. Напишите запрос к вашей базе данных, который распечатает первые пять лемм глаголов (fetchmany)


**Чек-лист**

1. Тетрадка с кодом
2. Получившаяся база данных

Если у вас есть вопросы, задавайте в чате или пишите преподавателям

### Критерии оценки
  
<table>
    <tr><th>Балл</th><th>Критерий</th></tr>
    <tr><td>1 балл</td><td>Пункт 1</td></tr>
    <tr><td>1 балл</td><td>Пункт 2</td></tr>
    <tr><td>1 балл</td><td>Пункт 3</td></tr>
    <tr><td>1 балл</td><td>Пункт 4</td></tr>
</table>

**Ссылки на GiHub Classroom:**

Группа 1 и 2 -- [ссылка](https://classroom.github.com/a/o5z1WLGY)

Группа 3 -- [ссылка](https://classroom.github.com/a/YTnFWDfI)

Группа 4 -- [ссылка](https://classroom.github.com/a/_zz8yBaJ) 
