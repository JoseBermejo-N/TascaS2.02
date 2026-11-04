# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 37 correctas de 41 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.57 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.20 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.17 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.18 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.16 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 6: Correcto

⏱ Tiempo: 0.16 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.15 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 8: Correcto

⏱ Tiempo: 0.21 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 9: Correcto

⏱ Tiempo: 0.16 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 10: Correcto

⏱ Tiempo: 0.16 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 11: Correcto

⏱ Tiempo: 0.15 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 12: Correcto

⏱ Tiempo: 0.18 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ✅ Query 13: Correcto

⏱ Tiempo: 0.16 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 14: Correcto

⏱ Tiempo: 0.14 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 15: Correcto

⏱ Tiempo: 0.16 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 16: Correcto

⏱ Tiempo: 0.15 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 17: Correcto

⏱ Tiempo: 0.14 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 18: Correcto

⏱ Tiempo: 0.14 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 19: Correcto

⏱ Tiempo: 0.15 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 20: Correcto

⏱ Tiempo: 0.15 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ✅ Query 21: Correcto

⏱ Tiempo: 0.16 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ✅ Query 22: Correcto

⏱ Tiempo: 0.18 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ✅ Query 23: Correcto

⏱ Tiempo: 0.16 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ✅ Query 24: Correcto

⏱ Tiempo: 0.15 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ✅ Query 25: Correcto

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ✅ Query 26: Correcto

⏱ Tiempo: 0.28 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ✅ Query 27: Correcto

⏱ Tiempo: 0.30 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ✅ Query 28: Correcto

⏱ Tiempo: 0.29 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ✅ Query 29: Correcto

⏱ Tiempo: 0.28 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

🚨 **Problemas detectados:**
⚠️ Considerar `EXISTS` en lugar de `IN` para eficiencia.

---

## ✅ Query 30: Correcto

⏱ Tiempo: 0.26 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ✅ Query 31: Correcto

⏱ Tiempo: 0.26 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ✅ Query 32: Correcto

⏱ Tiempo: 0.29 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ✅ Query 33: Correcto

⏱ Tiempo: 0.30 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ✅ Query 34: Correcto

⏱ Tiempo: 0.32 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ✅ Query 35: Correcto

⏱ Tiempo: 0.26 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ❌ Query 36: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,3 @@
-codigo | nombre | precio | codigo_fabricante
-8.00 | Portátil Yoga 520 | 559.00 | 2.00
-9.00 | Portátil Ideapd 320 | 444.00 | 2.00
+nombre | precio
+Portátil Yoga 520 | 559.00
+Portátil Ideapd 320 | 444.00
```

⏱ Tiempo: 0.29 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ✅ Query 37: Correcto

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 38: Correcto

⏱ Tiempo: 0.27 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 39: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-nombre
-Impresora HP Deskjet 3720
+nombre | precio
+Impresora HP Deskjet 3720 | 59.99
```

⏱ Tiempo: 0.25 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 40: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,3 @@
-codigo | nombre | precio | codigo_fabricante
-5.00 | GeForce GTX 1080 Xtreme | 755.00 | 6.00
-8.00 | Portátil Yoga 520 | 559.00 | 2.00
+nombre | precio
+GeForce GTX 1080 Xtreme | 755.00
+Portátil Yoga 520 | 559.00
```

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 41: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-codigo | nombre | precio | codigo_fabricante
-7.00 | Monitor 27 LED Full HD | 245.99 | 1.00
+nombre | precio
+Monitor 27 LED Full HD | 245.99
```

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---
