# Comandos de ayuda en la terminal de Linux

## Índice

  - [1. Introducción](#1-introducción)
  - [2. Comando man](#2-comando-man)
  - [3. Comando --help](#3-comando-help)
  - [4. Comando info](#4-comando-info)
  - [5. Comparativa de comandos](#5-comparativa-de-comandos)
  - [6. Recursos adicionales](#6-recursos-adicionales)
---
  
## 1. Introducción

Esta es una **breve guía** de 3 diferentes comandos para obtener *ayuda en la terminal* a la hora de buscar soluciones cuando nos quedamos atascados y no sabemos cómo escribir un comando, qué opciones tiene... 
Es una guía muy sencilla y breve, pero como dice el refrán popular:

> <small> "Un grano no hace granero, pero ayuda al compañero." --- Refrán popular</small>

Una cosa que habría que hacer siempre antes de manejar cualquier *distribución o distro* de Linux, sería actualizar el sistema, y para eso, la secuencia ordenada de comandos a escribir sería:
```
sudo apt update
sudo apt upgrade
sudo apt autoremove
```
Ingresaríamos la contraseña y el sistema se actualizaría y borraría aquellos paquetes innecesarios.

El único propósito de usar `man mkdir` , `mkdir --help` e `info mkdir` es para poder comparar las salidas que ofrecen por pantalla.

---

## 2. Comando man

Este comando sirve para obtener información sobre un comando, abriendo la página del manual. Para salir del manual hay que pulsar la tecla **Q**.
A continuación se ponen 3 ejemplos de este comando:

1. **man mkdir** ![man mkdir](Imágenes/man%20mkdir.png)
2. **man ls** 
3. **man cd** 

 
---

## 3. Comando help

Este comando también muestra ayuda, pero es una ayuda más concisa o breve. Aporta algunas instrucciones breves sobre el comando que queremos consultar.

1. **mkdir --help** ![mkdir --help](Imágenes/mkdir%20help.png)
2. **ls --help** 
3. **cd --help** 

---



## 4. Comando info

Las páginas que proporciona el comando info son más detalladas que las páginas del manual, y por supuesto que las de help. Aportan mucha información.
La sintaxis de este comando sería:
1. **info mkdir** ![info mkdir](Imágenes/info%20mkdir.png)
2. **info ls** 
3. **info cd** 



---
## 5. Comparativa de comandos

A continuación hay una simple comparativa de los comandos indicados en esta guía:

| **Comando** | **Sintaxis** | **Información aportada** |
|:-:|:-|:-:|
| man| man mkdir | media |
|help|mkdir --help|baja|
|info|info mkdir|alta|


---

## 6. Recursos Adicionales

*  [Foro de linux.org](https://www.linux.org/forums/#linux-tutorials.122)
*  [Wikipedia: Linux](https://es.wikipedia.org/wiki/GNU/Linux)
*  [Página web de The Linux Foundation](https://www.linuxfoundation.org/)
*  [Linux explicado en menos de 100 segundos](https://www.youtube.com/watch?v=NIQZOviElSU)


---
### Autor: José Ramón
