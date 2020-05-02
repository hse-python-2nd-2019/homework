## Инструкция по выполнению финального проекта

**Важно:** финальный проект -- это экзамен по этому курсу, то есть последний элемент контроля. Вес проекта -- 2 балла от итоговой оценки за курс. Проект -- индивидуальное задание. Вы можете выбрать один из шаблонов из таблички внизу, можете предложить свою тему. Один шаблон могут выбрать несколько человек, но варьирующие элементы шаблона должны быть у каждого свои.

Код проекта должен быть выложен в репозиторий, а также на `pythonanywhere` или `heroku`, если Вы делали бот/веб-сервис. Т.е. веб-сервис или телеграм-бот должен работать вне зависимости от того, запущен ли код на вашем/чьем-то другом компьютере. Ссылка на ваше pythonanywhereapp или herokuapp должна быть в `README` в папке с проектом.

**Timeline**:

- до 11 мая -- выбрать шаблон/тему и вписать её в табличку. **Шаблон/тему нужно будет вписать вот в эту табличку.**
- до 18 мая -- мы прокомментируем ваш выбор
- **8 июня 23:59** -- дедлайн сдачи проекта
- 9 июня -- обсуждение проектов на парах

№|Шаблон|Описание|Что выбрать самостоятельно
-|------|--------------------------|----
1.|«Гарри Поттер и...»|Веб-сервис/телеграм-бот, который присылает пользователю фразы, сгенерированные с помощью марковской цепи.|Данные, на которых будет обучаться марковская цепь, сходные по объему со [всеми книгами о Гарри Поттере](https://www.dropbox.com/s/gg62ggme0hi7zqk/%D0%94%D0%B6%D0%BE%D0%B0%D0%BD%20%D0%A0%D0%BE%D1%83%D0%BB%D0%B8%D0%BD%D0%B3.%20%D0%93%D0%B0%D1%80%D1%80%D0%B8%20%D0%9F%D0%BE%D1%82%D1%82%D0%B5%D1%80%20%282018%29.fb2?dl=0)
2.|Анекдоты|Веб-сервис/телеграм-бот, который по заданному персонажу находит в корпусе анекдоты о нем|Это тема для одного человека
3.|Толстой или компьютер?|Веб-сервис/телеграм-бот, который играет с пользователем в игру: предлагает угадать, оригинальное ли перед ним предложение какого-либо автора или сгенерированное компьютером с помощью word2vec. В конце показывает результат пользователя и статистику правильных ответов.|Автора, в произведениях которого будут заменяться слова.
4.|Пушкин каждый день|Веб-сервис/телеграм-бот, который в ответ на реплику пользователя отвечает строчкой из какого-либо русского поэта в рифму|Можно сделать либо веб-сервис, либо телеграм-бота; можно взять как стихи какого-нибудь одного поэта, так и нескольких (лучше всего использовать поэтический корпус НКРЯ
5.|Бот-рифмоплет|Веб-сервис/телеграм-бот, который генерирует стихотворение со словом, которые ввел пользователь|Можно сделать либо веб-сервис, либо телеграм-бота; можно выбрать формат стихов: пирожки, порошки, рифмованные двустишия, хайку...
6.|Новостные тренды|Веб-сервис, которое периодически скачивает новости с  любого сайта, где они есть (от "Известий" до главной страницы Школы лингвистики) и строит график совместной встречаемости полнозначных слов в окне 3.| Новостной сайт
7.|Все, что вы хотели знать о...|Веб-сервис, которое по id пользователя/сообщества Вконтакте выводит график самых частотных полнозначных слов на заданнный период времени, а также статистику по комментаторам: город, пол, возраст|Это тема для одного человека
8.|«...» Вконтакте|Веб-сервис, который обращается к заданному набору сообществ Вконтакте на определенную тему, скачивает последние 300 записей и строит графики частотности ключевых слов по этой тематике (их набор, 10-20 штук, вы определяете самостоятельно). Для каждого сообщества должен быть отдельный график, + график-сравнение по всем сообществам|Тематику, набор сообществ вк по этой тематике и ключевые слова
9.|The PenPal|Веб-сервис, где пользователь вводит текст, а программа автоматически ему отвечает. Необходимо обеспечить определённую степень связности между тем, что пишет пользователь, и тем, что отвечает программа. Ожидается, что будут комментарии или отдельный текстовый файл, объясняющий, как обеспечивается связность. Для этого нужно использовать пройденные темы (в любых комбинациях): регулярные выражения, морфологический анализ, word2vec, VK API и т.д. |Выбрать "персону" программы: она может сочувствовать, ругать, давать советы и т.п.
10.|Fieldwork Crowdsourcing|Веб-сервис, который позволяет носителям (малых) языков и лингвистам, занимающимся этими языками, добавлять тексты и другие материалы (можно выбрать жестовый язык, тогда добавляться будут фото и видео). Программа создаёт базу данных, в которой хранятся тексты (видео, фото), социолингвистическая информация о добавивших тексты (видео, фото). Есть страница поиска (по словам, по социолингвистическим параметрам); есть страница, отражающая статистику по социолингвистическим параметрам.| Выбрать язык (стартовые материалы по языку можно выкачать из интернета), выбрать конкретные параметры, которые веб-сервис будет позволять добавлять.|
11.|Кластеризация векторного пространства|Взять глагол (например, *искать*) и список существительных, которые часто занимают позицию субъекта или объекта при этом глаголе (можно извлечь самые частотные из НКРЯ). Взять любую предобученную векторную модель с rusvectores.org и извлечь оттуда вектор для глагола и каждого существительного из своего списка. На основе этих векторов построить репрезентацию для каждой пары «глагол + существительное» с помощью простой аддитивной модели композиции (Если каждый вектор – это объект типа array в модуле numpy, то можно просто сложить эти два объекта, используя оператор «+»).Собрать все векторные представления пар в единую матрицу и кластеризовать их. Прокомментировать результат.|Выбрать глагол, выбрать метод кластеризации (метод иерархической кластеризации; метод главных компонент; граф, разбитый на сообщества)|
12.|Своя тема|Необходимо использовать как минимум 3 пройденных за год темы (в любых комбинациях): например, VK API, matplotlib, морфологический анализ; flask, word2vec, графы и т.д.|