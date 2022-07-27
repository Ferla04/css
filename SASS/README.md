# Sass

## Instalación

- Primero se debe tener Node instalado e inicializado `npm init -y`.
- Instalar sass
  ```
    npm install sass --save-dev
    npm install -g sass
  ```

## Compilación

- Comando para que compile todos los archivos scss que estan en la carpeta sass y los ponga en una carpeta css
  ```
    sass --watch path_archivos_sass:path_donde_se_dejan_archivos_css
  ```
Ejemplo:
  ```
    sass --watch sass:css
  ```
