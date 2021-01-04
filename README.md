# CMD
Codigos varios de CMD

#### Para detectar las claves de las Wifi

netsh wlan show profile

netsh wlan export profile folder=C:\ key=clear


#### Navegar en archivos.
Encontrar un archivo:
C:\>where XXXXX

#### PATH
C:\> path => Entrega el path de "enviroment variable"
C:\> echo %PATH% => Entrega el path de "enviroment variable"
C:\> echo %PATH:;=&echo.%

#### Add To Windows PATH
C:\> path => 
netsh wlan show networks mode=bssid
netsh wlan show profile => muestra los perfiles wifi guardados en nuestra PC
nslookup www.facebook.com => muestra la ip de la pagnia web
Tree => muestra el arbol de archivos
apretar F7 = muestra el historial de comandos
netsh wlan show drivers => informacion acerca del adaptador de red
net view => para ver quien esta conectado
shutdown -i => apagado remoto de equipos
shutdown -a
driverquery => listado de controladores instalados
driverquery > respaldo_driver.txt => en txt respaldo de los driver utilizados
driverquery /v > respaldo_driver2.txt => en txt respaldo de los driver utilizados
driverquery /si > respaldo_driver3.txt  => en txt respaldo de los driver firmados
driverquery /si
set path > path.txt
echo %PATH% > C:\path-backup.txt =>Save the contents of the Windows PATH environment variable to C:\path-backup.txt file:
#### Comandos PIP
pip freeze

pip list
