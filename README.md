
# Vorgehen beim Projekt  

## Klonen des Repositories
  
      git clone SSH-Schlüssel

## Installation der notwendigen Pakete
      
      npm install

## Docker-Konfiguration und -Installation  
### Docker Installiation

[Docker Desktop](https://www.docker.com/products/docker-desktop/)   

### Docker Konfiguration

      dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart


      dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart



      wsl --set-default-version 2
## Starten der Applikation in einem Docker-Container  
Um die Applikation im Docker-Container zu Starten muss man nur einen Simplen befehl eingeben:


      docker compose up --build
Nun können sie im Browser unter diesem Link die Applikation begutachten:


      http://localhost:3000/
