# Revisión bibliográfica — Sistema alginato-quitosano para fibras funcionales

**Proyecto:** Síntesis y caracterización de fibras de alginato de calcio para aplicaciones textiles sostenibles  
**Investigadora:** María José Escobar León · Ingeniería de Materiales · Universidad de Antioquia  
**Propósito del documento:** Presentar el problema técnico de incorporar quitosano al sistema de fibras de alginato, revisar la literatura consultada y proponer una decisión de diseño experimental para la Fase 2.

---

## 1. Motivación — ¿Por qué incorporar quitosano?

La Fase 1 del proyecto caracteriza fibras de alginato de calcio puro bajo distintos parámetros de síntesis. Los valores de referencia documentados en literatura — resistencia a la tracción de 1.54–2.32 cN/dtex y elongación de 8.29–10.08% — son considerablemente inferiores a los de fibras sintéticas convencionales, lo que limita su aplicabilidad textil directa. Esta fragilidad mecánica intrínseca, sumada a la ausencia de actividad antimicrobiana activa, constituye la limitación central del sistema y justifica la búsqueda de una estrategia de mejora para la Fase 2.

Cuando las fibras de alginato absorben fluido, se hinchan y cierran los espacios entre ellas, atrapando físicamente las bacterias presentes en el líquido. No las elimina — las contiene. Para aplicaciones textiles en contacto directo con piel (ropa interior, apósitos, textiles médicos, máscaras faciales), esta limitación reduce significativamente el valor funcional del material.

El quitosano es el candidato natural para resolver esta limitación. Como polímero de origen marino con actividad antimicrobiana intrínseca, biocompatibilidad y biodegradabilidad demostradas, su incorporación al sistema de fibras podría generar un material con propiedades que ninguno de los dos polímeros posee de forma independiente.

---

## 2. ¿Qué es el quitosano?

El quitosano es un polisacárido catiónico obtenido por desacetilación de la quitina — el material estructural de los caparazones de crustáceos (camarones, cangrejos, langostas). Es el segundo biopolímero más abundante en la naturaleza después de la celulosa, y puede obtenerse como subproducto de la industria pesquera, lo que le confiere disponibilidad y bajo costo.

Su estructura química es poli-(1→4)-2-amino-2-desoxi-β-D-glucosa. El parámetro estructural más importante es el **grado de desacetilación (DD)** — el porcentaje de unidades monoméricas que tienen el grupo amino (-NH₂) libre en lugar del grupo acetilo (-COCH₃). Los polímeros con DD < 50% se consideran quitina; con DD > 50% se consideran quitosano. Un mayor DD implica más grupos amino libres, mayor carga positiva en solución ácida y mayor actividad antimicrobiana.

El grado de desacetilación es al quitosano lo que la relación M/G es al alginato — el parámetro que determina las propiedades del material y que debe constar en la ficha técnica del proveedor.

### 2.1 Diferencia fundamental con el alginato

| Propiedad | Alginato de sodio | Quitosano |
|---|---|---|
| Carga en solución | Aniónico (negativa) | Catiónico (positiva) |
| Solvente | Agua destilada | Ácido acético diluido (0.5–5%) |
| Mecanismo de coagulación | CaCl₂ — gelificación iónica egg-box | NaOH — precipitación por cambio de pH |
| Actividad antimicrobiana | Pasiva — atrapamiento físico | Activa — disrupción de membrana bacteriana |
| Origen | Algas pardas marinas | Caparazones de crustáceos |
| pH de trabajo | Neutro a ligeramente ácido | Ácido (pH 4–6) |

Esta tabla resume la incompatibilidad de procesamiento entre ambos polímeros. No comparten solvente ni mecanismo de coagulación, y sus cargas opuestas generan una interacción iónica espontánea que es a la vez su mayor potencial y su principal obstáculo técnico.

### 2.2 Mecanismo antimicrobiano del quitosano

El mecanismo antimicrobiano del quitosano es radicalmente distinto al del alginato. Como amina polimérica, el quitosano adquiere carga positiva en medio húmedo. Al entrar en contacto con la pared celular bacteriana — que está cargada negativamente — las cargas opuestas se atraen y el quitosano se adhiere a la membrana, perturbando su integridad hasta causar la muerte celular. Es un mecanismo de contacto directo que no requiere liberación de sustancias tóxicas y no genera resistencia bacteriana con facilidad. Las fibras de quitosano pueden quelar hasta 6.2% en peso de iones de zinc, potenciando adicionalmente su actividad antimicrobiana.

---

## 3. El problema técnico — gelificación prematura

El obstáculo central para producir fibras combinadas alginato-quitosano por wet spinning es la **interacción polielectrolítica** entre ambos polímeros.

El alginato de sodio en solución acuosa tiene carga negativa (grupos carboxilato —COO⁻). El quitosano disuelto en ácido acético tiene carga positiva (grupos amino protonados —NH₃⁺). Cuando ambas soluciones entran en contacto, las cadenas de carga opuesta se atraen electrostáticamente de forma inmediata, formando complejos polielectrolíticos insolubles — un gel denso que precipita antes de poder ser extruido.

Esta gelificación prematura hace imposible preparar una solución de hilado estable si los dos polímeros se mezclan directamente. El problema fue documentado formalmente por Watthanaphanit et al. (2009) como el obstáculo principal para la producción de fibras híbridas por wet spinning.

---

## 4. Revisión de la literatura — tres aproximaciones documentadas

### 4.1 Recubrimiento superficial (Tamura et al. · Knill et al.)

La aproximación más temprana consistió en fabricar primero la fibra de alginato de calcio por el proceso convencional, y luego sumergirla en una solución de quitosano para que este se adhiera a la superficie por interacción iónica con el alginato de la fibra. Knill et al. mejoró el método degradando el quitosano a oligosacáridos de bajo peso molecular para que pudiera penetrar mejor en las fibras hinchadas. Las fibras resultantes mostraron alta absorbencia y propiedades antimicrobianas sostenidas.

**Limitación:** el quitosano queda en la superficie y puede desprenderse con el lavado o el uso. No hay incorporación estructural profunda.

### 4.2 Ruta B — Emulsión de quitosano en alginato de sodio (Watthanaphanit et al. 2009)

Este artículo propone una solución ingeniosa al problema de gelificación prematura: neutralizar temporalmente la carga positiva del quitosano antes de mezclarlo con el alginato, de modo que las dos soluciones puedan combinarse sin reaccionar.

**El mecanismo en detalle:**

El quitosano se disuelve en ácido acético y se añade ácido cítrico. Los iones citrato se coordinan con los grupos amino del quitosano (—NH₃⁺), neutralizando su carga positiva y formando un complejo quitosano-citrato de carga reducida. Este complejo se encapsula dentro de micelas formadas por aceite de oliva y dodecilsulfato de sodio (SDS) como surfactante, generando una emulsión estable. La emulsión de quitosano encapsulado se añade a la solución de alginato de sodio sin que ocurra gelificación — el quitosano está eléctricamente neutralizado y físicamente aislado dentro de las micelas.

La solución combinada se extruye al baño de CaCl₂. El alginato gelifica normalmente por el mecanismo egg-box. Las micelas quedan atrapadas como dominios discretos dentro de la matriz de alginato de calcio. Cuando la fibra absorbe fluido en uso, las micelas se disuelven liberando el quitosano activo al entorno.

**Resultado:** una fibra con arquitectura de matriz-dominio. La matriz continua es alginato de calcio con su red egg-box intacta. El quitosano está distribuido como islas localizadas dentro de esa matriz — de ahí el nombre "chitosan-spotted" (fibra de alginato con manchas de quitosano).

**Ventajas:**
- El mecanismo egg-box del alginato se preserva íntegramente
- El baño de coagulación sigue siendo CaCl₂ — mismo proceso que la Fase 1
- La actividad antimicrobiana se libera de forma sostenida al absorber fluido
- Permite comparación directa entre fibras con y sin quitosano

**Limitaciones:**
- El proceso de preparación de la emulsión es más complejo que el wet spinning convencional
- La distribución del quitosano es heterogénea (dominios discretos, no mezcla homogénea)
- Requiere SDS (surfactante) y aceite de oliva como componentes adicionales

### 4.3 Ruta A — PGA + quitosano + baño de NaOH (Patente CN103012859B · 2012)

Esta patente aborda el problema desde otra perspectiva: en lugar de neutralizar el quitosano, sustituye el alginato de sodio por alginato de propilénglicol (PGA) — un derivado donde los grupos carboxilato están parcialmente esterificados y por tanto no tienen carga aniónica.

**El mecanismo:**

El PGA, al no tener grupos carboxilato libres, no reacciona iónicamente con el quitosano catiónico. Las dos soluciones — quitosano en ácido acético al 0.5–5% y PGA en agua — se pueden mezclar directamente sin gelificación prematura en proporciones (0.1–100):1 en peso.

La mezcla se extruye en un baño de NaOH. El medio alcalino cumple dos funciones simultáneas: precipita el quitosano (que necesita pH alcalino para solidificar) y activa una reacción de entrecruzamiento covalente entre los grupos amino del quitosano y los grupos éster del PGA. Este entrecruzamiento covalente — más estable que las asociaciones iónicas del egg-box — le da estabilidad estructural al material en húmedo. Sin él, el PGA puro se disolvería al contacto con agua.

**Resultado:** una fibra con red de entrecruzamiento covalente quitosano-PGA, con alta absorción hídrica aportada por el PGA y estabilidad estructural aportada por los entrecruzamientos con el quitosano.

**Ventajas:**
- No hay gelificación prematura — las soluciones se mezclan directamente
- El quitosano está distribuido de forma más homogénea en la fibra
- La estabilidad estructural en húmedo es superior a la del PGA puro

**Limitaciones:**
- El mecanismo de coagulación es completamente distinto al egg-box — no hay Ca²⁺ involucrado
- El baño de NaOH es diferente al baño de CaCl₂ de la Fase 1
- El PGA no puede usarse como material base en la Fase 1 (no forma fibras por egg-box)
- La continuidad experimental entre Fase 1 y Fase 2 se pierde

---

## 5. El problema de continuidad experimental

Esta es la pregunta central que surge de la revisión bibliográfica.

La Fase 1 del proyecto usa **alginato de sodio** con baño de **CaCl₂** — mecanismo egg-box, variables bien documentadas, rango de referencia establecido en literatura (1.54–2.32 cN/dtex).

Si la Fase 2 adopta la **Ruta A** (PGA + quitosano + NaOH), el sistema de coagulación es completamente diferente. El material base cambia, el baño cambia, el mecanismo cambia. Los resultados de la Fase 1 no son comparables directamente con los de la Fase 2 — no se puede atribuir un cambio en las propiedades a la incorporación del quitosano si todo lo demás también cambió.

Si la Fase 2 adopta la **Ruta B** (alginato de sodio + quitosano encapsulado + CaCl₂), el sistema base se mantiene. El mecanismo egg-box sigue siendo el mismo. La única variable nueva es la presencia del quitosano encapsulado. Los resultados de Fase 1 y Fase 2 son directamente comparables — se puede medir el efecto real del quitosano sobre las propiedades de la fibra.

| | Ruta A (PGA + NaOH) | Ruta B (alginato + emulsión + CaCl₂) |
|---|---|---|
| Continuidad con Fase 1 | No | Sí |
| Complejidad de proceso | Media | Alta |
| Homogeneidad del quitosano | Alta | Baja (dominios) |
| Mecanismo de coagulación | Covalente (NaOH) | Egg-box (CaCl₂) |
| Comparabilidad de resultados | Limitada | Directa |
| Referencia bibliográfica | Patente CN103012859B | Watthanaphanit et al. 2009 |

---

## 6. Propuesta para definir el comienzo del experimento

Con base en la revisión bibliográfica, se identifican dos decisiones que deben tomarse antes de diseñar la Fase 2:

**Decisión 1 — ¿Cuál es el propósito de la Fase 2?**

Si el objetivo es desarrollar un nuevo material funcional con quitosano sin necesidad de comparación directa con la Fase 1, la Ruta A es más simple y produce una fibra más homogénea. Si el objetivo es entender el efecto del quitosano sobre el sistema de alginato ya caracterizado, la Ruta B es la única opción metodológicamente coherente.

**Decisión 2 — ¿Qué variable se estudia en la Fase 2?**

Si se elige la Ruta B, la variable principal a evaluar sería la proporción de quitosano en la emulsión y su efecto sobre las propiedades mecánicas, antimicrobianas e hídricas de la fibra — manteniendo fijos los parámetros de alginato y CaCl₂ optimizados en la Fase 1.

Si se elige la Ruta A, las variables serían la proporción PGA:quitosano y la concentración del baño de NaOH — un diseño experimental nuevo e independiente.

---

## 7. Referencias

1. Qin, Y., Deng, Y., Hao, Y., Zhang, N., & Shang, X. (2017). Marine bioactive fibers: alginate and chitosan fibers — a critical review. *Journal of Textile Engineering & Fashion Technology*, 1(6), 228–231. DOI: 10.15406/jteft.2017.01.00037

2. CN103012859B (2015). Chitosan and propylene glycol alginate blending material as well as preparation method and application thereof. Patente china. Qingdao Bright Moon Biomedical Material Co. Ltd. Inventor: Yimin Qin. Fecha de publicación: 15 de abril de 2015.

3. Watthanaphanit, A., Supaphol, P., Furuike, T., Tokura, S., Tamura, H., & Rujiravanit, R. (2009). Novel Chitosan-Spotted Alginate Fibers from Wet-Spinning of Alginate Solutions Containing Emulsified Chitosan-Citrate Complex and their Characterization. *Biomacromolecules*, 10(2), 320–327. DOI: 10.1021/bm801043d
