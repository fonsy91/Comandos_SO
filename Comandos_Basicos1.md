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


