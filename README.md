После каждого урока в ДЗ входит внедрение тематического кода в проект Магазина.
Параллельно Магазин должен разбиться на логические части, которые потом превратятся в компоненты. 
(Или останутся как есть, для тех, кто уйдет в питон.)


# js1

### 1. Основы js
		
		- синтаксис js
		  Вставка скрипта script.js в HTML
		  Объявление переменных (var let const)
		  JavaScript не жестко типизированный язык
		  Как ставятся комментарии в js

		- браузер / работа с Console и Elements (остальные вкладки все на JS2) _если ученики не знакомы с текущей IDE - рассказать_

		- операторы (часть 1)
			++
			Логические операторы
			...

		- типы данных
			Boolean
			Null
			Undefined
			Number
			String
			Object
      Symbol() - попросить учеников, чтобы тут же это забыли
      BigInt() - попросить учеников, чтобы тут же это забыли

		- операторы (часть 2)
			typeof
			...

    - 3 вида ошибок + 1
      RefernceError
      TypeError
      SyntaxError
      +
      Логические ошибки ( ошибок в консоли нет, но в программе есть )

		- Стандарты JS - минимум инфы
			Версия ES5 (вышла в декабре 2009 года)
			Версия ES6/ES2015 (вышла в июне 2015 года)
			Версия ES2016+

### 2. Условия и циклы
		- циклы - for / do while / while
		- Тернарный оператор
		- switch, if, else if


### 3. функции 
		- function expressions, function declarations
    - оператор rest (spread) в определении функции
    - область видимости функций
		- функция с return и без return
		- аргументы
		- this (кратко - основное на js2)
    - рекурсия

		_показать как можно больше разных функций_
		~объяснения

### 4. массивы 
		- объявление массива
			[]
			new Array

		- Оператор
			FOR OF

		- Работа с массивом
			indexOf
			length
			Push, pop, shift, unshift
			Array.from()
			String.split()
			join()
			includes()

		- методы массива
			splice,
			slice
			concat
			spread opearator
			reverse()

		- перебирающие методы:
			callback
			forEach
			Map
			Every/some
			filter
			Reduce

    - деструктуризация массива

### 5. объекты
		- объявление объекта
		- Пары ключ-значение
		- Перезапись значения, свойство после создания
		- Обращение к свойсва через []
		- Обращение через .
		- Переменные в []
		- Вычисляемые свойства при создании объекта []
		- Несуществующие свойства - undefined
		- Оператор DELETE
		- Оператор IN
		- Оператор FOR IN
		- Методы объектов (обычныая и короткая запись)
		- Вложенные объекты
		- Циклическая ссылка
		- Короткая запись свойств { prop }
		- 2 переменные-ссылки на 1 объект
		- Сравнение 2ух объектов по ссылке
		- Object.keys, Object.values, Object.entries
    - деструктизация объекта

		для js2
		- Геттеры / сеттеры
		- иммутабельность / мутабельность
		- Object.assign
		- Object spread ...
    - __proto__
		- hasOwnProperty
		- всё ли в js объекты?

### 6. DOM / window / document
		- Document
		- Elements / Nodes
		- Поиск по дому (querySelector, querySelectorAll, getElementById...)
		- DOM collection => Array
		- innerHTML / textContent
		- className / classList
		- createElement
		- insertAdjacentHTML
		- methods: append, prepend before, after
		- Свойства и атрибуты
			getAttribute / setAttribute / hasAttribute
		- свойства STYLE

### 7. Обработка событий
		- события addEventListener
			'click'
			'mouseover/mouseout'
			'mousedown/mouseup'
			'mousemove'
			'submit'
			'focus'
			'contextmenu'
			и т.д.
		- onclick
    - setTimeout, setInterval, clear

### 8. Базовые принципы ООП / патерны
    - Абстракция
    - Полиморфизм
    - Наследование
    - Инкапсуляция

    - патерны на выбор, примеры
		


