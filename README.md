# SPARK 101 

# 1. Docker + jupyter/pyspark-notebook
 - 1: Insalar docker
 - 2: Ejecutar "docker pull jupyter/pyspark-notebook"
 - 3: Seguir las instrucciones:

   - 1. Ejecutar el contenedor:
        ~~~
        docker run -it --rm -p 8888:8888 jupyter/pyspark-notebook
        ~~~
    - 2. Conectar con jupyter notebook: 
    http://127.0.0.1:8888/?token=0727b6912260e71c72aab2910b82bd103a0debe6905cbf87

# 2. Descargar los datos.
Vamos a usar un dataset de https://openlibrary.org/  enorme base de datos de libros
Puedes descargar de aqui:  https://openlibrary.org/developers/dumps
Descargar versio reducida: 
~~~
curl https://s3-eu-west-1.amazonaws.com/csparkdata/ol_cdump.json --output ol_cdump.json
~~~




# Recursos

https://medium.com/@suci/running-pyspark-on-jupyter-notebook-with-docker-602b18ac4494