# Proyecto SMPIA

Este repositorio incluye tres submódulos y los orquesta utilizando `docker-compose`.

## Contenido

-  **SMPIA_MAIN_API**: Strapi API.
-  **SMPIA_ML_API**: FastAPI API que contiene un modelo IA.
-  **SMPIA_WEB_APP**: Frontend en React.

## Requisitos

-  Docker
-  Docker Compose

## Instalación

1. Clona el repositorio junto con los submódulos:

   ```bash
   git clone --recurse-submodules https://github.com/tu-usuario/SMPIA.git
   ```

2. Navega al directorio del proyecto:

   ```bash
   cd SMPIA
   ```

## Uso

1. Construye y levanta los contenedores con `docker-compose`:

   ```bash
   docker-compose up --build
   ```

2. Accede a los servicios proporcionados por los submódulos a través de los puertos especificados en el archivo `docker-compose.yml`.

## Contribución

1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios y haz commit (`git commit -am 'Añadir nueva funcionalidad'`).
4. Sube tus cambios (`git push origin feature/nueva-funcionalidad`).
5. Abre un Pull Request.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.

## Contacto

Para cualquier consulta, puedes contactar a [tu-email@dominio.com](mailto:tu-email@dominio.com).
