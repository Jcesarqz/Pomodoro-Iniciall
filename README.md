# Consigna Evaluación Parcial: Pomodoro Timer

## Objetivo
Desarrollar un temporizador Pomodoro que permita al usuario gestionar intervalos de trabajo y descanso. El temporizador debe incluir una interfaz atractiva y funcionalidades básicas como iniciar, pausar y reiniciar.

### **Desarrollador**
**QUISPE ZARATE JULIO CESAR**

---

## Requisitos Funcionales

### Interfaz de Usuario (HTML y CSS):
- Mostrar un temporizador grande que indique el tiempo restante en formato MM:SS.
- Incluir botones para:
  - **Iniciar**: Comienza el temporizador.
  - **Pausar**: Detiene el temporizador.
  - **Reiniciar**: Vuelve al tiempo inicial.
- Mostrar un mensaje o indicador que diga si el usuario está en un intervalo de trabajo o descanso.
- Mejorar la estética del temporizador utilizando colores, fuentes y diseños modernos.

### Lógica del Temporizador (JavaScript):
- El temporizador debe alternar entre dos intervalos:
  - **Trabajo**: 25 minutos.
  - **Descanso**: 5 minutos.
- Cuando el temporizador llega a 0, debe cambiar automáticamente al siguiente intervalo (de trabajo a descanso o viceversa).
- El temporizador debe actualizarse cada segundo.
- El usuario debe poder pausar y reanudar el temporizador en cualquier momento.
- Al hacer clic en **Reiniciar**, el temporizador debe volver al intervalo inicial (25 minutos de trabajo).

---

## Estructura Básica del Proyecto

### HTML:
```html
<div class="pomodoro-container">
  <h1>Pomodoro Timer</h1>
  <div id="timer">25:00</div>
  <div id="status">Tiempo de Trabajo</div>
  <button id="start">Iniciar</button>
  <button id="pause">Pausar</button>
  <button id="reset">Reiniciar</button>
</div>
