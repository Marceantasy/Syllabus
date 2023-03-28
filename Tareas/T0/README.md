# Tarea 0: DCCeldas 💣🐢🏰

## Consideraciones generales :octocat:

 El programa es capaz de realizar todo lo solicitado en el enunciado, con la excepción de la regla 5, el programa encuentra una solución que satisfaga todas las otras reglas.
 Al escribir el nombre del archivo en el menú de inicio, debe escribirse sin la extensión .txt, ej: si el archivo es ```tablero_2x2.txt``` debe escribirse ```tablero_2x2```.
 La función ```solucionar_tablero()``` llama a la función ```solucionar_tablero_en_posición()``` para que haga la recursión y retorne el tablero solución.
 
### Cosas implementadas y no implementadas :white_check_mark: :x:

Explicación: mantén el emoji correspondiente, de manera honesta, para cada item. Si quieres, también puedes agregarlos a los títulos:
- ❌ si **NO** completaste lo pedido
- ✅ si completaste **correctamente** lo pedido
- 🟠 si el item está **incompleto** o tiene algunos errores
#### Menú de Inicio (5 pts) (7%)
##### ✅ Seleccionar Archivo
##### ✅ Validar Archivos
#### Menú de Acciones (11 pts) (15%) 
##### ✅ Opciones
##### ✅ Mostrar tablero 
##### ✅ Validar bombas y tortugas
##### ✅ Revisar solución
##### ✅ Solucionar tablero
##### ✅ Salir
#### Funciones (34 pts) (45%)
##### ✅ Cargar tablero
##### ✅ Guardar tablero
##### ✅ Valor bombas
##### ✅ Alcance bomba
##### ✅ Verificar tortugas
##### ✅ Solucionar tablero
#### General: (19 pts) (25%)
##### ✅ Manejo de Archivos
##### ✅ Menús
##### ✅ tablero.py
##### ✅ Módulos
##### ✅ PEP-8
#### Bonus: 6 décimas
##### ❌ Funciones atómicas
##### ❌ Regla 5

## Ejecución :computer:
El módulo principal de la tarea a ejecutar es  ```main.py```. No deben crearse archivos adicionales aparte de los tableros de prueba en la carpeta ```Archivos``` 


## Librerías :books:
### Librerías externas utilizadas
La lista de librerías externas que utilicé fue la siguiente:

1. ```os```: ```path.isfile()```

### Librerías propias
Por otro lado, los módulos que fueron creados fueron los siguientes:

1. ```functions.py```: Contiene a la función ```solucionar_tablero_en_posicion(x: int, y: int, tablero: list):``` la cual aplica la recursión utilizada para encontrar una solucion de ```solucionar_tablero()```


## Supuestos y consideraciones adicionales :thinking:
Los supuestos que realicé durante la tarea son los siguientes:

1. La carpeta archivos viene vacia para que los ayudantes agreguen los tableros de prueba que quieran utilizar
2. El programa acepta solucionar el mismo tablero (con mismo nombre de archivo) ya que si existe el archivo solución, se sobreescribe, en caso de no existe, se crea y luego se escribe
3. Si al momento de buscar una solución al tablero, esta solución no existe, el archivo solución no se crea/actualiza
4. En el caso que la opción introducida en el menú de Acciones sea invalida, se le pedirá al usuario ingresar nuevamente la opción


PD: El programa asume que los ayudantes rellenarán la carpeta ```Archivos``` con los tableros de prueba


-------

