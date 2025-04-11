# Usa una imagen de Python
FROM python:3.10-slim

# Instala dependencias
RUN pip install pika

# Copia los archivos de tu app al contenedor
WORKDIR /app
COPY . .

# Comando por defecto (puedes sobreescribirlo con docker-compose)
CMD ["python", "send.py"]
