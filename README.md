<p align="center">
  <img src="assets/logox128.png" alt="Logo de Recolecta Gotas" width="128">
</p>

<p align="center">
  <strong>¡Atrapa las gotas buenas, esquiva las malas y supera tu récord!</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/LibGDX-000000?style=flat&logo=libgdx&logoColor=white" alt="LibGDX">
  <img src="https://img.shields.io/badge/Gradle-02303A?style=flat&logo=gradle&logoColor=white" alt="Gradle">
</p>

## Introducción

**Recolecta Gotas** es un videojuego desarrollado en Java con el framework LibGDX como proyecto universitario de Programación Avanzada.

El objetivo es recolectar la mayor cantidad posible de gotas buenas controlando un tarro, mientras esquivas las gotas peligrosas que pueden hacerte perder vidas. A medida que aumenta tu puntuación, la dificultad evoluciona con nuevos patrones de movimiento, objetos especiales y eventos que ponen a prueba tus reflejos.

## Controles

| Tecla | Acción |
|---|---|
| `←` / `→` | Mover el tarro hacia la izquierda o derecha |
| `ESC` | Pausar o reanudar la partida |
| `F3` | Mostrar u ocultar las hitboxes de colisión |
| `R` | Reiniciar rápidamente la partida |

## Etapas y eventos

| Etapa | Requisito | Efecto |
|---|---|---|
| Etapa 1 | Inicio | Movimiento vertical y dificultad inicial. |
| Etapa 2 | 1.000 puntos | Mayor velocidad de caída y movimientos diagonales. |
| Etapa 3 | 2.500 puntos | Mayor dificultad, con movimientos diagonales y serpenteantes según el tipo de objeto. |
| Tormenta bonus | Recolectar 3 power-ups de Tormenta | Lluvia torrencial de gotas buenas durante un tiempo limitado. |

## Tecnologías y diseño

El proyecto utiliza las siguientes tecnologías y conceptos:

- **Java:** lenguaje de programación principal.
- **LibGDX:** framework para el desarrollo del videojuego.
- **Gradle:** gestión del proyecto y sus dependencias.
- **Programación Orientada a Objetos:** encapsulamiento, herencia, abstracción y polimorfismo.
- **Patrones de diseño:** Singleton, Template Method y Strategy para organizar la lógica del juego y facilitar su extensibilidad.

## Instalación y ejecución

### Requisitos

- Java compatible con la configuración del proyecto.
- Un IDE compatible con Gradle.

### 1. Descargar el proyecto

Clona el repositorio o descarga el proyecto desde GitHub.

```bash
git clone <URL_DEL_REPOSITORIO>
```

Si descargaste el archivo ZIP, descomprímelo antes de continuar.

### 2. Importar el proyecto

1. Abre IntelliJ IDEA o tu IDE de preferencia.
2. Selecciona **Open** y abre la carpeta raíz del proyecto.
3. Espera a que Gradle sincronice el proyecto y descargue las dependencias necesarias.

### 3. Ejecutar el juego

Localiza la clase `Lwjgl3Launcher.java` dentro del módulo `desktop`:

`desktop/src/com.mygdx.game/Lwjgl3Launcher.java`

Ejecuta la clase desde el IDE seleccionando **Run 'Lwjgl3Launcher'**.

El juego se abrirá en una ventana de **800 × 480 píxeles**.

## Contexto académico

Este proyecto fue desarrollado en equipo para la asignatura **INF2236 — Programación Avanzada**, con el objetivo de aplicar conceptos de programación orientada a objetos y patrones de diseño en un videojuego funcional.

## Autores

- Annais Paullette Legua Flores
- Benjamin Antonio Brito Veloso
- Ivan Moises Ferreira Leon

---

<p align="center">
  <em>Recolecta gotas, evita los peligros y supera tu récord. 💧</em>
</p>