# Práctica: Your First 2D Game (Godot Engine)

Proyecto 2D interactivo desarrollado en **Godot Engine 4 (stable)** siguiendo la guía oficial *Your first 2D game*, adaptado con recursos gráficos personalizados y una mecánica adicional.

---

## 🎮 Mecánica de Juego
* **Objetivo:** Esquivar los enemigos generados aleatoriamente en los bordes de la pantalla mientras el puntaje incrementa por cada segundo con vida.
* **Mecánica extra agregada:** Se integró una habilidad especial de impulso/esquiva rápida para evitar colisiones en situaciones críticas.
* **Controles:**
  * Flechas o `W`, `A`, `S`, `D`: Mover al personaje en 4 direcciones.
  * `Espacio` / `Shift`: Activar mecánica especial.

---

## 📁 Estructura del Repositorio
* `project.godot`: Archivo de configuración central del motor.
* `*.tscn`: Escenas principales (`main.tscn`, `player.tscn`, `mob.tscn`, `hud.tscn`).
* `*.gd`: Scripts de lógica correspondientes a cada escena.
* `art/` y `fonts/`: Recursos gráficos y tipografía obtenidos de itch.io.
* `build/`: Contiene el binario ejecutable comprimido listo para su uso.

---

## 🚀 Ejecución del Juego (/build)
El ejecutable para Windows se encuentra comprimido en volúmenes dentro de la carpeta `build/` debido a límites de almacenamiento:

1. Descarga los dos archivos ubicados en la carpeta `build/` (`Tarea.zip` y `Tarea.z01`).
2. Colócalos en la misma carpeta en tu computadora.
3. Haz clic derecho en `Tarea.zip` y selecciona extraer usando **7-Zip** o **WinRAR**.
4. Abre `Tarea.exe` para jugar sin requerir abrir Godot.
