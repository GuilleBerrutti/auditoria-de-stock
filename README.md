## 🎯 Objetivo del Proyecto

Analizar el estado del inventario para optimizar la gestión de stock, evitar quiebres y mejorar la eficiencia en la toma de decisiones del área de compras.

Este proyecto transforma datos operativos en información accionable mediante lógica SQL aplicada a un caso real de control de inventario.

---

## 🧠 Problema de Negocio

Las organizaciones enfrentan desafíos frecuentes en la gestión de inventario:

- Riesgo de ruptura de stock (pérdida de ventas)  
- Exceso de inventario (capital inmovilizado)  
- Falta de visibilidad sobre el estado real del stock  

👉 Pregunta clave del análisis:

**¿Cómo priorizar decisiones de compra en función del estado actual del inventario?**

---

## 📊 Metodología

El análisis se desarrolló utilizando SQL (PostgreSQL) para:

- Evaluar niveles de stock por producto  
- Clasificar inventario según criticidad  
- Calcular el valor total del inventario disponible  
- Generar indicadores visuales para facilitar la toma de decisiones  

---

## 🛠️ Técnicas Aplicadas

- **Lógica condicional (`CASE WHEN`)**  
  Clasificación del inventario en categorías de riesgo (Alto, Medio, Bajo)

- **Casting de datos (`::numeric`)**  
  Conversión para asegurar precisión en cálculos financieros

- **Alias y ordenamiento**  
  Mejora de la legibilidad del reporte para usuarios de negocio

---

## 📊 Resultado del Análisis

El resultado es un reporte que permite visualizar el estado del inventario mediante un sistema tipo “semáforo”:

- 🔴 **Stock crítico** → requiere reposición inmediata  
- 🟡 **Stock moderado** → monitoreo y planificación  
- 🟢 **Sobrestock** → oportunidad de optimización  

<details>
  <summary><b>🔍 Ver reporte de inventario</b></summary>
  <br>
  <p align="center">
    <img src="proyecto-control-stock/Scripts/Results/resultado_stock.png" width="800">
  </p>
</details>

---

## 📈 Conclusiones y Recomendaciones

El análisis permite establecer prioridades claras para la gestión de inventario:

- **Reposición inmediata:**  
  Productos con stock crítico deben ser priorizados para evitar pérdidas de venta  

- **Optimización de capital:**  
  Productos en sobrestock representan una oportunidad para reducir costos  

- **Automatización de decisiones:**  
  El script permite generar un listado de prioridades de forma rápida y consistente  

---

## 📂 Recursos del Proyecto

- [📄 Script SQL Completo](proyecto-control-stock/Scripts/script.sql)  
- [📊 Conclusiones Técnicas](proyecto-control-stock/Scripts/Results/conclusiones.md)  
 
