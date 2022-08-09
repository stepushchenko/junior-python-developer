### Python - это:

- Строго типизированный язык
- Динамически типизированный язык
- Интерпретируемый язык
- Мультипарадигмальный язык

### Типы данных
`Подробнее https://stepik.org/course/97054/promo`

- списки (list),
- множества (set),
- байтовые массивы (byte arrays)
- словари (dict)
- целые числа (int),
- числа с плавающей запятой (float)
- булевы значения (bool)
- строки (str)
- кортежи (tuple)
- неизменяемые множества (frozenset)

**Классификация типов данных:**
- изменяемые (списки, словари и множества)
- неизменяемые (числа, строки и кортежи)
- упорядоченные (списки, кортежи, строки и словари)
- неупорядоченные (множества)

### Структуры данных

Структуры данных — это структуры кода для хранения и организации данных, <br> 
которые упрощают изменение, навигацию и доступ к информации. Структуры данных <br> 
определяют способ сбора данных, функциональные возможности, <br>
которые мы можем реализовать, и отношения между данными. <br>

`Подробнее https://bestprogrammer.ru/programmirovanie-i-razrabotka/8-struktur-dannyh-python`

- список
- массив
- очередь
- стеки
- связанные списки и циркулярно связанные списки
- деревья
- графы
- хеш таблицы
- словарь (в том числе OrderedDict и defaultdict() )
- кортеж

### Элементы языка
- Итераторы 
- Генераторы `Подробнее https://habr.com/ru/post/488112/`

### Functions
- Декораторы (functools.wraps в том числе) https://docs.google.com/presentation/d/1LCe2VMySjXsm84sYdC_GI71JnGiymeymeQglYqYr66A/edit#slide=id.g9f74094941_1_33
- *args и **kwargs 

### Classes
- 

### Базы данных: 
- ORM

### Потоки, процессы
`Подробнее http://onreader.mdl.ru/MasteringConcurrencyInPython/content/Ch06.html`
- Потоки (включая GIL)
  - mutexes
  - semaphore
- Процессы
- Межпроцессное взаимодействие
- Синхронное и асинхронное программирование

### Алгоритмы и прочие полезности
- Контекстные менеджеры
- Способы обхода графов
- Бинарный поиск
- Алгоритм сортировки

### Фреймворки
- Django
- Flask

### Смежные дисциплины
- Как рефакторить в python
- Как писать юнит тесты на свой код



### Job requirements

1. Алгоритмы и структуры данных (без привязки к языку программирования). Желательно знать, как устроены массивы,
связные списки, хеш-таблицы, множества, бинарные деревья поиска, графы. Какая сложность (в O-нотации) основных
операций при работе с ними. Могут также задать вопросы по базовым алгоритмам. Например, попросить рассказать
про основные алгоритмы сортировки, бинарный поиск или способы обхода графов.

2. Структуры данных в Python: примеры применения, различия, преимущества и недостатки. Будьте готовы отвечать
на вопросы про числовые типы данных, строки, списки, кортежи, множества и словари. Преимуществом будет знание
и опыт применения встроенных в язык структур данных, например, OrderedDict или defaultdict из модуля collections.

3. Изменяемые и неизменяемые типы данных в Python: в чём разница между ними, примеры использования.
Часто просят просто перечислить изменяемые и неизменяемые типы данных, которые вы знаете. Могут предложить
решить задачу и спросить, какой тип или какую структуру данных вы бы выбрали для её решения и почему.

4. Декораторы: что это такое и как они устроены. Могут, например, попросить написать код декоратора для
измерения времени работы функции или декоратора с параметром. Полезным будет знание functools.wraps.

5. Контекстные менеджеры: что это такое и для чего используют. Могут попросить реализовать контекстный
менеджер для работы с файлами, аналогичный встроенному open().

6. Генераторы и итераторы: что это такое, для чего они используются, какая между ними разница. Могут,
например, попросить написать генератор чётных чисел или чисел Фибоначчи.

7. GIL: зачем он нужен и как работает. Вопрос на собеседовании может быть такой: «Могут ли в Python
одновременно выполняться больше одного потока?» От начинающих специалистов обычно не требуют знаний
про GIL, но они могут выгодно выделить вас на фоне других кандидатов.

8. Как устроен один из популярных фреймворков, например Django или Flask. Хорошо, если вы понимаете его
сильные и слабые стороны. Могут попросить спроектировать базу данных для приложения, написать несколько
запросов с помощью ORM или на чистом SQL.

9. Как работает интернет: понимание модели/моделей OSI/TCP IP, основных протоколов. Популярный вопрос из
этого раздела: «Что происходит, когда в поисковой строке вбиваешь google.com?»

10. Утилиты командной строки. Могут попросить рассказать про пять – десять команд, которыми вы чаще всего
пользуетесь.

11. Потоки, процессы, асинхронное программирование. Например, в чём разница между потоком и процессом,
или какие способы межпроцессного взаимодействия вы знаете.

12. Логические и математические задачи: для их решения может понадобиться школьная математика, базовые
знания комбинаторики, теории вероятностей, умение работать с числами в разных системах счисления.