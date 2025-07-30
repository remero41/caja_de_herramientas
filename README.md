

<div align="center">

# Caja-de-Herramientas

<img src="https://cloud.githubusercontent.com/assets/2059754/24601246/753a7f36-1858-11e7-9d6b-7a0e64fb27f7.png" height="250px" width="250px">

##### Esta es una puerta para la instalación de Katty y poder instalar cualquier cosa necesaria en nodos y entorno local
</div>



## Librerias necesarias
```
sudo apt install curl
sudo apt install git
```


## General
```
[ -e ~/.ssh/id_rsagithub ] && rm ~/.ssh/id_rsagithub
curl -o inicio.sh https://raw.githubusercontent.com/remero41/caja_de_herramientas/main/inicio.sh?v=1
bash ~/inicio.sh && rm -f ~/inicio.sh
```

