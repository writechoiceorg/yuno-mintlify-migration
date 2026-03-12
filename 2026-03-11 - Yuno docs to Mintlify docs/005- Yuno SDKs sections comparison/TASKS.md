Ayudame a comparar estas dos secciones de SDKs:
- /SDKs fue creada para esta tarea /2026-03-11 - Yuno docs to Mintlify docs segun lo tratado con Heitor en /2026-03-11 - Yuno docs to Mintlify docs/001 - Context/call-trascript.md.
- /Yuno SDKs fue creada por mí y un TW de Yuno hace unas semanas. Pero creo que esta vesion ya está orientada al User Journey pero quizas necesite algunos ajustes.
- Ayudame a comparar y decidir que version enviar al equipo de desarrollo para migrar Yuno docs de Readme a Miltlify.
- Primero dime si tienes alguna duda, luego analiza ambas versiones y dame una opinion y sugerencias pero sin hacer cambios.
- Anota todo en este archivo.

## 1. Dudas Iniciales
Antes de proceder, tengo una duda clave basada en la comparación:
- **Pruning de Plataformas**: La versión `/SDKs` ha eliminado por completo **React Native** y **Flutter**. Heitor mencionó en el transcript enfocar en "mobile, iOS y Android", pero no mencionó explícitamente si React Native y Flutter deben ser eliminados o simplemente movidos a una sección secundaria. ¿Confirmamos que estas plataformas no deben incluirse en la migración inicial?

---

## 2. Análisis Comparativo

| Característica | Versión `/SDKs` (Refactorizada) | Versión `/Yuno SDKs` (User Journey) |
| :--- | :--- | :--- |
| **Enfoque Estratégico** | **Alineado con Heitor**: Se centra exclusivamente en *Full Checkout* y *Secure Fields*. | **Omnicanal**: Incluye todos los métodos de integración (Lite, Headless, Seamless, etc.). |
| **Organización** | **Orientada a Funcionalidades**: Estructura de carpetas por `Full Checkout`, `Card Enrollment`, `Customization`. | **Orientada a Plataformas**: Estructura por `android-sdks`, `ios-sdks`, `web-sdks`. |
| **Navegabilidad** | Páginas más cortas y específicas. Mejor para usuarios que ya saben qué producto usar. | Páginas extensas (ej. Android tiene 800+ líneas). Mejor para desarrolladores que solo quieren ver "todo lo de su plataforma" en un solo lugar. |
| **Mantenimiento** | Más fácil de actualizar por producto. | Más propenso a redundancia (instrucciones similares repetidas por plataforma). |

---

## 3. Opinión y Sugerencias

### Opinión
La versión **`/SDKs`** es superior para la migración a Mintlify por tres razones principales:
1. **Consistencia con la Estrategia**: Sigue al pie de la letra la instrucción de Heitor de "limpiar" la documentación y ocultar/eliminar métodos que no sean Full Checkout o Secure Fields.
2. **User Journey de Negocio**: Aunque `/Yuno SDKs` se autodefine como orientada al User Journey, la versión `/SDKs` realmente guía al usuario desde la decisión de negocio (¿Qué quiero hacer?) hacia la implementación técnica, lo cual es un journey más maduro.
3. **Escalabilidad**: Una estructura basada en funcionalidades es más escalable en Mintlify para añadir nuevos productos sin crear carpetas de plataforma infinitas.

### Sugerencias
Para que la versión `/SDKs` sea la definitiva, sugiero los siguientes ajustes menores:

1. **Corrección de Enlaces Internos**: He detectado que algunos archivos en `/SDKs` aún referencian nombres de archivos viejos (ej. referencian `choose-your-integration` cuando ahora es `choose-integration`). Necesitan un audit de links.
2. **Sección de Secure Fields en Quickstart**: El "Quickstart Guide" de `/SDKs` se enfoca mucho en Full Checkout. Podría beneficiarse de un pequeño apartado o link prominente a "Secure Fields" desde el inicio.
3. **Manejo de React Native/Flutter**: Si no se eliminan permanentemente, sugiero moverlos a una carpeta de "Otros" o "Advanced" pero marcándolos como "Hidden" en el sidebar, de modo que el equipo de desarrollo no los pierda pero no ensucien la navegación principal deseada por Heitor.
4. **Verificación de "Advanced Content"**: Heitor mencionó que "todo lo relacionado con Full SDK" debe quedarse. Asegurarme de que las customizaciones avanzadas (como crear formularios propios de tarjeta en Android) que estaban en `/Yuno SDKs` se hayan movido correctamente a `/SDKs/Customization`.

---

## 4. Conclusión
Recomiendo enviar la versión **`/SDKs`** al equipo de desarrollo, ya que refleja la dirección estratégica actual y presenta una estructura de información más moderna y limpia para el usuario final.

---


