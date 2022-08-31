FROM openjdk:8-jre
WORKDIR /srv/minecraft
COPY . .
EXPOSE 25565
ARG MIN_RAM=1G
ARG MAX_RAM=6G
ENV min_ram $MIN_RAM
ENV max_ram $MAX_RAM
CMD java -Xms$min_ram -Xmx$max_ram -jar forge-1.7.10-10.13.4.1614-1.7.10-universal.jar nogui
