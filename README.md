# 🌌 Star Defender 3D — Laboratorio de IA Generativa y Distributiva

> Proyecto interactivo y académico que demuestra la implementación de **Inteligencia Artificial Generativa** y **Sistemas Distribuidos en Red** aplicados a la industria de los videojuegos modernos.

---

## 🎯 Objetivo del Proyecto

Este minijuego en 3D fue desarrollado utilizando **Three.js** y **WebGL** para ilustrar en tiempo real y de forma visual dos de los conceptos más importantes de la inteligencia artificial contemporánea:

1. **Inteligencia Artificial Generativa (Generación Procedural):** Creación de entornos, geometrías, biomas y patrones de juego al vuelo mediante algoritmos matemáticos y semillas (*seeds*).
2. **Inteligencia Artificial Distributiva (Sistemas en Red / Enjambre):** Comunicación y distribución de carga de cómputo entre nodos o entidades independientes coordinadas en tiempo real.

---

## 🚀 Características Principales

- **Entorno 3D y Gráficos Vectoriales:** Desarrollado con Three.js, incluyendo iluminación ambiental dinámicamente adaptada, niebla atmosférica y sombreado tridimensional.
- **Botón IA Generativa:** Modifica la semilla (*seed*) del mapa para calcular en tiempo real nuevas alturas de terreno, paletas de color HSL, niebla atmosférica y geometrías tridimensionales para las naves enemigas (octaedros, toros, cubos).
- **Botón IA Distributiva:** Conecta a la flota enemiga mediante un enjambre en red visible (líneas láser verdes). Los nodos enemigos comparten datos de posición y sincronizan sus movimientos laterales reduciendo la carga de procesamiento central.
- **Sistema de Combate y Audio Sintetizado:** Movimiento de la nave en 3D, disparos láser y efectos de sonido generados directamente por código mediante la **Web Audio API** sin librerías externas pesadas.

---

## 🕹️ Controles del Juego

- **Mover la Nave:** Teclas `[W]` `[A]` `[S]` `[D]` o **Flechas de dirección**.
- **Disparar Láser:** Tecla `[Espacio]`.
- **Aplicar IA Generativa:** Haz clic en el botón **✨ APLICAR IA GENERATIVA**.
- **Activar IA Distributiva:** Haz clic en el botón **🌐 ACTIVAR IA DISTRIBUTIVA**.

---

## 📚 Explicación de los Conceptos de IA

### 1. IA Generativa (Basado en *No Man's Sky*)
En lugar de almacenar texturas pesadas o modelos estáticos en un disco duro, el sistema utiliza algoritmos de ruido y combinatoria probabilística. Cada vez que presionas el botón generativo, la matemática recalcula el universo completo sin consumir gigabytes de almacenamiento.

### 2. IA Distributiva
Demuestra la arquitectura donde la toma de decisiones y el procesamiento no recaen sobre un único núcleo central, sino que se distribuyen entre múltiples agentes en red. Las naves enemigas intercambian información táctica y coordinan maniobras de evasión o ataque en grupo.

---

## 🛠️ Tecnologías Utilizadas

- **HTML5 & CSS3:** Estructura e interfaz HUD futurista.
- **JavaScript Vanilla (ES6+):** Lógica del juego, físicas y eventos.
- **Three.js (r128):** Renderizado de gráficos 3D en WebGL.
- **Web Audio API:** Síntesis nativa de sonido para disparos e impactos.