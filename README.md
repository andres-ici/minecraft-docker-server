# ⛏️ Minecraft Server (Docker)

Este repositorio contiene la configuración necesaria para levantar un servidor de Minecraft de manera rápida y automatizada, utilizando la imagen [itzg/docker-minecraft-server](https://github.com/itzg/docker-minecraft-server).

## 📋 Requisitos Previos

Para ejecutar este servidor, necesitas tener instalado:
- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## 🚀 Inicio Rápido

1. Es obligatorio aceptar el EULA de Minecraft para que el servidor inicie. Asegúrate de que la variable de entorno `EULA=TRUE` esté configurada en tu archivo Compose.
2. Inicia el servidor en segundo plano ejecutando:

   ```bash
   docker compose up -d

3. Check de status del servidor

   ```bash
   docker compose ps
   ```

4. Enable interactive console

   ```bash
   docker attach <container_name>
   ```
   
4. Para apagar el servidor
   ```bash
   docker compose stop
   ```
