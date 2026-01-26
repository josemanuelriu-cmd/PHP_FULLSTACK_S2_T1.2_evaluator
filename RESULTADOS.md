# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 21 correctas de 23 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.45 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.32 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 6: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 8: Correcto

⏱ Tiempo: 0.33 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 9: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 10: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 11: Correcto

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 12: Correcto

⏱ Tiempo: 0.28 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ✅ Query 13: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 14: Correcto

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 15: Correcto

⏱ Tiempo: 0.34 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 16: Correcto

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 17: Correcto

⏱ Tiempo: 0.32 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 18: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 19: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 20: Correcto

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ✅ Query 21: Correcto

⏱ Tiempo: 0.30 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 22: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
 nombre | precio | nombre del fabricante
+Disco duro SATA3 1TB | 86.99 | Seagate
+Disco SSD 1 TB | 150.99 | Samsung
+GeForce GTX 1050Ti | 185.00 | Gigabyte
+GeForce GTX 1080 Xtreme | 755.00 | Crucial
+Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard
+Impresora HP Laserjet Pro M26nw | 180.00 | Hewlett-Packard
+Memoria RAM DDR4 8GB | 120.00 | Crucial
 Monitor 24 LED Full HD | 202.00 | Asus
 Monitor 27 LED Full HD | 245.99 | Asus
-Memoria RAM DDR4 8GB | 120.00 | Crucial
-GeForce GTX 1080 Xtreme | 755.00 | Crucial
-GeForce GTX 1050Ti | 185.00 | Gigabyte
-Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard
-Impresora HP Laserjet Pro M26nw | 180.00 | Hewlett-Packard
+Portátil Ideapd 320 | 444.00 | Lenovo
 Portátil Yoga 520 | 559.00 | Lenovo
-Portátil Ideapd 320 | 444.00 | Lenovo
-Disco SSD 1 TB | 150.99 | Samsung
-Disco duro SATA3 1TB | 86.99 | Seagate
```

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 23: Error
- **Descripción**: 'NoneType' object is not iterable

