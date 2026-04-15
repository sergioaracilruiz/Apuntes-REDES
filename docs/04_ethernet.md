# 04 · Ethernet

## 1. Ideas clave del capítulo

- **Ethernet** es la tecnología de red de área local más utilizada.
- Está normalizada por el estándar **IEEE 802.3**.
- Define cómo se transmiten los datos y cómo se accede al medio.
- Utiliza direcciones **MAC** para identificar los dispositivos.
- La velocidad y el medio físico determinan el tipo de Ethernet.

---

## 2. Qué es Ethernet

**Ethernet** es una tecnología de red que define:

- El formato de las tramas
- El método de acceso al medio
- Las velocidades de transmisión
- Los medios físicos soportados

Se diseñó originalmente para redes cableadas, aunque hoy convive con redes inalámbricas.

!!! note "Idea importante"
    Ethernet funciona principalmente en las **capas 1 y 2 del modelo OSI** (física y enlace).

---

## 3. El acceso al medio: CSMA/CD

Ethernet utiliza el método **CSMA/CD**  
(*Carrier Sense Multiple Access with Collision Detection*).

### Funcionamiento básico

1. La estación **escucha el canal**
2. Si está libre, **transmite**
3. Si detecta una **colisión**:
   - Detiene la transmisión
   - Envía una señal de aviso (*jam*)
   - Espera un tiempo aleatorio
   - Reintenta el envío

!!! warning "Examen"
    CSMA/CD solo se usa en **Ethernet compartida** (hubs).  
    En redes con **switch**, las colisiones desaparecen.

---

## 4. Colisiones y dominios de colisión

### 4.1 Colisión

Una **colisión** se produce cuando:

- Dos estaciones transmiten al mismo tiempo
- Sus señales se superponen en el medio

Esto provoca:

- Pérdida de datos
- Retransmisiones
- Reducción del rendimiento

---

### 4.2 Dominio de colisión

Un **dominio de colisión** es la parte de la red donde:

- Pueden producirse colisiones entre equipos

Dispositivos y dominios:

- **Hub** → un único dominio de colisión
- **Switch** → un dominio por puerto
- **Router** → separa dominios de colisión

!!! tip "Apunte"
    Los **switches eliminan las colisiones** en Ethernet moderna.

---

## 5. Trama Ethernet

La información en Ethernet se transmite en forma de **tramas**.

Una trama Ethernet incluye:

- Dirección MAC destino
- Dirección MAC origen
- Datos
- Control de errores

### Función de la tarjeta de red

La tarjeta de red:

- Construye la trama antes de enviarla
- Comprueba errores al recibirla
- Descarta tramas no dirigidas a su MAC

---

## 6. Tipos de Ethernet según velocidad y medio

### 6.1 Ethernet a 10 Mbps

- **10Base5**
  - Coaxial grueso
  - Hasta 500 m
- **10Base2**
  - Coaxial fino
  - Hasta 185 m
- **10BaseT**
  - UTP
  - Hasta 100 m

---

### 6.2 Fast Ethernet (100 Mbps)

- **100BaseTX**
  - UTP/STP categoría 5
  - Hasta 100 m
- **100BaseFX**
  - Fibra óptica
  - Hasta 2 km en dúplex

---

### 6.3 Gigabit Ethernet (1 Gbps)

- **1000BaseTX**
  - UTP categoría 5e / 6
  - Hasta 100 m
- **1000BaseSX**
  - Fibra multimodo
  - Hasta 550 m
- **1000BaseLX**
  - Fibra monomodo
  - Hasta 10 km

---

### 6.4 Ethernet a 10 Gbps

- **10GBaseT**
  - UTP categoría 6 o superior
  - Hasta 100 m
- **10GBaseSR / LR / ER**
  - Fibra óptica
  - Desde cientos de metros hasta decenas de km

---

## 7. Resumen comparativo de tipos Ethernet

| Tipo | Medio | Velocidad | Distancia típica |
|---|---|---|---|
| 10BaseT | UTP | 10 Mbps | 100 m |
| 100BaseTX | UTP Cat 5 | 100 Mbps | 100 m |
| 1000BaseTX | UTP Cat 5e | 1 Gbps | 100 m |
| 1000BaseLX | Fibra | 1 Gbps | Hasta 10 km |
