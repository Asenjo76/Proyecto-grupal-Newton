📊 Proyecto Grupal de Estadística: Correlación y Regresión

---
El núcleo de nuestro análisis consiste en entender cómo se relacionan el área de un país y su población. Para ello, utilizamos una muestra de 100 países elegidos de forma aleatoria, extraídos de una población total de 250 países.

--- 

1. 📈 Correlación¿Están relacionados? ¿Cómo de fuerte es esa relación?

Lo primero que hicimos fue medir la Correlación de Pearson, obteniendo un valor de $r = 0.54$. Esto indica una relación positiva moderada: por lo general, a mayor área, mayor población.Sin embargo, al aplicar la correlación de Spearman, el valor subió a 0.91. Esto demuestra que la relación es mucho más fuerte de lo que parece, pero no es lineal debido a los "países gigantes" o muy "pequeños" (valores atípicos o outliers).

---


2. 📏 Regresión Lineal¿Podemos predecir?

Con la regresión, intentamos trazar la "línea perfecta" que atraviesa nuestros datos. Creamos una fórmula matemática que nos permite estimar: "Si un país mide $X$ área, su población debería ser $Y$ habitantes".
Ejemplo: Nuestro modelo predice que para un país de $100 \text{ km}^2$, la población esperada es de unos 76 habitantes.

---

3. ✅ Bondad de Ajuste ($R^2$)¿Es fiable el modelo?

Aquí medimos la calidad del ajuste. Nuestro $R^2$ es de 0.30, lo que significa que el tamaño del territorio explica el 30% de la variación de la población. El otro 70% depende de factores externos como la economía, el clima o la historia. El área no lo es todo.

---

4. 🔍 Residuos y Error¿Dónde fallamos?

Los residuos son la diferencia entre la predicción del modelo y la realidad. Estudiar el error es vital porque nos avisa que no podemos aplicar la misma regla a todos por igual.

---

Tipo de Residuo y 📝 Significado:

📍 EjemploPositivo ➕El país tiene más población de la que le "correspondería" por su tamaño.Países densos (Singapur, India).

Negativo ➖El país tiene menos población de la que se esperaría para su extensión.Países con desiertos o zonas polares (Canadá).

Cero 🎯Predicción perfecta. El país se comporta exactamente según la tendencia global.Caso ideal.