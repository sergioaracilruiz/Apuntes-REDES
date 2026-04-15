# 01 · Medios de transmisión

## 1. Ideas clave del capítulo

- El **medio de transmisión** es el soporte físico por el que viaja la información.
- Pertenece a la **capa física (capa 1) del modelo OSI**.
- La elección del medio influye directamente en:
  - Velocidad
  - Distancia
  - Fiabilidad
  - Coste
- En redes locales se utilizan principalmente:
  - Cables de par trenzado
  - Fibra óptica
  - Sistemas inalámbricos

---

## 2. El nivel físico del modelo OSI

La instalación física de una red se centra en la **capa 1 del modelo OSI**, responsable de:

- La transmisión de bits (0 y 1)
- Las características eléctricas, ópticas o radioeléctricas
- El tipo de cableado, conectores y señal

Esta capa **no interpreta datos**, solo garantiza que la señal llegue correctamente entre dispositivos.

---

## 3. Qué es un medio de transmisión

El **medio de transmisión** es el soporte físico que permite transportar la información entre dos dispositivos de red.

Según la naturaleza de la señal, puede ser:

- **Eléctrico** → cables de cobre
- **Óptico** → fibra óptica
- **Electromagnético** → radio (Wi‑Fi)

La **calidad de la transmisión** depende de factores como:

- Atenuación
- Interferencias
- Distancia
- Velocidad de transmisión

---

## 4. Cables de pares metálicos (par trenzado)

Son los cables más utilizados en redes de área local (LAN).

### 4.1 Características generales

- Formados por **pares de hilos de cobre**
- Cada par está **trenzado** para reducir interferencias
- Cumplen leyes eléctricas (Ley de Ohm y electromagnetismo)
- Económicos y fáciles de instalar

Cuando se superan ciertas distancias, la señal se degrada y pueden ser necesarios **repetidores**.

---

### 4.2 Tipos de cables de par trenzado

#### Cable UTP (Unshielded Twisted Pair)

- Sin apantallamiento
- Flexible y barato
- Muy utilizado en instalaciones estándar
- Sensible a interferencias

#### Cable STP (Shielded Twisted Pair)

- Incorpora **malla metálica de protección**
- Mucha mejor inmunidad al ruido
- Menos flexible
- **Debe conectarse a tierra**

!!! tip "Apunte"
    En la práctica profesional, **UTP es el más usado**, salvo en entornos con mucho ruido eléctrico.

---

### 4.3 Comparativa UTP vs STP

| Característica | UTP | STP |
|---|---|---|
| Precio | Bajo | Más alto |
| Flexibilidad | Alta | Baja |
| Protección frente al ruido | Baja | Alta |
| Dificultad de instalación | Baja | Alta |
| Conexión a tierra | No | Sí |

---

## 5. Categorías y clases del cableado

### 5.1 Categorías (prestaciones eléctricas)

Las **categorías** definen las prestaciones del cable en frecuencia y velocidad.

| Categoría | Frecuencia máx. | Uso típico |
|---|---|---|
| Cat 3 | 10 MHz | 10 Mbps (obsoleta) |
| Cat 5 | 100 MHz | 100 Mbps |
| Cat 5e | 100 MHz | 1 Gbps |
| Cat 6 | 250 MHz | 1–10 Gbps |
| Cat 7 | 600 MHz | 10 Gbps |

!!! tip "Apunte actualidad"
    Actualmente las más utilizadas son **Cat 5e y Cat 6**.

---

### 5.2 Clases (aplicaciones)

Las **clases** definen la relación entre ancho de banda, distancia y aplicación.

| Clase | Ancho de banda |
|---|---|
| A | 100 kHz |
| B | 1 MHz |
| C | 20 MHz |
| D | 100 MHz |
| E | 250 MHz |
| F | 600 MHz |

Categoría y clase están relacionadas, pero **no son lo mismo**.

---

## 6. Fibra óptica

La **fibra óptica** transmite información mediante **pulsos de luz**.

### 6.1 Características principales

- Inmune a interferencias electromagnéticas
- Muy alta velocidad
- Grandes distancias
- Más cara y frágil que el cobre

!!! note "Idea importante"
    Una sola fibra puede transmitir **decenas de Gbps** a kilómetros de distancia.

---

### 6.2 Tipos de fibra óptica

#### Fibra monomodo (SMF)

- Núcleo muy estrecho (menor de 10 μm)
- Un solo camino para la luz
- Alcances de decenas de kilómetros
- Usada en backbone y campus

#### Fibra multimodo (MMF)

- Núcleo más ancho (50 o 62,5 μm)
- Múltiples reflexiones internas
- Distancias más cortas
- Más económica

---

### 6.3 Comparativa fibra vs cobre

| Característica | Par trenzado | Fibra óptica |
|---|---|---|
| Velocidad | Media / Alta | Muy alta |
| Distancia | Hasta 100 m | Kilómetros |
| Inmunidad al ruido | Baja | Total |
| Coste | Bajo | Alto |
| Fragilidad | Baja | Alta |

---

## 7. Sistemas inalámbricos

Los **sistemas inalámbricos** transmiten información mediante **ondas electromagnéticas**.

### 7.1 Ventajas

- Movilidad
- Flexibilidad
- Instalación sencilla
- No requieren cableado físico

### 7.2 Inconvenientes

- Menor velocidad que cableado
- Mayor latencia
- Sensibles a interferencias
- Seguridad más compleja

---

### 7.3 Fenómenos que afectan a la señal

- **Reflexión**: rebote de la señal en superficies duras
- **Difracción**: la señal rodea obstáculos
- **Dispersión**: difusión en múltiples direcciones

!!! warning "Examen"
    Estos fenómenos **reducen la calidad del Wi‑Fi** y provocan cortes o baja velocidad.

---

## 8. Resumen para estudiar

### Esquema mental

- Medios de transmisión
  - Par trenzado
    - UTP
    - STP
    - Categorías 5e / 6
  - Fibra óptica
    - Monomodo
    - Multimodo
  - Sistemas inalámbricos
    - Wi‑Fi
    - Interferencias

### Puntos habituales de examen

- Diferencias entre UTP y STP
- Categorías más usadas en LAN
- Ventajas de la fibra óptica
- Fenómenos de la señal inalámbrica