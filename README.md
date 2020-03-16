# Набор всех тем, которые будет знать ученик, после js1 && js2


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
