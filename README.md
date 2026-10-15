# 🎮 Guess The Number (Adivina el Número)

¡Bienvenido a **Guess The Number**! Este es un juego interactivo e intuitivo desarrollado como un ejercicio de clase para poner en práctica el desarrollo web frontend utilizando **HTML, CSS y JavaScript**.

🚀 **[¡Haz click para jugar!](https://pablo-cortina.github.io/GuessTheNumber/)**

---

## 📝 Descripción del Proyecto

El objetivo del juego es adivinar un número secreto generado aleatoriamente por la aplicación dentro del rango del **1 al 100**. El sistema cuenta con un límite de intentos, un historial visual de las jugadas y un sistema dinámico de proximidad térmica que se adapta en tiempo real según el nivel de dificultad seleccionado.

### 🌟 Características Destacadas:
* **Modos de Dificultad:** Permite elegir entre tres niveles para ajustar el reto (**Fácil, Normal y Difícil**).
* **Control de Intentos Estricto:** Límite máximo de **10 intentos por ronda**. El sistema realiza un seguimiento del acumulado total de intentos globales de la sesión.
* **Contador de Aciertos:** Registra cuántas veces has adivinado el número con éxito a lo largo de tus sesiones.
* **Historial Térmico:** Muestra tarjetas dinámicas con los números ya ingresados e indica con colores y texto el nivel de proximidad de cada uno para evitar repeticiones.
* **Modo Claro / Modo Oscuro:** Interfaz adaptable para jugar cómodamente en cualquier entorno de luz.

---

## ⚙️ Niveles de Dificultad y Sistema de Proximidad

El juego calcula la distancia entre el número ingresado y el número oculto. Dependiendo de la dificultad, los umbrales cambian de la siguiente manera:

| Dificultad | 🔥 TE QUEMAS | ☀️ CALIENTE | ⛅ TIBIO | ❄️ FRÍO FRÍO | 🧊 CONGELADO |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **🟢 Fácil** | Distancia `≤ 10` | Distancia `≤ 20` | Distancia `≤ 35` | Distancia `≤ 50` | Distancia `> 50` |
| **🟡 Normal** | Distancia `≤ 5` | Distancia `≤ 10` | Distancia `≤ 15` | Distancia `≤ 25` | Distancia `> 25` |
| **🔴 Difícil** | Distancia `≤ 2` | Distancia `≤ 4` | Distancia `≤ 8` | Distancia `≤ 15` | Distancia `> 15` |

---

## 🛠️ Tecnologías Utilizadas

* **HTML:** Estructura semántica del juego, botones de control y secciones de información.
* **CSS:** Estilos personalizados para los paneles y la gestión del tema visual.
* **JavaScript:** Lógica del juego, manejo de arrays, validaciones de entrada, gestión del estado del marcador y manipulación del DOM.

---

## 🕹️ Cómo Jugar

1. **Selecciona tu dificultad:** Elige el nivel deseado. Ten en cuenta que si cambias la dificultad con una partida en curso, esta se reiniciará.
2. **Ingresa tu propuesta:** Escribe un número válido entre 1 y 100.
3. **Comprueba el resultado:** Haz clic en **"Comprobar"** o presiona la tecla **Enter**. 
4. **Interpreta las pistas:** Revisa el color del mensaje y del historial para afinar tu puntería según la temperatura de tu intento.
5. **Victoria o Derrota:** Si aciertas, sumarás un acierto al marcador. Si alcanzas los 10 intentos sin adivinarlo, el juego revelará el número oculto y te forzará a reiniciar.
