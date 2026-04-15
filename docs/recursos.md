# Recursos y esquemas

Este documento reúne **esquemas, tablas resumen y listas clave** para facilitar el estudio,
el repaso rápido y la preparación de exámenes relacionados con la **instalación física de redes**.

---

## 1. Modelo OSI (recordatorio rápido)

| Capa | Nombre | Función principal |
|---|---|---|
| 7 | Aplicación | Servicios al usuario |
| 6 | Presentación | Formato de datos |
| 5 | Sesión | Control de sesión |
| 4 | Transporte | Comunicación extremo a extremo |
| 3 | Red | Direccionamiento lógico (IP) |
| 2 | Enlace | Direcciones MAC, tramas |
| 1 | Física | Medios de transmisión |

📌 En este temario trabajamos sobre todo con las **capas 1 y 2**.

---

## 2. Medios de transmisión (esquema global)

### Clasificación principal

- **Cobre**
  - UTP
  - STP
- **Fibra óptica**
  - Monomodo (SMF)
  - Multimodo (MMF)
- **Inalámbrico**
  - Wi‑Fi

---

### Comparativa rápida

| Medio | Velocidad | Distancia | Inmunidad al ruido | Coste |
|---|---|---|---|---|
| UTP | Media‑Alta | 100 m | Baja | Bajo |
| STP | Alta | 100 m | Alta | Medio |
| Fibra | Muy alta | Km | Total | Alto |
| Wi‑Fi | Media | Variable | Media | Bajo |

---

## 3. Categorías de cable más habituales

| Categoría | Velocidad típica | Uso actual |
|---|---|---|
| Cat 5 | 100 Mbps | Obsoleta |
| Cat 5e | 1 Gbps | Muy común |
| Cat 6 | 1–10 Gbps | Instalaciones nuevas |
| Cat 7 | 10 Gbps | Profesional / backbone |

---

## 4. Conectores más usados

### Par trenzado

- RJ45 → redes Ethernet
- RJ11 / RJ12 → telefonía

### Fibra óptica

- SC → muy común
- ST → instalaciones híbridas
- LC → alta densidad

### Coaxial (histórico)

- BNC
- T coaxial + terminadores

---

## 5. Herramientas básicas del instalador

- Crimpadora
- Pelacables
- Comprobador de cables
- Certificador
- Destornilladores
- Bridas y etiquetas

✅ **Regla clave**: cada cable se prueba **nada más terminarse**.

---

## 6. Tarjeta de red (resumen rápido)

### Funciones

- Generar tramas
- Detectar errores
- Controlar el acceso al medio
- Filtrar por dirección MAC

### Elementos clave

- Interfaz (PCIe, USB)
- Dirección MAC
- Driver
- Parámetros de velocidad y dúplex

---

## 7. Comandos básicos de red (Linux)

| Comando | Función |
|---|---|
| `ifconfig` | Configuración cableada |
| `iwconfig` | Configuración Wi‑Fi |

💡 En sistemas modernos también se usan herramientas gráficas.

---

## 8. Ethernet – resumen visual

### Tipos principales

- 10 Mbps → 10BaseT
- 100 Mbps → 100BaseTX
- 1 Gbps → 1000BaseTX / LX
- 10 Gbps → 10GBaseT / fibra

### Dispositivos y colisiones

| Dispositivo | Dominios de colisión |
|---|---|
| Hub | Uno solo |
| Switch | Uno por puerto |
| Router | Los separa |

---

## 9. Power over Ethernet (PoE)

### Elementos

- **PSE** → suministra energía (switch PoE)
- **PD** → recibe energía (cámara, AP)

### Usos normales

- Cámaras IP
- Teléfonos IP
- Puntos de acceso Wi‑Fi

---

## 10. Cableado estructurado – esquema general

```text
Puesto de trabajo
    ↓
Cableado horizontal
    ↓
Cuarto de comunicaciones (rack)
    ↓
Cableado vertical / backbone
    ↓
CPD / Campus
