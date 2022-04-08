# Base de datos NoSQL basada en Key-Value

## Realizado por Alejandro Rodriguez Muñoz, Camila Mejia y Daniel Solano 

### Materia Topicos de telematica de la universidad EAFIT 2022-1

### Instalacción
***
```
$ git clone https://github.com/AlejoRm01/NoSQL-KeyValue
$ cd ../path/to/the/file/NoSQL-KeyValue
```
### Ejecución
***
#### Primero nodos
Se puede ejecutar de la siguiente manera: 
```
$ py nodo.py 5000
$ py nodo.py 5001
$ py nodo.py 5002
$ py nodo.py 5003
```
#### Segundo balanceardor de carga
Se puede ejecutar de la siguiente manera: 
```
$ py balanceador_de_carga.py -a 5000 5001 5002 5003
```

#### Tercero cliente
El cliente puede crear, leer, actualizar y eliminar.

#### Crear
```
c.crear('01', 'Juan Carlos es el mejor profesor') 
```
#### Leer 
```
c.leer('01')
``` 
#### Actualizar
```
#c.actualizar('01', 'Telematica')
```
#### Eliminar
```
#c.eliminar('01')
```
Solo es cambiar la llave por una de su elección, y el valor por uno de su elección.
#### Ejecutar de la siguiente forma:
```
$ py cliente.py 
```
