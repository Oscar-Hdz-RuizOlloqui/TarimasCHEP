# 📊 Dashboard Planeación Panovo - Power BI

Este repositorio contiene un ejemplo real de implementación de una solución en SharePoint orientada al control y gestión del uso de tarimas CHEP. 

---

## 📌 Objetivo

Controlar y dar seguimiento al uso de tarimas CHEP, incluyendo el análisis de tarifas de renta, movimientos y eficiencia operativa, con el propósito de reducir costos logísticos y prevenir cargos innecesarios por uso ineficiente o pérdida de activos.

---

## 🛠️ Tecnologías Utilizadas

- Power BI Desktop (DirectQuery)
- Sharepoint (Consultas a vistas y tablas en producción)
- DAX (Medidas complejas para disponibilidad, eficiencia, forecast, etc.)
- GitHub (para control de versiones y documentación técnica)

---

## 📁 Estructura del Repositorio

```plaintext
TarimasCHEP/
├── pbix/                                   → Archivo PBIX del tablero
├── README.md                               → Descripción general del repositorio
├── docs/
│   ├── Medidas.md                          → Medidas DAX documentadas
│   ├── Columnas_Calculadas.md              → DAX documentadas
│   ├── Tablas.md                  → DAX documentadas
│   └── video_tutorial.md                   → Guía de uso del dashboard
├── img/
│   ├── preview_dashboard.png               → Captura del dashboard
│   └── Modelo_Datos.png                    → Relación entre tablas
```

---

## 📷 Preview del Dashboard

![Preview](img/preview_dashboard.png)

---

## 📎 Cómo utilizarlo

1. Clona este repositorio.
2. Abre el archivo `pbix/DA_TarimasCHEP` con Power BI Desktop.
3. Conecta tu fuente de datos o consulta en SQL Server.
4. Revisa la documentación en `/docs` para entender cada fórmula y estructura.

---

## 📄 Licencia

MIT – Libre uso con atribución.
