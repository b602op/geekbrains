# geekbrains
 lessons for GeekBrains

---
html/css
---

### верстка интернет магазина 
#### учник имеет
```
	indedx.html
	style.css
```
### Основы программирования
	- Переменные и типа данных
	- Циклы и ветвления
	- Массивы
	- Основы html

### git


---
js1
---


### 1. Основы js
		
		- объявление переменных
			var let const
		- браузер / работа с Console и Elements (остальные вкладки все на JS2) _если ученики не знакомы с текущей IDE - рассказать_
		- операторы (часть 1)
			++
			Логические операторы
			...

		- типы данных
			Boolean,
			Null,
			Undefined,
			Number,
			String,
			Object

		- операторы (часть 2)
			typeof
			...

		- Стандарты JS - минимум инфы
			Версия ES5 (вышла в декабре 2009 года)
			Версия ES6/ES2015 (вышла в июне 2015 года)
			Версия ES2016+

### 2. Условия и циклы
		- циклы - for while
		- Тернарный оператор
		- switch, if, else if


### 3. функции 
		- объявление функций
		- функция с return и без return
		- аргументы
		- this (кратко - основное на js2)

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
		- __proto__
		- hasOwnProperty
		- 2 переменные-ссылки на 1 объект
		- Сравнение 2ух объектов по ссылке
		- Object.keys, Object.values, Object.entries

		для js2
		- Геттеры / сеттеры
		- иммутабельность / мутабельность
		- Object.assign
		- Object spread ...
		- всё ли в js объекты?

### 6. DOM / window / document

### 7. Обработка событий

### 8. Около js темы		
		- Рекурсия
		- знакомство с сайтами по js


После каждого урока в ДЗ входит внедрение тематического кода в проект Магазина.
Параллельно Магазин должен разбиться на логические части, которые потом превратятся в компоненты. Или останутся как есть, для тех, кто уйдет в питон.


---
js2
---

### coming soon


---
всё в пермешку
---

# Набор всех тем, которые будет знать ученик, после js1 -> js2


### Основное

	1. Тег скприпт в браузере async, defer
	2. 'Use strict'
		+ var let const
	3. Типы данных:
		Boolean,
		Null,
		Undefined,
		Number,
		String,
		Object,
	4. typeof
	5. Приоритеты операций
	6. Оператор ++
	7. Логические операторы
	8. Тернарный оператор
	9. Циклы - for while
	10. Switch, if, else if
	11. Перемнные в памяти, объекты в памяти

### Массивы

	1. создание - [], new Array
	2. FOR OF
	3. Array.from()
	4. String.split()
	5. join()
	6. indexOf
	7. includes()
	8. length
	9. Push, pop, shift, unshift
	10. методы массива
			splice,
			slice
			concat
			spread opearator
			reverse()

	11. перебирающие методы:
			callback
			forEach
			Map
			Every/some
			filter
			Reduce


### Функции

	1. способы объявления
	2. работа с аргументами
		- как расширить входящие параметры
		- как узнать аргументы
			посмотрите в консоли такую запись
			function test() {
				console.log(arguments)
			}
			test(123, 'привет', {user: 'Иван'})
	3. this в функции
		- привязка this к функции
			-call
			-apply
			-bind
	4. рекусрия из функций
	5. функция с return и без return
	6. стрлочные функции
		- у стрелочной функции нет своего this!!
		- return можно не писать, но он будет (записи ниже для x и x2 одинаковые)
			let x = () => 3
			let x2 = () => {
				return 3
			}
	7. замыкание




### Объекты

	1. Пары ключ-значение
	2. Перезапись значения, свойство после создания
	3. Обращение к свойсва через []
	4. Обращение через .
	5. Переменные в []
	6. Вычисляемые свойства при создании объекта []
	7. Несуществующие свойства - undefined
	8. Оператор DELETE
	9. Оператор IN
	10. Оператор FOR IN
	11. Методы объектов (обычныая и короткая запись)
	12. Вложенные объекты
	13. Цикоическая ссылка
	14. Короткая запись свойств { prop }
	15. __proto__
	16. hasOwnProperty
	17. Геттеры / сеттеры
	18. 2 переменные-ссылки на 1 объект
	19. Сравнение 2ух объектов по ссылке
	20. иммутабельность / мутабельность
	21. Object.assign
	22. Object spread ...
	23. Object.keys, Object.values, Object.entries



### DOM

	1 Document
	2 Elements / Nodes
	3 Поиск по дому (querySelector, querySelectorAll, getElementById...)
	4 DOM collection => Array
	5 innerHTML / textContent
	6 className / classList
	7 createElement
	8 insertAdjacentHTML
	9 methods: append, prepend before, after
	10 Свойства и атрибуты
		getAttribute / setAttribute / hasAttribute
	11 свойства STYLE
	12 события addEventListener
	13 onclick