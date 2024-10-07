# FinalProject-devops

## Descripción del proyecto
Este proyecto es una aplicación frontend construida con Node.js y Vite. La aplicación se despliega utilizando Docker y Nginx para servir los archivos estáticos.

## Requisitos previos para ejecutar el proyecto
- Node.js (versión 14 o superior)
- npm (versión 6 o superior)
- Docker (versión 20 o superior)

## Instrucciones para ejecutar el proyecto localmente

1. Clona el repositorio:
   ```sh
   git clone https://github.com/tu-usuario/FinalProject-devops.git
   cd FinalProject-devops
2. Instala las dependencias:
    ```bash
    npm install
3. Construye el proyecto:
    ```bash
    npm run build

4. Ejecuta el proyecto:
    ```bash
    npm start

## Instrucciones para ejecutar el proyecto usando Docker
1. Construye la imagen Docker:
    ```bash
    docker build -t tu-usuario/finalproject-devops:v1 .
2. Ejecuta el contenedor Docker:
    ```bash
    docker run -d -p 80:80 tu-usuario/finalproject-devops:v1