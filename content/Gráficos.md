---
title: Gráficos y Datos
tags: [pruebas, mermaid, datos]
---

# 📊 Gráficos y Datos

Ejemplos de gráficos interactivos generados con **Mermaid**. Se ven tanto en Obsidian como en la web.

---

## Puntos de fusión y ebullición de hidrocarburos

Comparativa de los primeros cuatro [[02-Química Orgánica/Hidrocarburos|alcanos]]:

```mermaid
xychart-beta
    title "Puntos de fusión y ebullición (°C)"
    x-axis ["Metano (CH₄)", "Etano (C₂H₆)", "Propano (C₃H₈)", "Butano (C₄H₁₀)"]
    y-axis "Temperatura °C" -200 --> 50
    bar [-183, -172, -188, -138]
    bar [-161, -89, -42, -0.5]
```

🔵 Azul = punto de fusión | 🟠 Naranja = punto de ebullición

A más carbonos, más sube el punto de ebullición. El punto de fusión no sigue un patrón tan lineal.

---

## Composición del aire seco

```mermaid
pie title Composición del aire seco (%)
    "Nitrógeno (N₂)" : 78
    "Oxígeno (O₂)" : 21
    "Argón (Ar)" : 0.93
    "CO₂ y otros" : 0.07
```

Fuente: composición atmosférica estándar a nivel del mar.

---

## Estados del agua según temperatura

```mermaid
flowchart LR
    H[/"❄️ Hielo"/] -->|"0 °C"| L[/"💧 Agua líquida"/]
    L -->|"100 °C"| G[/"💨 Vapor"/]
    G -->|"Condensación\n100 °C"| L
    L -->|"Congelación\n0 °C"| H
```

A 1 atmósfera de presión. A mayor altitud (menor presión), el agua hierve a menor temperatura.

> 📖 **Ver también:** [[04-Termodinámica/Entalpía]], [[02-Química Orgánica/Hidrocarburos]]
