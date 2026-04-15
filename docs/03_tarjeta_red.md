# 03 · La tarjeta de red

## 1. Ideas clave del capítulo

- La **tarjeta de red** es el elemento que conecta el equipo a la red.
- Actúa como interfaz entre el **hardware** y la **red de comunicaciones**.
- Cada tarjeta está diseñada para una **tecnología de red concreta**.
- Requiere un **controlador (driver)** para funcionar correctamente.
- Su configuración influye directamente en el rendimiento de la red.

---

## 2. Qué es una tarjeta de red

La **tarjeta de red**, también llamada **adaptador de red** o **NIC**  
(*Network Interface Card*), es el componente que permite que un dispositivo:

- Envíe datos a la red
- Reciba datos desde la red

Cumple dos funciones básicas:

1. Convertir los datos del sistema en señales aptas para el medio físico  
2. Detectar y procesar las señales que provienen de la red

!!! note "Idea importante"
    Sin tarjeta de red **no existe comunicación en red**, aunque el equipo tenga sistema operativo.

---

## 3. Tipos de tarjetas de red

### 3.1 Según el medio de transmisión

- **Tarjetas cableadas**
  - Ethernet (UTP, STP, fibra)
- **Tarjetas inalámbricas**
  - Wi‑Fi
  - Utilizan antenas en lugar de conectores

---

### 3.2 Según el tipo de equipo

- **Equipos de sobremesa**
  - PCI / PCI‑Express
- **Portátiles**
  - Integradas
  - PCMCIA (antiguo)
  - USB
- **Servidores**
  - Tarjetas de alto rendimiento
  - Doble o múltiple puerto

---

## 4. Conexión de la tarjeta al sistema

La tarjeta de red se conecta al hardware mediante un **bus interno**.

### 4.1 Buses más utilizados

| Bus | Uso habitual |
|---|---|
| PCI‑Express | Sobremesa / Servidores |
| USB | Portátiles y sobremesa |
| PCMCIA | Portátiles antiguos |

Cuanto mayor sea:

- La velocidad del bus
- El número de bits transmitidos en paralelo  

!!! tip "Información"
    mayor será el rendimiento potencial de la tarjeta.

---

## 5. Instalación de la tarjeta de red

### 5.1 Aspectos de seguridad

Antes de instalar una tarjeta:

- Descargar electricidad estática
- Trabajar en entorno seco y limpio
- Apagar el equipo
- Manipular con cuidado los componentes

!!! warning "Seguridad"
    La electricidad estática puede **dañar irreversible­mente** una tarjeta.

---

### 5.2 Plug & Play

La mayoría de los sistemas modernos utilizan tecnología  
**Plug & Play** (“enchufar y listo”):

- El sistema detecta la tarjeta automáticamente
- Intenta instalar el controlador adecuado
- Puede requerir confirmación del usuario

---

## 6. Controladores de red (drivers)

El **controlador** es el software que permite al sistema operativo:

- Comunicarse con la tarjeta
- Controlar la transmisión y recepción de datos

Sin driver:

- La tarjeta **no funciona**
- El sistema no puede usar la red

---

### 6.1 Tipos de controladores

- Proporcionados por el **fabricante**
- Incluidos en el **sistema operativo**
- Firmados digitalmente (en sistemas modernos)

!!! tip "Buenas prácticas"
    Es recomendable mantener los drivers **actualizados** para mejorar estabilidad y rendimiento.

---

## 7. Funciones internas de la tarjeta de red

La tarjeta de red se encarga de:

- Crear tramas de datos
- Detectar errores
- Controlar el acceso al medio
- Filtrar tramas según la dirección MAC

Además, incorpora:

- Una **dirección física única** (dirección MAC)
- Memoria interna
- Electrónica de control

---

## 8. Parámetros configurables de una tarjeta de red

Algunas tarjetas permiten configurar:

- Velocidad (10 / 100 / 1000 Mbps)
- Modo dúplex (half / full)
- Tipo de conexión (Ethernet, Wi‑Fi)
- Ahorro de energía

Estas opciones pueden ajustarse:

- Mediante interfaz gráfica
- Mediante comandos

---

## 9. Configuración en sistemas operativos

### 9.1 En Windows

- Panel de control
- Configuración de red
- Propiedades del adaptador

Permite:

- Activar/desactivar la tarjeta
- Configurar IP
- Ver estado de conexión

---

### 9.2 En Linux

Configuración mediante comandos:

- `ifconfig` → tarjetas cableadas
- `iwconfig` → tarjetas inalámbricas

También existe configuración gráfica dependiendo de la distribución.

!!! tip "Examen"
    `ifconfig` → cable  
    `iwconfig` → Wi‑Fi

---

## 10. Tarjetas de red avanzadas

Algunas tarjetas incorporan funciones adicionales:

- **Arranque por red (PXE)**
  - Permite cargar el sistema operativo desde la red
- **Offloading**
  - Descarga tareas del procesador central
- **Múltiples interfaces**
  - Balanceo o redundancia

Estas características son comunes en **servidores**.

---

## 11. Buenas prácticas profesionales

- Instalar tarjetas compatibles con la red
- Usar drivers oficiales
- Documentar el hardware instalado
- Probar la conexión tras la instalación
- Evitar configuraciones innecesarias

---

## 12. Resumen para estudiar

### Esquema mental

- Tarjeta de red
  - Cableada / Inalámbrica
  - Interfaz (PCIe, USB)
  - Driver
  - Configuración
  - Dirección MAC

### Puntos habituales de examen

- Función de una tarjeta de red
- Diferencia entre hardware y driver
- Qué es Plug & Play
- Comandos `ifconfig` / `iwconfig`
- Dirección MAC