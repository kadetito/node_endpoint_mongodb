# node_endpoint_mongodb


instalar mediante 

```
npm install 
```
para compilar node_modules

ejecutar posteriormente con:

```
tsc
npm start
```

o instalar nodemon y posteriormente ejecutar en dosterminales diferentes (recomendable):

```
tsc -w
nodemon dist
```
### IMPORTANTE:

En el código se llama a un perfil en Atlas Mongo DB donde está montada una base de datos. sustituir esa llamada por localhost en local.
Recordar levantar la bbdd mongodb a la que queramos consultar.
