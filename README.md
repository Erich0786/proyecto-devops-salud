#Servicio Web de Reserva de Horas Médicas (Proyecto DevOps)

Plataforma web estática contenerizada con Nginx y Docker para garantizar entornos reproductibles y despliegues sin errores de configuración.

## Requisitos Previos
* Docker Desktop instalado y en ejecución
* Git instalado

## Ejecución Local con Docker Compose
1. Abrir la terminal en la raíz del proyecto.
2. Construir la imagen y levantar el contenedor en segundo plano:
```bash
docker compose up -d --build