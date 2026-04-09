# MLB Bulk Report Automation ⚾🤖

Este proyecto permite la generación masiva y automatizada de reportes estadísticos individuales para una lista de jugadores de la **MLB**. Es ideal para procesar rosters completos o grupos de prospectos en segundos.

### ✨ Capacidades de Automatización:
* **Procesamiento por Lotes (Bulk):** Itera sobre una lista de IDs oficiales de MLB y genera un archivo Excel independiente para cada uno.
* **Consistencia de Formato:** Cada reporte mantiene el estándar ejecutivo (Azul #1F4E78, bordes limpios y fila de CARRERA).
* **Gestión de Archivos:** Crea nombres de archivos dinámicos basados en el nombre real del jugador obtenido de la API.
* **Optimización de Memoria:** Utiliza contextos de `ExcelWriter` para asegurar que cada archivo se cierre correctamente tras su creación.

### 🚀 Tecnologías:
* **Python 3.x**
* **Pandas / XlsxWriter**
* **Requests (API REST)**

### 📸 Ejemplo de Salida Masiva:
<img width="700" height="520" alt="consola_automatizacion png" src="https://github.com/user-attachments/assets/ead986d3-a68f-4ef7-87b4-0317c442b335" />

#### Resultado final del reporte:
<img width="1366" height="736" alt="resultado_excel_pro png" src="https://github.com/user-attachments/assets/b0295c8e-5989-4d61-91a8-959be8961413" />


---
Desarrollado por **VICTOR ARMANDO DE OLIVEIRA RODRÍGUEZ**
