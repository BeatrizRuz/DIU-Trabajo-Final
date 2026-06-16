
# PARTE II: Caso de Estudio - Propuesta de Diseño ECO MERCADO UGR

## 1. Caso seleccionado

**Nuestras Huertas** (Bustarviejo, Madrid - `nuestrashuertas.com`).

---

## 2. Auditoría UX/UI: Análisis de "Nuestras Huertas"

### 2.1. Usabilidad y Arquitectura de la Información (Heurísticas de Nielsen)

El ecosistema digital de *Nuestras Huertas* divide su catálogo en secciones lógicas ("Huerto", "Despensa", "Cestas"), pero presenta vulnerabilidades graves en el flujo de compra.

* **Prevención de errores (Heurística #5):** El sistema de selección de productos genera alta carga cognitiva y propensión al error. Al listar productos como el *"Aguacate Cocktail Mini"*, el precio base se muestra en `€/kg`, pero el selector de cantidad (`+` / `-`) añade unidades discretas (Uds) sin aclarar dinámicamente el impacto en el precio final ni el peso estimado por unidad. El usuario no sabe con certeza cuánto pagará hasta llegar al carrito.
* **Visibilidad del estado del sistema (Heurística #1):** Falta *feedback* visual inmediato al añadir productos al carrito en la vista de catálogo. Si la conexión es lenta, el usuario puede pulsar repetidamente el botón `+`, añadiendo kilos indeseados.
* **Flexibilidad y eficiencia de uso (Heurística #7):** El catálogo (con más de 114 resultados en la categoría "Huerto") carece de un sistema de filtrado avanzado eficiente. Solo permite ordenar por "precio" o "popularidad", ignorando filtros vitales para el usuario objetivo como "Certificación Ecológica", "Temporada" o "Alérgenos".

### 2.2. Diseño Visual y Accesibilidad (WCAG)

* **Contraste y Legibilidad:** Las jerarquías tipográficas no están bien definidas. Los títulos de los productos compiten visualmente con las etiquetas de precio y los botones de acción.
* **Accesibilidad Cognitiva:** La mezcla de formatos de venta (productos que se cobran "al peso" frente a productos "por unidad" en la misma vista de lista) viola el principio de consistencia. El usuario debe leer la "letra pequeña" de cada tarjeta de producto para entender cómo está comprando.

### 2.3. Adaptación a Dispositivos (Mobile First / Responsive)

Dado que el público objetivo interactúa mayoritariamente vía *smartphone*, la plataforma muestra deficiencias en el diseño táctil (*Touch Targets*). Los selectores de cantidad (`+` y `-`) son demasiado pequeños para el estándar de 44x44 píxeles recomendado por Apple/Google, lo que provoca *misclicks* recurrentes (pulsar el enlace del producto en lugar de añadir cantidad).

---

## 3. Insights y Propuesta de Valor: ECO MERCADO UGR

A partir de la auditoría anterior y la lectura del contexto del Eco Mercado UGR (iniciativa universitaria, productores locales, comercio justo), se extraen los siguientes *insights* accionables:

1. **Insight de Confianza:** El usuario universitario/PDI está concienciado, pero tiene poco tiempo. Necesita transparencia absoluta en el precio y el origen del producto sin tener que investigar.
2. **Insight Logístico:** La compra al peso en el entorno digital genera ansiedad. Es preferible estandarizar formatos (cestas cerradas o *packs* de "1 Kg aproximado") para agilizar la toma de decisiones.

### Propuesta de Valor (Value Proposition)

**"Eco Mercado UGR App: Del productor a tu facultad en 3 clics."**
Una aplicación *Mobile-First* que conecta de forma transparente a los productores agroecológicos de Granada con la comunidad UGR. Su pilar es la **fricción cero**: estandarización de formatos de venta (cestas semanales, productos por lotes claros), perfiles detallados de cada productor local (fomentando el comercio ético) y puntos de recogida sincronizados con los campus universitarios.

---

## 4. Planteamiento del Diseño (Mockup Concept)

Se propone el diseño de un prototipo interactivo en vista móvil (basado en componentes *Atomic Design* en Figma) estructurado en dos pantallas clave para resolver los problemas detectados en *Nuestras Huertas*:

**Pantalla 1: *Landing* / Catálogo Eficiente**

* **Arquitectura:** Navegación inferior (*Bottom Navigation Bar*) con iconos gruesos y accesibles (Inicio, Cestas, Productores, Perfil).
* **UI/Layout:** En lugar de una lista interminable, la pantalla principal prioriza *Cards* grandes para las "Cestas de Temporada" (ej. "Cesta Estudiante 5Kg" - Precio cerrado).
* **Solución UX:** Los botones de "Añadir al carrito" ocupan todo el ancho disponible (*Full-width button*). Los precios son finales y absolutos, eliminando el cálculo mental de `€/kg`.

**Pantalla 2: Ficha de Transparencia del Productor**

* **Arquitectura:** Al pulsar sobre un producto (ej. Tomates de la Vega), la pantalla no solo muestra la información nutricional, sino una ficha del productor local vinculada.
* **Solución UX:** Cumple con la heurística de "Relación entre el sistema y el mundo real". Humaniza la compra mostrando quién cultivó el alimento y a cuántos kilómetros de la universidad se encuentra la huerta (cálculo de huella de carbono).

*(Nota para la entrega: Se recomienda adjuntar en la carpeta `/img` de tu repositorio 1 o 2 bocetos rápidos hechos en Figma o dibujados a mano, escaneados, que representen estas dos pantallas de la App Eco Mercado UGR).*

---

## 5. Conclusiones y Autoevaluación Práctica

Realizar este análisis como consultor externo me ha permitido auditar mi propia evolución técnica. Al enfrentar un caso real como *Nuestras Huertas*, he aplicado de forma natural y automática los principios que tanto esfuerzo costó interiorizar durante la práctica de **Cyber-Gourmet**: la jerarquía visual, la necesidad imperiosa de *Touch Targets* accesibles en móvil y la prevención de errores (gestión de la fricción cognitiva).

**Análisis comparativo con las prácticas:**

* **Lo aplicado:** He logrado trasladar la capacidad de análisis crítico adquirida. Al igual que cuando evaluamos *Punto Café* (Caso B), he detectado inmediatamente cómo una arquitectura de información ambigua (como mezclar unidades y pesos) puede destruir la conversión de un *e-commerce*.
* **Lo que ha faltado (Limitaciones del estudio rápido):** En un entorno profesional real (o con más tiempo), este ejercicio requeriría la elaboración formal de un *User Journey Map* del estudiante de la UGR, y la ejecución de un **Test A/B** o la administración de un **Cuestionario SUS** sobre el prototipo propuesto para validar si nuestra hipótesis de "cestas de precio cerrado" realmente reduce la ansiedad de compra frente al modelo tradicional de "compra al peso".

En definitiva, este caso de estudio demuestra que las metodologías de UX Research y UI Design no son exclusivas de plataformas tecnológicas complejas, sino que son herramientas vitales para el éxito y la accesibilidad de iniciativas de impacto social y ecológico como el Eco Mercado UGR.
