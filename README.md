# RxJava in practice

## ¿Qué es RxJava?

Es una implementación de ReactiveX, una API para programación asincrona con flujo de datos desde objetos llamados observables.

<p align="center">
  <img src="./reactivex-logo.png" href="http://reactivex.io/"/>
</p>

> [ReactiveX](http://reactivex.io/) is a combination of the best ideas from [the Observer pattern](https://sourcemaking.com/design_patterns/iterator),
[the Iterator pattern](https://sourcemaking.com/design_patterns/iterator), and functional programming


## Recursos para aprender RxJava

1. [A quick introduccion](https://praveer09.github.io/technology/2016/02/13/rxjava-part-1-a-quick-introduction/): Se exponen tres 
artículos donde se presenta **los conceptos fundamentales para entender la programación reactiva**: La fuente de datos,
el consumidor de datos y la conexión entre el consumidor y la fuente. Estos conceptos se ven reflejados por la API 
respectivamente en Observable, Observer y el método subscribe. Asimismo, **los diferentes escenarios para la creación de Observables**.
Y finalmente, **el comportamiento que posee la API para tratar con multihilos.**

2. [How to Think, in RxJava, Before Reacting](https://vimeo.com/170796165): Una conferencia dictada por Praveer Gupta donde explica
apartados que van desde una introducción a la programación reactiva hasta utilidades para pruebas unitarias. Brindando suficiente
 información acerca de los mecanismos de RxJava para poder seguir experimentado con esta libreria.

3. [RxJava- Understanding observeOn() and subscribeOn()](http://tomstechnicalblog.blogspot.pe/2016/02/rxjava-understanding-observeon-and.html): Thomas Nield parte de la teoria básica de concurrencia y multihilos para enseñar conceptos claves en el entendimiento de observeOn() y subcribeOn(), ambos operadores muy especiales en ReactiveX.

