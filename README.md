# Poker-Kata
## Resumen del Proyecto
  El proyecto consiste en un sistema de evaluación de manos de póker, implementado en Java. Incluye varias clases para representar las cartas, la baraja, los jugadores y la mesa de juego, así como tests unitarios para garantizar el correcto funcionamiento de las clases.
### Clases
Card:

Representa una carta de juego con un palo y un valor.
Deck:

Representa una baraja de cartas y proporciona métodos para mezclarla y repartirla.
HandRank:

Enumeración que define las posibles clasificaciones de manos de póker.
HandWithPlayerIndex:

Representa una mano de jugador con su clasificación y la carta de mayor valor.
Player:

Representa un jugador en el juego.
PlayingCard:

Representa una carta de juego con un palo y un valor, incluyendo un método para comparar cartas.
Table:

Representa la mesa de juego en el póker, con métodos para repartir cartas comunitarias.
Tests
CardTest:

Verifica el funcionamiento de los métodos de la clase Card.
DeckTest:

Verifica el funcionamiento de los métodos de la clase Deck.
HandRankTest:

Verifica que la enumeración HandRank esté definida correctamente.
HandWithPlayerIndexTest:

Verifica el funcionamiento de los métodos de la clase HandWithPlayerIndex.
PlayerTest:

Verifica el funcionamiento de los métodos de la clase Player.
PlayingCardTest:

Verifica el funcionamiento del método compareTo() de la clase PlayingCard.
TableTest:

Verifica el funcionamiento de los métodos de la clase Table.
Estos tests garantizan que las clases y sus métodos funcionen correctamente en el contexto del juego de póker.