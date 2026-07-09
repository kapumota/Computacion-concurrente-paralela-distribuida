### Laboratorio de Computación Concurrente, Paralela y Distribuida 

Repositorio con actividades, notebooks, evaluaciones y ejemplos prácticos sobre programación concurrente, paralelismo, sistemas distribuidos, mensajería, microservicios, contenedores y Kubernetes.

#### Propósito del repositorio

Este repositorio organiza materiales de trabajo para estudiar cómo se construyen, ejecutan y analizan programas que aprovechan concurrencia, paralelismo y distribución. El enfoque combina teoría aplicada, experimentación en notebooks, scripts ejecutables y ejercicios de infraestructura.

El repositorio no está diseñado como una única aplicación monolítica. Su función principal es servir como laboratorio docente progresivo para explorar conceptos fundamentales y técnicas prácticas de sistemas computacionales modernos.

### Ejes temáticos

#### 1. Computación concurrente

Incluye actividades sobre hilos, ejecución concurrente, programación asíncrona, sincronización, consistencia y coordinación de tareas.

Temas principales:

- Hilos y multithreading.
- Programación asíncrona con `asyncio`.
- Sincronización y consistencia.
- Condiciones de carrera.
- Coordinación de tareas concurrentes.
- Uso de `concurrent.futures`.

#### 2. Computación paralela

Incluye notebooks y ejemplos orientados a paralelismo, multiprocessing, análisis de rendimiento y modelos de paralelismo.

Temas principales:

- Multiprocessing.
- Modelos de paralelismo.
- Arquitecturas paralelas.
- Memoria compartida y memoria distribuida.
- Algoritmos paralelos.
- Análisis de rendimiento.
- Cache y efectos de arquitectura.

#### 3. Sistemas distribuidos

Incluye materiales sobre comunicación entre procesos, sockets, servicios, modelos distribuidos, algoritmos distribuidos, mensajería, microservicios y despliegue con contenedores.

Temas principales:

- Sockets cliente-servidor.
- MapReduce experimental.
- Sistemas de archivos distribuidos.
- Bases de datos distribuidas.
- Propiedades de sistemas distribuidos.
- Mensajería.
- Microservicios.
- Docker.
- Kubernetes.

#### 4. Programación en C para fundamentos de sistemas

Incluye ejemplos opcionales en lenguaje C para reforzar conceptos de bajo nivel, compilación, memoria, modularización y fundamentos de programación de sistemas.

Temas principales:

- Compilación con CMake.
- Archivos fuente y cabeceras.
- Preprocesador.
- Memoria y estructuras básicas.
- Organización de programas en C.

### Estructura general

```text
.
├── Actividad0/                  # Recursos iniciales e infraestructura básica
├── Actividad2/                  # Cliente, servidor y Docker
├── Actividad4/                  # Sockets, servidores y variantes de MapReduce
├── Actividad6/                  # Servicios y programación asíncrona
├── Actividad8/                  # Modelos de paralelismo y memoria distribuida
├── Actividad9/                  # Arquitecturas paralelas y cache
├── Actividad10/                 # Multithreading
├── Actividad11/                 # Multiprocessing
├── Actividad12/                 # Algoritmos paralelos y rendimiento
├── Actividad13/                 # Sincronización y consistencia
├── Actividad14/                 # Modelos de programación distribuida
├── Actividad15/                 # Algoritmos distribuidos
├── Actividad16/                 # Sistemas de archivos distribuidos
├── Actividad17/                 # Bases de datos distribuidas
├── Actividad18/                 # Mensajería
├── Actividad19/                 # Microservicios y contenerización
├── Evaluacion*/                 # Evaluaciones y ejercicios
├── LenguajeC/                   # Material opcional de lenguaje C
├── Concurrencia.ipynb           # Notebook introductorio de concurrencia
├── Paralelismo.ipynb            # Notebook introductorio de paralelismo
├── BibliotecasC-paralelismo.ipynb
├── Caso-Refactorizacion.ipynb
└── Repaso.ipynb
```

#### Lenguajes y tecnologías utilizadas

| Tecnología | Uso principal |
|---|---|
| Python | Scripts, servidores, clientes, sockets, concurrencia, paralelismo y experimentos distribuidos. |
| Jupyter Notebook | Actividades guiadas, explicaciones, demostraciones y análisis interactivo. |
| C | Fundamentos de programación de sistemas y material complementario. |
| Docker | Ejecución aislada de servicios y ejemplos cliente-servidor. |
| Kubernetes | Manifiestos básicos para pods, servicios, endpoints y jobs. |
| YAML | Configuración de infraestructura y despliegue. |

#### Requisitos sugeridos

Para trabajar con el repositorio se recomienda tener instalado:

- Python 3.10 o superior.
- Jupyter Notebook o JupyterLab.
- Docker.
- Kubernetes local opcional, por ejemplo Minikube, Kind o Docker Desktop con Kubernetes.
- Compilador C, por ejemplo GCC o Clang.
- CMake para los ejemplos de `LenguajeC`.

