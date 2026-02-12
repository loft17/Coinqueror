# 🪙 Coinqueror

**Coinqueror** es un juego incremental desarrollado en HTML, CSS y JavaScript donde lanzas una moneda al aire para ganar dinero, desbloquear logros y mejorar tus estadísticas.

Cuanto mayor sea tu racha de caras, mayor será la recompensa.

---

## 🎮 Características

- 🎲 Lanzamiento animado en 3D con efecto visual realista
- 💰 Sistema incremental de ganancias
- 🏆 21 logros desbloqueables con recompensa económica
- 📈 Multiplicador dinámico por racha de caras consecutivas
- 🛒 Tienda de mejoras:
  - 🍀 Aumentar probabilidad de cara
  - ⚡ Reducir tiempo de vuelo
  - 💰 Incrementar valor base de recompensa
- 🔊 Efectos de sonido generados con Web Audio API
- 💾 Guardado automático con LocalStorage
- 📤 Exportación e importación manual de partidas
- 🔥 Reforma total (reset completo)

---

## 🧠 Mecánica del Juego

- La probabilidad inicial de obtener cara es del **1%**.
- Puedes mejorar:
  - La probabilidad hasta un máximo del 100%.
  - El tiempo de vuelo hasta un mínimo de 0.3 segundos.
  - El valor base de cada cara obtenida.
- Las rachas consecutivas aumentan el multiplicador de ganancia.
- Los logros desbloqueados otorgan dinero adicional.

---

## 📊 Panel de Estadísticas

El juego muestra en tiempo real:

- Tiempo total de juego
- Dinero acumulado
- Valor actual por cara
- Multiplicador activo
- Número total de lanzamientos
- Total de caras obtenidas
- Mejor racha conseguida
- Porcentaje actual de suerte
- Tiempo de vuelo de la moneda

---

## 💾 Sistema de Guardado

El progreso se guarda automáticamente usando `localStorage`.

Opciones disponibles:

- Exportar partida a código Base64
- Importar partida desde código válido
- Reiniciar completamente el progreso

---

## 🚀 Cómo usarlo

1. Descarga el archivo `.html`
2. Ábrelo en cualquier navegador moderno
3. Empieza a lanzar la moneda

No requiere instalación ni dependencias externas.

---

## 🛠 Tecnologías utilizadas

- HTML5
- CSS3 (animaciones 3D)
- JavaScript Vanilla
- Web Audio API
- LocalStorage API

---

## 📦 Versión

v1.2.0

---

## 🌐 Autor

joseromera.es
