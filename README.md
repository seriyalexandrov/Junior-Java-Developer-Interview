# Материалы к собеседованию Junior Java Developer (младший Java разработчик) (В разработке)

Обзор знаний, необходимых (но не всегда достаточных!) для прохождения интервью на позицию Junior Java Developer

## Общее
 - UML диаграммы, основные виды связей
 - XML
   - Синтаксис
   - Well-formed XML
   - XSD (Общее понимание)
   - XLST (Общее понимание)
   - Преимущества/Недостатки
 - JSON
   - Синтаксис
   - Применение
   - Преимущество/Недостатки
 - Системы контроля версий
   - Git
   - SVN
   - Обоснование применения
   - Ветки
   - Слияние (Merge)
   - Конфликты
 - Отладка
   - Debug, удаленный debug
   - Логирование
     - Преимущества по сравнению с распечаткой
     - Примеры современных бибиотек Java
     
## Java Basics
 - Байткод, Java-машина, Garbage Collector
 - Типы данных, переменные, массивы, autoboxing
 - If, while, for, break, continue, return, switch-case
 - Классы, поля, методы, объекты, интерфейсы, this, super
 - Перегрузка(Overload) методов, аргументы функций
 - Static, final
 - Вложенные классы, виды, применение
 - Exceptions
   - checked/uncheked
   - throw, throws, try, catch, finally
   - try-with-resources
   - stacktrace, анализ stacktrace
 - Модификаторы доступа
 - Enums
 - Класс Object
 - Классы String, StringBuilder, StringBuffer
 - Интернирование строк
 - Equals и HashCode
 - Generics
 - Java Collections - принципы работы, сложность операций. 
   - Иерархия классов
   - Map (HashMap)
   - Set (HashSet, TreeSet)
   - List (ArrayList, LinkedList)
 - Serialization/Marshalling
 - Reflection. Создание объектов, вызов методов, доступ к полям
 - Java I/O

## Java Advanced
 - Multitheading
   - JMM - понимание что, зачем
   - Классы Thread, Runnable
   - Кэши процессора, барьеры
   - synchronized, final, volatile, мониторы
   - wait/notify/notify all
   - Прерывание потоков, interrupted, InterruptedException
   - Thread-safe Collections
     - synchronizedList,Map, etc.
     - ConcurrentHashMap
     - CopyOnWriteArrayList
     - BlockingQueue
   - Executor, Thread-pool
   - ThreadLocal
   - Semaphore, CountDownLatch, CyclicBarrier
   - Locks, ReentrantLock, ReentrantReadWriteLock, Fair/Unfair
   
   
 
## Объектно-Ориентированное программирование
 - Парадигмы
   - Инкапсуляция, реализация в Java
   - Наследование, реализация в Java
   - Полиморфизм, реализация в Java
 - Принципы проектирования программного кода
   - SOLID
 - Инверсия зависимостей
 - Абстрактные классы и интерфейсы
 - Порождающие шаблоны проектирования
   - Builder
   - Factory
 - Структурные шаблоны проектирования
   - Adapter
   - Decorator
 - Поведенческие шаблоны проектирования
   - Strategy
   - Iterator
   - Observer

 
## Алгоритмы и структуры данных (без привязки к языку программирования)
 - Массив
   - Применение
   - Вставка/Удаление
   - Поиск по индексу/значению
 - Связный список
   - Применение
   - Вставка/Удаление
   - Поиск
 - Деревья
   - Сбалансированные/Несбалансированные деревья
   - Обход в ширину/глубину
   - Поиск
   - Вставка/Удаление
   - Применение в СУБД
 - Хэш-таблица
   - Вставка/Удаление
   - Преимущества/Недостатки
   - Поиск
   - Хэш-функция
   - Метод построение хэш-таблицы
   - Применение
 - Базовые алгоритмы сортировки
   - Пузырьком
   - Вставками
   - Quicksort
   
 ## Компьютерные сети
 - HTTP
   - Принцип работы
   - Структура пакета
   - Применение
 - TCP/UDP
 - IP
 - Ethernet
 - IP и MAC адреса
 - Switch (Коммутатор), Router (Маршрутизатор)
 
 ## Разработка Enterprise систем
  - REST API
    - Принципы
    - Реализация на Java (Любой вариант: Jersey, Spring, Vertex, ...)
  - 

 ## Реляционные БД, SQL
  - Популярные реляционные БД
  - Понятие и применение SQL
  - Структура простого запроса
  - ORDER BY
  - GROUP BY, HAVING
  - Join
    - Inner
    - Outer
    - Cartesian
    - Natural
  - DML
  - DDL
  - Индексы, план запроса
  - PL/SQL (общее понимание, область применения)
  - Однострочные функции
  - Подзапросы в разных блоках (select, from, where)
  - Иерархические запросы
  - Агрегатные функции
  - Аналитические функции
  
  
