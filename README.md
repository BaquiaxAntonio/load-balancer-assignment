# Assignment 01 - Load Balancer con Nginx y Docker

## Descripción
Este proyecto implementa un balanceador de carga utilizando Nginx con el algoritmo Round Robin.
Se configuran dos servidores web simples que muestran:

- "Hola mundo desde server 1"
- "Hola mundo desde server 2"

El balanceador distribuye las solicitudes entre ambos servidores.

##Diagrama de la infraestructura
![Diagrama de infraestructura](Docs/diagram.png)

Estructura:
Cliente → Nginx (Load Balancer) → Server1  
                                  → Server2

## Cómo ejecutar la infraestructura
Desde la raíz del proyecto ejecutar:
```bash
docker compose up --build

