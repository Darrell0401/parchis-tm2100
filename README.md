# Parchís TM2100

Proyecto de Parchís (tablero 1–68, 2 jugadores, dado 1–6, salida con 5, preguntas V/F) con arquitectura MVC en Java (Swing).

## Estructura
- `parallax.com.proyectodarrell.model` → Clases de lógica y datos del juego
- `parallax.com.proyectodarrell.view` → Interfaz gráfica (Swing)
- `parallax.com.proyectodarrell.controller` → Comunicación entre vista y modelo
- `parallax.com.proyectodarrell.main` → Punto de entrada (`App`)
## Requisitos
- JDK 17+ (sugerido)

## Ejecución
```bash
javac -d out $(find src/main/java -name "*.java")
java -cp out parallax.com.proyectodarrell.main.App

