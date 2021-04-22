# Titulo de la Solución: Proyecto Covid-ICESI
FALTA

## Tabla de Contenidos
* [Descripción de la solución](#descripción-de-la-solución)
* [Screenshots](#screenshots)
* [Requerimientos](#requerimientos)
* [Instalacion](#instalación)
* [Ejemplos de Codigo](#ejemplos-de-codigo)
* [Pruebas Automatizadas](#pruebas-automatizadas)
* [Autores](#autores)

## Descripción de la solución
Desarrollo de un modelo de asignación de pacientes, a las diferentes áreas (UCIs) disponibles en el departamento del Valle del Cauca. El modelo se ejecuta por medio de PuLP, un solver o modelador LP lineal para la optimización de restricciones.
### Screenshots
![screenshot](https://www.eclipsemediasolutions.com/sites/default/files/Audience-web-traffic-fluctuations1.jpg)
## Requerimientos
Lenguaje: Python 3.6
Manejador de dependencias: pip3
### Librerias Empleadas 
- pulp
- numpy
### Requerimientos Hardware
RAM: 512 Mb
Disco: 2 Gb
### Requerimientos Software
Sistema operativo: Linux, Linux alpine, ubuntu 16.04 o superior.
## Arquitectura de la solución
Para llenar
## Diagrama Entidad - Relacion 
No aplica
## Instalación
#### Guía de instalanción para el sistema operativo Ubuntu 16.04

1. Ejecutar los siguientes comandos para instalar python 3.6:
```
sudo add-apt-repository ppa:jonathonf/python-3.6
sudo apt-get update
sudo apt-get install python3.6
sudo update-alternatives --install /usr/bin/python3 python3 /usr/bin/python3.6 1
sudo update-alternatives --config python3
python3 --version
```

2. Ejecutar los siguientes comandos para instalar el manejador de paquetes pip3:
```
sudo apt update
sudo apt install python3-pip
pip3 --version
```

3. Ejecutar los siguientes comandos para instalar dependencias del proyecto:
```
cd <carpeta-del-proyecto>
pip3 install -r requirements.txt
```

4. Ejecutar el proyecto:
```
python3 main.py
```
## Configuracion
No aplica
## Ejemplos de Codigo
No aplica
## Errores conocidos
No aplica
## Pruebas Automatizadas
No aplica
## Imagenes
No aplica
## Autores

