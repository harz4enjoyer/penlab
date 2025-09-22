Dies ist ein PENTEST Labor mit Metasploitable2 und Kali Linux

To Setup:

Docker Netzwerk Erstellen:

`docker create penlab_kali`

Docker Maschinen Starten mit docker Compose:

`docker compose up --no-cache --build -d`

Kali VM benutzen:

`podman exec -it kali bash`

anstatt ip adresse einfach den hostname für metasploid verwenden metasploitable2
