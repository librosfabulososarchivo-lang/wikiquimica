---
title: Gráficos y Datos
tags: [pruebas, mermaid, datos]
---

# 📊 Gráficos y Datos

Ejemplos de gráficos generados con **Mermaid**. Se ven tanto en Obsidian como en la web.

---

## Puntos de ebullición de hidrocarburos

A más carbonos, más temperatura necesitas para hervir el compuesto:

```mermaid
xychart-beta
    title "Punto de ebullición de alcanos (°C)"
    x-axis ["Metano\nCH₄", "Etano\nC₂H₆", "Propano\nC₃H₈", "Butano\nC₄H₁₀", "Pentano\nC₅H₁₂"]
    y-axis "°C" -200 --> 50
    bar [-161, -89, -42, -0.5, 36]
```

---

## Puntos de fusión de hidrocarburos

El punto de fusión también sube con el tamaño, pero con altibajos:

```mermaid
xychart-beta
    title "Punto de fusión de alcanos (°C)"
    x-axis ["Metano\nCH₄", "Etano\nC₂H₆", "Propano\nC₃H₈", "Butano\nC₄H₁₀", "Pentano\nC₅H₁₂"]
    y-axis "°C" -200 --> 0
    bar [-183, -172, -188, -138, -130]
```

El propano (C₃H₈) rompe la tendencia: funde a -188 °C, más bajo que el etano. Los alcanos con número impar de carbonos se empaquetan peor en estado sólido.

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
