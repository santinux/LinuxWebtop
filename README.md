# LinuxWebtop
Una configuración básica para levantar un sistema operativo con interfaz gráfica dockerizado en un navegador web.

---
# Configuraciones previas
## Descargar Docker
La guía oficial para instalación
https://docs.docker.com/desktop/setup/install/linux/

También puede buscar docker-desktop en su gestor de paquetes GUI
(Pamac/Synaptic/KDE Discover) para mayor facilidad.

## Iniciar el servicio de Docker
```bash
sudo systemctl start docker
```

## Para que se inicie automáticamente al arrancar
```bash
sudo systemctl enable docker
```

## Levantar el contenedor
```bash
sudo docker compose up -d
```

Una vez descargada la imagen y activo el servicio, podemos abrir el
Webtop desde un navegador en http://localhost:3000/ o http://127.0.0.1:3000/
que es lo mismo.

