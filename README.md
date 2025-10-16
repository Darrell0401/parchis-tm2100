# Parchís TM2100

Proyecto de Parchís (tablero 1–68, 2 jugadores, dado 1–6, salida con 5, preguntas V/F) con arquitectura MVC en Java (Swing).

## Estructura
- `modelo/`: lógica del juego (Juego, Jugador, Ficha, Tablero, Casillas, BancoPreguntas…)
- `vista/`: interfaz gráfica (GUIInicio, GUITablero, paneles)
- `controlador/`: orquestación entre modelo y vista
- `main/`: punto de entrada (`App`)

## Requisitos
- JDK 17+ (sugerido)

## Ejecución
```bash
javac -d out $(find src/main/java -name "*.java")
java -cp out cr.ucr.parchis.main.App
