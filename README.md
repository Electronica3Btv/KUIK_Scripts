# KUIK_Scripts
Imagen KUIK 2.0

-Anydesk descargado pero no instalado
-Script de Puesta en marcha de anydesk
-Lanzadores de los scripts creados en Startup, solo falta activar el que se necesite.
-reinicio a las 4:05 AM
-DHCP activado


-Ultima version de los scripts de Github 12/06/2024

-Los symlinks de ttyTPV y ttyQR

-Archivo comprimido de los Drivers de la impresora


Por hacer:
	-Auto-Startup en la BIOS
	-(en caso de haber TPV) 60 segundos de BOOT en la BIOS
	-Elegir si es Intelio o Maletas en el Startup
	-(Si se quiere) Tunel
	-Cambiar el archivo del TPV nuestro por el del cliente




GIT GUIDE

Descargar

1ª vez:  	git clone https://github.com/Electronica3Btv/KUIK_Scripts

Siguientes: git stash -u
            git pull origin main

Subir

git add <file>
git commit -m 'mensaje'
git push