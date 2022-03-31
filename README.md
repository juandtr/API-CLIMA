 
Proyecto creado para consumir el API del clima (https://openweathermap.org)
<img width="933" alt="clima" src="https://user-images.githubusercontent.com/75295437/131236578-a88badf9-f91f-48c9-84f3-f6f5f991086c.png">


### Pre-requisitos

```
Vue.JS
```
```
Vuetify
```
```
Webpack
```
```
Sass
```
#ejercicio 05

#cceder a los nodos del cluster
DB_CLUSTER_ID: el identificador del clúster en el que se ejecuta el script. Consulte Clusters API 2.0.
DB_CONTAINER_IP: la dirección IP privada del contenedor en el que se ejecuta Spark. El script init se ejecuta dentro de este contenedor. Consulte SparkNode.
DB_IS_DRIVER: si el script se ejecuta en un nodo de controlador.
DB_DRIVER_IP:  la dirección IP del nodo del controlador.
DB_INSTANCE_TYPE: el tipo de instancia de la máquina virtual host.
DB_CLUSTER_NAME:  el nombre del clúster en el que se ejecuta el script.
DB_PYTHON_VERSION: la versión de Python que se usa en el clúster.
DB_IS_JOB_CLUSTER: si el clúster se creó para ejecutar un trabajo. Consulte Creación de un trabajo.
SPARKPASSWORD: una ruta de acceso a un SPARKPASSWO
#tambien lo podemos hacer desde bash si deseamos acceder a un nodo podemos hacerlo de la siguiente manera utilizando el siguiente script
echo $DB_IS_DRIVER
if [[ $DB_IS_DRIVER = "TRUE" ]]; then
  <run this part only on driver>
else
  <run this part only on workers>
fi
<run this part on both driver and workers>
Css
```

### Instalación
```
npm install, 

npm install -g @vue/cli
```

```
npm run serve
```


## Construido con

* [VueJs](https://vuejs.org/) - El framework web usado Frontend JS
* [Vuetify](https://vuetifyjs.com/en/) - El framework web usado Style
* [Sass]() - Estilos

# social
* **linkedin** - (https://www.linkedin.com/in/juan-trujillo-7843161b1/)

## proyecto realizado por: juan david trujillo rodriguez


