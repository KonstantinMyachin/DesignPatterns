# State (Состояние)

**Состояние** - управляет изменением поведения объекта при изменении его внутреннего состояния. Внешне это выглядит так,
словно объект меняет свой класс.

## Применимость

* Когда у Вас есть объект, поведение которого кардинально меняется в зависимости от внутреннего состояния, причем типов 
состояний много, и их код часто меняется;
* Когда код класса содержит множество больших похожих друг на друга, условных операторов, которые выбирают поведение в 
в зависимости от текущих значений полей класса;
* Когда Вы сознательно используете табличную машину состояний, построенную на условных операторах, но вынуждены мириться
с дублирование кода для похожих состояний и переходов.

## Категория

Относится к **поведенчиским** паттернам.

## UML

<img src="/src/main/resources/uml/state/State.svg">