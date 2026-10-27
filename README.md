## Transiciones CSS

Una transición se compone de 4 propiedades principales.

- `transition-property`: qué propiedad de CSS yo quiero animar.
- `transition-duration`: quanto tiempo tarda en s o ms 
- `transition-timing-function`:la curva de aceleración o de velocidad.  
    1. **ease** (por defecto): empieza despacio, acelera rápido y frena suave. Botones, desplegables
    2. **linear**: velocidad constante sin aceleración. Barra de progreso, spinner
    3. **ease-in**: empieza despacio y va acelerando. Elementos que salen en la pantalla 
    4. **ease-out**: empieza muy rapido y va frenando. Notificaciones o ventana modal
    5. **ease-in-out**: empieza despacio, acelera en medio y frena pero mas exagerado que en ease. Movimiento completo de ida y vuelta en una pantalla
    6. **cubic-bezier(x1,y1,x2,y2)**: permite diseñar la curva definiendo 4 puntos (dos fijos que son principio y fin y dos que son manejadores para la forma de la curva). Los valores de x estan entre 0 y 1 y los de en medio pueden ser mayores que 1 y menores que 0
    7. steps(n, direction)
- `transition-delay`: cuánto tiempo espera antes de comenzar
