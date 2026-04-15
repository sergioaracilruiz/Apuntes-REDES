# 02 · Conectores y herramientas

## 1. Ideas clave del capítulo

- Los **conectores** permiten que la señal eléctrica u óptica entre y salga del cable.
- Un mal conector o una mala conexión es una de las **principales causas de fallos en redes**.
- Cada tipo de cable requiere **conectores y herramientas específicas**.
- La calidad del cableado depende tanto del cable como de la **correcta conectorización**.

---

## 2. Qué es un conector de red

Un **conector** (o interfaz física) es el elemento que une:

- El **cable** con
- Un **dispositivo de red** (tarjeta de red, switch, router, patch panel, etc.)

En una red local, los conectores deben garantizar:

- Continuidad eléctrica u óptica
- Correcta impedancia
- Sujeción mecánica fiable

!!! note "Idea importante"
    La mayoría de los problemas en redes LAN **no están en el software**, sino en cables y conectores.

---

## 3. Conectores para cables de par trenzado

### 3.1 Conector RJ45

Es el **conector más utilizado en redes Ethernet**.

Características principales:

- 8 pines (4 pares)
- Usado con cable UTP y STP
- Compatible con categorías 5e, 6, etc.

Usos habituales:

- Conexión de PCs
- Switches
- Patch panels
- Rosetas de red

---

### 3.2 Otros conectores de pares

- **RJ11 / RJ12**
  - Usados en telefonía
  - Menor número de pines
- **AUI / DB15**
  - Antiguos sistemas Ethernet
  - Hoy prácticamente en desuso

---

## 4. Conectores para cable coaxial

El cable coaxial se utilizó en las primeras redes Ethernet.

### Conectores más comunes

- **BNC**
  - Mantiene la estructura coaxial
  - Muy usado en 10Base2
- **T coaxial**
  - Permite conectar una estación a un bus
- **Terminadores**
  - Resistencias de 50 Ω
  - Evitan reflexiones de señal

!!! warning "Examen"
    En redes coaxiales, **sin terminadores la red no funciona**.

---

## 5. Conectores para fibra óptica

La fibra óptica requiere conectores de **alta precisión**, ya que trabajan con luz.

### 5.1 Conectores más usados

#### Conector SC (Straight Connection)

- Inserción directa
- Uso frecuente en Gigabit Ethernet
- Muy común en instalaciones actuales

#### Conector ST (Straight Tip)

- Requiere giro para bloquearse
- Similar a conectores coaxiales
- Usado en instalaciones híbridas

---

### 5.2 Otros conectores de fibra

- **FC**
- **LC**
- **MT Array**
- **SC Duplex**

Cada uno tiene aplicaciones específicas según:

- Densidad
- Facilidad de conexión
- Tipo de instalación

---

## 6. Elementos físicos complementarios

Además de cables y conectores, en una instalación real encontramos:

- **Racks**
  - Armarios normalizados (19")
  - Organizan todos los dispositivos
- **Patch panels**
  - Facilitan la gestión del cableado
  - Evitan manipular el cable largo
- **Latiguillos**
  - Cables cortos de interconexión
- **Canaletas**
  - Protegen el cableado
  - Mejoran organización y estética
- **Rosetas**
  - Punto final del cableado en el puesto de trabajo

---

## 7. Herramientas de conectorización

Una buena instalación requiere **herramientas adecuadas**.

### 7.1 Herramientas básicas

- **Crimpadora**
  - Fija el conector RJ45 al cable
- **Pelacables**
  - Retira la cubierta exterior
- **Cúter o cuchilla**
- **Destornilladores**
- **Pinzas**

!!! tip "Buenas prácticas"
    Nunca improvises herramientas: **un mal crimpado provoca fallos intermitentes**.

---

### 7.2 Herramientas para fibra óptica

- Cortadora de fibra
- Pulidora
- Kits de alineación
- Herramientas de limpieza

!!! warning "Importante"
    La fibra es **muy frágil** y no debe doblarse en exceso.

---

## 8. Equipos de comprobación y certificación

Antes de dar por buena una instalación hay que **probarla**.

### Tipos de comprobadores

- **Comprobador de continuidad**
  - Verifica que los hilos están bien conectados
- **Verificador de cables**
  - Detecta cruces o pares incorrectos
- **Certificador**
  - Mide:
    - Atenuación
    - Diafonía (NEXT)
    - Longitud
    - Categoría real del cable

!!! note "Profesional"
    En instalaciones reales, **la certificación del cableado suele ser obligatoria**.

---

## 9. Buenas prácticas en la conectorización

- No destrenzar más de lo necesario
- Respetar el **código de colores**
- Etiquetar cables y conectores
- Probar cada cable después de montarlo
- Mantener herramientas ordenadas

### Seguridad y medioambiente

- Tener cuidado con herramientas cortantes
- Reciclar residuos electrónicos
- Mantener el puesto de trabajo limpio

---

## 10. Resumen para estudiar

### Esquema mental

- Conectores
  - RJ45
  - BNC
  - Fibra (SC, ST)
- Elementos físicos
  - Racks
  - Patch panels
  - Rosetas
- Herramientas
  - Crimpadora
  - Pelacables
  - Certificadores

### Puntos habituales de examen

- Diferencia entre RJ45 y RJ11
- Función del patch panel
- Por qué se certifica el cableado
- Herramientas básicas de conectorización
``