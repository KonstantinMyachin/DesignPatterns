# Proxy (Заместитель)

**Заместитель** - предоставляет суррогатный объект, управляющий допступом к другому объекту.

## Применимость

* Ленивая инициализация (**виртуальный прокси**). Когда у Вас есть тяжелый объекты, грузящий данные из файловой системы 
или базы данных;
* Защита доступа (**защищающий прокси**). Когда в программе есть типы пользователей, и Вам хочется защитить объект от 
неавторизованного досутупа. Например, если Ваши объекты - это важная часть операционной системы, а пользователи - 
сторонние прогарммы (хорошие или вредоностоные);
* Локальный запуск сервиса (**удаленный прокси**). Когда настоящий сервисный объект находится на удаленном сервере;
* Логирование запросов (**логирующий прокси**). Когда требуется хранить историю обращений к сервисному объекту;
* Кеширование объектов ("умная" ссылка). Когда нужно кешировать результаты запросов клиентов и управлять их жизненным 
циклом.

## Категория

Относится к **структурным** паттернам.

## UML

![Proxy](https://github.com/KonstantinMyachin/DesignPatterns/tree/master/src/main/resources/uml/proxy/Proxy.uml "Proxy")