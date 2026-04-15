# 05 · Cableado estructurado e instalación de red

## 1. Ideas clave del capítulo

- Una instalación de red profesional requiere **planificación y documentación**.
- El **cableado estructurado** es un sistema normalizado y modular.
- Permite **orden, flexibilidad y escalabilidad** en la red.
- Sigue **estándares internacionales** (ANSI/TIA/EIA).
- Facilita el mantenimiento y las futuras ampliaciones.

---

## 2. Qué es el cableado estructurado

El **cableado estructurado** es un sistema organizado de:

- Cables
- Conectores
- Canalizaciones
- Armarios
- Etiquetas y documentación

Diseñado para crear una **infraestructura genérica de comunicaciones** en un edificio o campus.

!!! note "Idea importante"
    Un buen cableado estructurado **no depende de una tecnología concreta** y permite cambios sin rehacer la instalación.

---

## 3. Ventajas del cableado estructurado

Un sistema de cableado estructurado bien diseñado ofrece:

- **Seguridad** → menos errores y fallos
- **Flexibilidad** → cambios rápidos de configuración
- **Escalabilidad** → crecimiento sin rehacer la red
- **Orden y limpieza**
- **Facilidad de mantenimiento**

---

## 4. El proyecto de instalación de red

Antes de instalar una red es necesario elaborar un **proyecto de instalación**.

### 4.1 Fases del proyecto

1. Estudio de necesidades
2. Diseño de la red
3. Selección de materiales
4. Presupuesto
5. Ejecución
6. Pruebas y certificación
7. Documentación final

---

### 4.2 Tareas habituales en la instalación

- Instalación de tomas de corriente
- Colocación de rosetas y jacks
- Tendido del cableado
- Conectorización en rosetas y patch panels
- Pruebas del cableado
- Etiquetado
- Instalación de dispositivos de red
- Configuración del software

!!! tip "Examen"
    El **orden correcto de las tareas** es una pregunta muy habitual.

---

## 5. Elementos de la instalación

### 5.1 Armarios o racks

Los **racks** son armarios normalizados donde se alojan:

- Switches
- Routers
- Patch panels
- Servidores
- Sistemas SAI

Características principales:

- Anchura estándar: **19 pulgadas**
- Altura medida en **U (Rack Units)**

!!! note "Dato técnico"
    1 U = 1,75 pulgadas ≈ 44,45 mm

---

### 5.2 Canaletas y conducciones

Las **canaletas** protegen y organizan los cables:

- En paredes
- Falsos suelos
- Falsos techos

Buenas prácticas:

- Separar **datos** y **fuerza eléctrica**
- Evitar motores y líneas de alta tensión
- Sujetar los cables con bridas

---

### 5.3 Rosetas y patch panels

- **Rosetas**
  - Punto final del cableado en el puesto
- **Patch panels**
  - Permiten gestionar las conexiones sin manipular cables largos

!!! tip "Apunte"
    Cambiar un latiguillo es más seguro que tocar el cableado fijo.

---

## 6. Estructura del cableado estructurado

El sistema se organiza en **subsistemas jerarquizados**.

### 6.1 Subsistemas principales

- **Puesto de trabajo**
- **Cableado horizontal**
- **Cuarto de comunicaciones (distribuidor)**
- **Cableado vertical o backbone**
- **Subsistema de campus**

---

### 6.2 Cableado horizontal

- Conecta las rosetas con el armario de planta
- Normalmente UTP Cat 5e o Cat 6
- Longitud máxima:
  - 90 m de cable fijo
  - 10 m de latiguillos

---

### 6.3 Cableado vertical (backbone)

- Comunica armarios de distintas plantas
- Requiere:
  - Alta velocidad
  - Alta fiabilidad
- Normalmente fibra óptica

---

## 7. Cuartos de comunicaciones y CPD

### 7.1 Cuartos de comunicaciones

Son espacios técnicos donde se concentran:

- Cableado
- Armarios
- Electrónica de red

Se recomienda al menos **uno por planta**.

---

### 7.2 Centro de Proceso de Datos (CPD)

El **CPD** alberga los sistemas críticos:

- Servidores
- Almacenamiento
- Seguridad
- Comunicaciones externas

Requisitos del CPD:

- Acceso restringido
- Aire acondicionado
- Control de temperatura y humedad
- Alimentación eléctrica segura
- Sistemas SAI

!!! warning "Importante"
    Un fallo eléctrico sin SAI puede provocar **pérdida de datos**.

---

## 8. Instalación eléctrica y climatización

En redes profesionales es imprescindible:

- Tomas con **tierra**
- Cuadros eléctricos independientes
- Protección frente a picos de tensión
- Aire acondicionado redundante

Un entorno inadecuado puede dañar los equipos incluso aunque la red esté bien diseñada.

---

## 9. Etiquetado y documentación

Todo elemento debe identificarse de forma **clara y única**.

### Buenas prácticas de etiquetado

- Etiquetar ambos extremos del cable
- Usar códigos neutros (salas, rosetas)
- Documentar cambios

Normativa habitual:
- **EIA/TIA‑606** (administración del cableado)

---

## 10. Certificación del cableado

La **certificación** verifica que la instalación:

- Cumple los estándares
- Soporta las velocidades previstas

### Parámetros comunes

- Continuidad
- Longitud
- Atenuación
- Diafonía (NEXT)

Normas habituales:
- ANSI/TIA/EIA‑568
- ISO/IEC 11801

!!! note "Profesional"
    Muchas instalaciones **no se consideran finalizadas sin certificación**.

---

## 11. Buenas prácticas profesionales

- No improvisar
- Seguir los estándares
- Mantener orden y limpieza
- Respetar la seguridad laboral
- Separar residuos y reciclar

---

## 12. Resumen para estudiar

### Esquema mental

- Proyecto de instalación
- Cableado estructurado
  - Horizontal
  - Vertical (backbone)
- Racks
- Patch panels
- CPD
- Certificación

### Puntos habituales de examen

- Qué es cableado estructurado
- Qué es un rack y una U
- Longitudes máximas del cable horizontal
- Función del backbone
- Por qué se certifica una instalación