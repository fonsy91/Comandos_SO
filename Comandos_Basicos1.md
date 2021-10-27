# Comandos Basico - Alfonso Muñoz
- __cat___: concatena y muestra un archivo

```bash
	$ cat <nombre del archivo>
```

- __chmod__: cambia los permisos de un archivo. Existen los permisos de lectura (r), de escritura (w) y de ejecucion (x). Se puede agregar o quitar permisos con el  signo + o -.

```bash
	$chmod <permisos> <archivo>
	$ chmod  +w archivo
	$chmod -rwx archivo
```

-__chown__: cambia el dueño de un archivo.
-__cp__:  copia archivos. En el ejemplo esta copiando fichero1 en fichero2

```bash
	$ cp <fichero1> <fichero2>
```

-__diff__: Encuentra diferencias entre archvios, la opcion -r es para que se 
comparen recursivaemnte, es decir que se comparen todos los subdirectorios 
que estan dentro del directorio analizado, y -q para que solo salgan en pantalla 
los ficheros que difieren de un directorio a otro.

```bash
	$ diff  -r -q <directorio1> <directorio2>
```

-__du__:  Muestra el tamaño del archivo o del directorio donde nos encontremos

```bash
	$ du  <directorio/archivo>
```

-__find__:  Encuentra archivos en el directorio donde nos encontremos, se
puede buscar por nombre de archivo (-name), tipo de archivo (-type),
tamaño (-size) etc...

```bash
	$ find . -name  <nombre_diectorio/archivo>
```

-__grep__:  Busca patrones en un archivo, algunas opciones son:

-__i__: la búsqueda no distinguirá entre mayúsculas y minúsculas. Es decir, si quieres buscar la palabra «auto» será lo mismo que «AUTO»
-__c__: solo mostrará el número de líneas que coinciden con el patrón buscado
-__r__: habilita la búsqueda recursiva en el directorio actual
-__n__: busca líneas y precede cada línea coincidente con un número de línea.
-__v__: con esta opción, se nos muestran las líneas que no coinciden con el patrón que hemos buscado

```bash
	$ grep [opciones] patter [archivo]
	$grep -i <palabra a buscar> [archivo]
```



