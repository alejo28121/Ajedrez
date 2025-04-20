
# Juego de Ajedrez en Racket

Este proyecto es una implementación completa de un juego de ajedrez usando el lenguaje **Racket 8.15**, con una **interfaz gráfica personalizada**. Permite jugar partidas completas entre dos jugadores, incluyendo reglas como el **jaque**, **jaque mate**, y la **coronación de peones**.

---

## 🖼️ Capturas de pantalla

### Tablero inicial:
![Inicio](./Screenshot%202025-04-20%20164855.png)

### Jaque mate:
![Jaque Mate](./Screenshot%202025-04-20%20165012.png)

---

## 🧠 Características

- Interfaz gráfica en Racket usando `graphics/graphics`.
- Movimiento completo de todas las piezas.
- Validación de turnos (blancas y negras).
- Detección de jaque y jaque mate.
- Finalización de partida con botón "TERMINAR".
- **Coronación de peones** incluida.
- Lógica de verificación optimizada con uso de strings.
- Mensajes visuales en el tablero y menú lateral.

---

## ⚙️ Estructura del proyecto

- `Ajedrez.rkt`: Archivo principal con toda la lógica del juego y gráficos.
- Requiere tener instalado **Racket 8.15**.

---

## ▶️ Cómo ejecutar

1. Instala Racket desde [https://racket-lang.org/](https://racket-lang.org/)
2. Asegúrate de estar usando la versión **8.15**.
3. Abre el archivo `Ajedrez.rkt` en DrRacket o terminal.
4. Ejecuta el programa (en DrRacket presiona el botón **Run**).

---

## ♟️ Representación de piezas

En el sistema se utilizan caracteres para representar las piezas en cadenas de 64 caracteres (8x8):

| Pieza         | Blanca | Negra  |
|---------------|--------|--------|
| Rey           | `Y`    | `y`    |
| Reina         | `R`    | `r`    |
| Torre         | `T`    | `t`    |
| Alfil         | `A`    | `a`    |
| Caballo       | `C`    | `c`    |
| Peón          | `P`    | `p`    |
| Casilla vacía | `-`    | `-`    |

Ejemplo de cadena de tablero inicial:
```
TCARYACT
PPPPPPPP
--------
--------
--------
--------
pppppppp
tcaryact
```

---

## 📦 Detalles técnicos

- Solo se utilizan **strings locales** y **gráficos básicos**.
- No se emplean identificadores globales para mantener simplicidad y control.
- El flujo de turnos se controla completamente desde el menú lateral y internamente mediante 1 y 0.
- Se emplea una función `VerificateJaqueMate` para analizar posibles jaques o jaques mates.

---

## ✅ Requisitos

- Racket 8.15
- Módulo gráfico `graphics/graphics`

---
## 📝 Autor
Alejandro Grajales Vargas 
## Git Hub
[https://github.com/alejo28121](https://github.com/alejo28121)

Este proyecto fue creado como una práctica gráfica y lógica de ajedrez con Racket.

---

