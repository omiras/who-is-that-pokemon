# Who's that pokemon?

Tenemos un juego que nos aparece la sombra de un pokemon, y tenemos que adivinar cúal es.
Ponemos el nombre en el input y le damos al enter para comprobarlo.

[Demo Funcional](https://omiras.github.io/who-is-that-pokemon/)

## Requisitos

Nuestro programa falla en algunas partes y queremos añadir una funcionalidad nueva. Revisa el código y hazte una idea general de como funciona. Para ello, fijate sobretodo:

1. Nombre de las variables globales
2. Nombre de las funciones
3. El desarrollador ha dejado comentarios. Asegúrate de leerlos.
4. Pon todos los console.log que consideres, o usa el depurador de JavaScript en Google Chrome para establecer puntos de parada

### Errores detectados

Corrige los siguientes errores detectados. Cada uno suele resolverse modificando una única línea de código. No tienes por qué resolverlos en orden

1. la aplicación tan solo recupera 10 pokemons de la [PokeAPI](https://pokeapi.co/). Nos gustaría recuperar los pokemons de la primera generación (sí, tendrás que buscar cuantos pokemons hay en la primera genración)
2. A pesar de que pongamos bien el nombre del pokemon, si lo ponemos en mayúsculas, no nos cuenta como acierto. Encuentra la línea que provoca esto y corrígela
3. Nos han pedido que añadamos un botón que ponga "Check". Al hacer click en el, debe hacer lo mismo que el hecho de pulsar el enter

## Bonus divertido

Fíjate en la función _playPokemonMp3_. Añade un listener con un evento adecuado para que, cuando el usuario haga click en el input de adivinar el pokemon, se ejecuta dicha función. Como pista, el evento que buscas tiene que ver con el _focus_ de un elemento.

## Bonus difícil

¿Dirías que la función getRandomIntInclusive es adecuada para nuestro programa?
Para averiguarlo

1. Establece el límite de pokemons a 1 (siempre recupera a bulbasaur de la API)
2. Fíjate si se produce algún error al recargar la página

¿Qué está sucediendo?

## Motivación

Muchas veces vamos a tener que entender código, más o menos bien hecho, que no es nuestro. Es importante tomar soltura en este tipo de situaciones.
