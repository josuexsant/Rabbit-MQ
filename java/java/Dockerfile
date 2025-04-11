FROM eclipse-temurin:17-jdk

WORKDIR /app

COPY . /app

# Compilar archivos Java
RUN javac -cp ".:lib/*" Send.java Recv.java

# Ejecutar ambos programas (primero el receptor)
CMD java -cp ".:lib/*" Recv
