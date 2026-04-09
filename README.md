# MLB Bulk Report Automation ⚾🤖

[Read this in English](#english-version) | [Leer en Español](#versión-en-español)

---

## English Version

This project enables the automated, mass generation of individual statistical reports for a list of **MLB** players. It is the ideal solution for processing entire rosters or groups of prospects in seconds.

### ✨ Automation Capabilities:
* **Batch Processing (Bulk):** Iterates over a list of official MLB IDs and generates an independent Excel file for each one.
* **Format Consistency:** Every report maintains the executive standard (Blue #1F4E78, clean borders, and Career totals row).
* **Dynamic File Management:** Automatically names files based on the player's real name retrieved from the API.
* **Memory Optimization:** Uses `ExcelWriter` contexts to ensure each file is correctly saved and closed during the loop.

### 🚀 Tech Stack:
* **Python 3.x**
* **Pandas / XlsxWriter**
* **Requests** (REST API)

---

## Versión en Español

Este proyecto permite la generación masiva y automatizada de reportes estadísticos individuales para una lista de jugadores de la **MLB**. Es ideal para procesar rosters completos o grupos de prospectos en segundos.

### ✨ Capacidades de Automatización:
* **Procesamiento por Lotes (Bulk):** Itera sobre una lista de IDs oficiales de MLB y genera un archivo Excel independiente para cada uno.
* **Consistencia de Formato:** Cada reporte mantiene el estándar ejecutivo (Azul #1F4E78, bordes limpios y fila de CARRERA).
* **Gestión de Archivos:** Crea nombres de archivos dinámicos basados en el nombre real del jugador obtenido de la API.
* **Optimización de Memoria:** Utiliza contextos de `ExcelWriter` para asegurar que cada archivo se cierre correctamente tras su creación.

### 🚀 Tecnologías:
* **Python 3.x**
* **Pandas / XlsxWriter**
* **Requests** (API REST)

---

### 📸 Execution & Output Preview / Vista Previa:

#### Bulk Console Output / Salida en Consola:
<img width="700" height="520" alt="consola_automatizacion png" src="https://github.com/user-attachments/assets/ead986d3-a68f-4ef7-87b4-0317c442b335" />

#### Final Report Result / Resultado Final del Reporte:
<img width="1366" height="736" alt="resultado_excel_pro png" src="https://github.com/user-attachments/assets/b0295c8e-5989-4d61-91a8-959be8961413" />

---
Developed by / Desarrollado por **VICTOR ARMANDO DE OLIVEIRA RODRÍGUEZ**
