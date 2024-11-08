# My Docker IA Project

Este es un proyecto Docker que configura un entorno con una interfaz WebUI y un servicio Ollama para ejecutar modelos de lenguaje como Llama, GPT, entre otros.

## Requisitos

- **Docker**: Asegúrate de tener instalado Docker Engine o Docker Desktop en tu máquina.
- **Docker Compose**: Necesitarás Docker Compose para gestionar los servicios de manera sencilla.

## Instalación

1. **Clona el repositorio** en tu máquina:

   ```bash
   git clone 

2. **Navega a la carpeta del proyecto** en tu maquina

    ```bash
    cd Docker_IA

3. **Ejecuta los contenedores con Docker Compose:**

    ```bash 
    docker-compose up -d

4. **Acceso a la Interfaz Web**

    https://localhost:8080

## Crear un Modelo con Ollama

1. **Accede al contenedor de Ollama**
    ```bash
        docker exec -it ollama bash

2. **Ejecuta un modelo con Ollama**
    ```bash
        ollama run llama3.2


## Detener los Contenedores
    ```bash
    docker-compose down
