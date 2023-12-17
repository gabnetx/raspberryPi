# raspberryPi
Pasos para configuracion RaspBerry Pi B+ 1.2

## Configuracion inicial para RASP
- Le instalo la imagen de 2018-10-09-raspbian-stretch-lite en una memory card de 32GB (De preferencia con buena tasa de I/O, buscar alguna marca ScanDisk Ultra o extreme)
- Loguearse, `sudo raspi-config`
  - pi/raspbian
- Editar, debido a que la edicion *stretch-lite* ya es software legado po rlo que el repositorio se movio de ubicacion: `sudo vi /etc/apt/sources.list` luego agregar la linea `deb http://legacy.raspbian.org/raspbian/ stretch main contrib non-free rpi`
- Armarse de paciencia para hacer actualizaciones
  - `sudo raspi-config`
  - `sudo apt-get update`
  - 
