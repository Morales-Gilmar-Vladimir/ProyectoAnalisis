# ProyectoAnalisis 
-Proceso Primera parte
1. Para este proyecto deberemos obtener diferentes datos, los mismo tendran diferentes formatos, tales como
CSV, JSON, XLSX y sqlLite, los cuales contiene tematicas como peliculas, restaurantes, deportes y hobies:

![image](https://github.com/Morales-Gilmar-Vladimir/ProyectoAnalisis/assets/117743690/d96e9102-6825-4f23-9a1a-89225794232f)

3. Para este proyecto utilizaremos las siguientes bases de datos, las mismas son estructuradas(SqlLite, SqlServer) y  no estrucuturadas
(RavenDB,CouchDB,MongoDB):

![image](https://github.com/Morales-Gilmar-Vladimir/ProyectoAnalisis/assets/117743690/dee0ef10-fa20-4094-9128-ee9759701ea7)

4. Obteniendo dichos datasets, ahora los subiremos a SqlLite, para lo cual varios archivos tendran que cambiar sus formatos,
en este caso se convertira los JSON Y XLSX en CSV.

![image](https://github.com/Morales-Gilmar-Vladimir/ProyectoAnalisis/assets/117743690/b5bcef0e-2f98-4ef9-bf4c-d6ef9d286db1)
![image](https://github.com/Morales-Gilmar-Vladimir/ProyectoAnalisis/assets/112398547/f688c1f5-ce5a-41c7-a1ea-1f9c5d4e95a6)

Tal como se muestra aqui, con esto podremos visualizar todos los datasets en SqlLite:

![image](https://github.com/Morales-Gilmar-Vladimir/ProyectoAnalisis/assets/117743690/41764ccb-70c7-4d3b-a29c-4cf1b52fd444)
![image](https://github.com/Morales-Gilmar-Vladimir/ProyectoAnalisis/assets/117743690/8adcc683-d3ff-4b14-bb63-f2a0eca3649e)
![image](https://github.com/Morales-Gilmar-Vladimir/ProyectoAnalisis/assets/117743690/fd865ee4-5641-42df-a45d-71eafedc2236)
![image](https://github.com/Morales-Gilmar-Vladimir/ProyectoAnalisis/assets/117743690/af7be4c3-4c52-415e-ab02-8435a11f31aa) 
![image](https://github.com/Morales-Gilmar-Vladimir/ProyectoAnalisis/assets/117743690/203964d0-6d06-476c-b2e8-2821f626b060)
![image](https://github.com/Morales-Gilmar-Vladimir/ProyectoAnalisis/assets/117743690/4a68adfb-bdf1-4ce4-9178-96cec3563f42)
![image](https://github.com/Morales-Gilmar-Vladimir/ProyectoAnalisis/assets/117743690/eb3452fd-8ffa-41b4-9666-39eba50e52c6)
![image](https://github.com/Morales-Gilmar-Vladimir/ProyectoAnalisis/assets/117743690/acd9e320-ddca-473e-9ab6-c20bdfd157b0)
![image](https://github.com/Morales-Gilmar-Vladimir/ProyectoAnalisis/assets/117743690/47fe6ee0-a8b3-43e2-8550-33823bbbed3f)

5. En este punto deberemos importar los archivos de SqlLite en dos tandas, unos CSV y otros Json, los archivos CSV seran exportados 
a MongoDB y los Json a CouchDB

![image](https://github.com/Morales-Gilmar-Vladimir/ProyectoAnalisis/assets/112398547/089265b3-4efb-4ae5-8a41-a409b6f9462f) 
![image](https://github.com/Morales-Gilmar-Vladimir/ProyectoAnalisis/assets/112398547/d9b59fce-ab75-420b-9c0f-18afa4442ef6)

6. En el caso de MongoDB la aplicación nos permitira exportar de forma facil dichos datasets:
   
![image](https://github.com/Morales-Gilmar-Vladimir/ProyectoAnalisis/assets/112398547/489c9454-f7c3-42cd-8143-8945b68e5085)
![image](https://github.com/Morales-Gilmar-Vladimir/ProyectoAnalisis/assets/112398547/9974009a-d506-4746-9c0e-6c65a075d4fe)
![image](https://github.com/Morales-Gilmar-Vladimir/ProyectoAnalisis/assets/112398547/ef78ab63-c91e-4e0e-8ee7-5c896af7c909)

7. Para subir datasets a Couchdb, sera necesario utilizar lenguaje python, donde nos conectaremmos a dicha base de datos, cargaremos 
dichos archivos

![image](https://github.com/Morales-Gilmar-Vladimir/ProyectoAnalisis/assets/112398547/69aaab24-83a6-4f5a-831e-82092e9876b1)
![image](https://github.com/Morales-Gilmar-Vladimir/ProyectoAnalisis/assets/112398547/5ee26e9a-d1de-4b30-8366-a6af6a6d092c)
![image](https://github.com/Morales-Gilmar-Vladimir/ProyectoAnalisis/assets/112398547/0a3dca4a-774e-49bc-b046-4d7d414e0e6c)
![imagen](https://github.com/Morales-Gilmar-Vladimir/ProyectoAnalisis/assets/117743844/e9e0c1e4-9532-4235-b8c6-fc7952e531e1)

8. Ahora deberemos exportar de cada base de datos (MongoDB y CouchDB) en un archivo CSV, de esta manera podremos exportar dichos
archivos a la siguiente base de datos RavenDB, tal como se muestra a continuación:

![image](https://github.com/Morales-Gilmar-Vladimir/ProyectoAnalisis/assets/112398547/14c54252-c8a5-4b43-8fad-eb0027e7d84a)
![image](https://github.com/Morales-Gilmar-Vladimir/ProyectoAnalisis/assets/112398547/8caf58d1-f162-42de-b63f-c0fb08f0a35a)
![image](https://github.com/Morales-Gilmar-Vladimir/ProyectoAnalisis/assets/112398547/c1309f78-0992-45a4-8fce-0936c6fb5e0b)

9.Para poder extraer datos desde RavenDb, dicha base nos permite exportar los archivos como tipo json, los mismos seran convertidos, 
por medio de app web a tipo csv, dicho formato es aceptado para la ultima base de datos SQLserver, donde subiremos todos los archivos
de RavenDB, de la siguiente manera:

![image](https://github.com/Morales-Gilmar-Vladimir/ProyectoAnalisis/assets/112398547/c283c74c-4898-4c0b-b672-2b9ca310b2ac)
![image](https://github.com/Morales-Gilmar-Vladimir/ProyectoAnalisis/assets/112398547/a20c452a-285b-4b89-ac0f-a460cd2cc37f)
![image](https://github.com/Morales-Gilmar-Vladimir/ProyectoAnalisis/assets/112398547/549ac445-f6ad-4002-9739-1a059bf20bb2)
![image](https://github.com/Morales-Gilmar-Vladimir/ProyectoAnalisis/assets/112398547/f1c7991a-5230-47dc-bb15-ae063c0472ba)

Por último, aqui se vvisualiza la arquitectura de este proyecto, siendo la primera, una versión simplificada donde podemos visualizar
en que orden se almacenaron los datos en cada base de datos, mientras que la segunda visualizamos la misma arquitectura, pero añadiendo
los diferentes datos que posee cada base y sus diferentes conversiones.

![image](https://github.com/Morales-Gilmar-Vladimir/ProyectoAnalisis/assets/112398547/d087802c-024c-45b9-b0a1-dc006f8236a6)
![image](https://github.com/Morales-Gilmar-Vladimir/ProyectoAnalisis/assets/112398547/c252179a-6e10-4672-a69b-8e976df64492)

































    













