# Herramienta de consulta para api link2

uso:
```bash
# dar permisos de ejecucion
chmod +x cli getList getToken
#ejecutar el cli
./cli
```

el cli te mostrara la siguiente pantalla para obtener los parametros deseados

usuario_solicitante [practicanteIt] (obligatorio): /n
id_proyecto [omitir] (opcional):
id_zona [omitir] (opcional):
id_cliente [omitir] (opcional):
id_empresa [omitir] (opcional):
id_estatus_proyecto [omitir] (1-9 o lista ej 1,2,3, opcional):
nombre_largo [omitir] (busqueda parcial, opcional):
activo [omitir] (0|1, opcional):
obra_terminada [omitir] (0|1, opcional):
tipo_listado [omitir] (c|r|a, opcional):

alternativamete se puede invocar getList de la siguiente forma

```bash
# ./getList <param=key> ej:
./getList tipo_listado=r
```
