# Sistema de Chat cliente-servidor

Este proyecto consiste en la implementación de un sistema de chat basado en arquitectura cliente-servidor, desarrollado como trabajo práctico para la materia **Algoritmos y Programación [TA130]** de la carrera de Ingeniería Electrónica.

El objetivo fue diseñar y programar completamente en lenguaje C, tanto un **cliente** como un **servidor** capaces de comunicarse entre sí mediante sockets. El sistema permite la conexión de múltiples clientes, la creación de canales de chat y el intercambio de mensajes entre los usuarios conectados.

---

## Características principales

- Comunicación mediante sockets 
- Conexión simultánea de múltiples clientes
- Gestión de canales (creación, ingreso, salida, modificación)
- Modularización del código fuente
- Uso interactivo mediante la terminal
- Posibilidad de utilizar `telnet` como cliente alternativo

---

## Requisitos

- Sistema operativo: Linux o compatible 
- Compilador: `gcc`
- Herramienta de construcción: `make`

---

## Compilación y ejecución

### Compilar y ejecutar el **cliente**
cd cliente
make
./cliente <IP_SERVIDOR> <PUERTO>

### Compilar y ejecutar el **servidor**
cd servidor
make
./servidor <PUERTO>

### Alternativa para probar el servidor con telnet

telnet <IP_SERVIDOR> <PUERTO>


### Documentación
Los enunciados originales de ambos trabajos prácticos se encuentran en la carpeta /docs para facilitar la comprensión del contexto y los requerimientos de cada componente.

## Autor

- **Mateo Acosta** – [matacosta@fi.uba.ar](mailto:matacosta@fi.uba.ar)  
  Ingeniería Electrónica | Facultad de Ingeniería - Universidad de Buenos Aires  
  

---
