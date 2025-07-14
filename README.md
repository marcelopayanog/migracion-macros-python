# Migración de Macros de Excel a Python

Este proyecto muestra cómo migrar un proceso automatizado en Excel con macros (VBA) a un script en Python, utilizando `pandas` y `openpyxl`.

## 📌 Objetivo

Automatizar la generación de reportes de usuarios activos que antes se realizaba con macros en Excel, ahora usando Python.

## 📁 Archivos

- `usuarios_con_macros.xlsm`: archivo con macro original
- `script_migracion.py`: versión en Python que genera el mismo reporte
- `reporte_python.xlsx`: archivo generado automáticamente

## 🐍 Tecnologías

- Python 3.10+
- Pandas
- Openpyxl

## 📈 Resultado

El script lee el Excel, filtra los usuarios activos, y crea un nuevo archivo con los datos procesados.

---
