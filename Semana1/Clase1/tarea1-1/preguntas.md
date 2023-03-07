# Ejercicio 1 ( 2 preguntas extra)

## 🍎 Buscar la diferencia entre "Terminal Application" y "Terminal Emulator"

> **ChatGPT:**
>
> La principal diferencia entre una "Terminal Application" y un "Terminal Emulator" radica en su función y su contexto de uso.
>
> Una Terminal Application es un programa diseñado para proporcionar una interfaz de línea de comandos (CLI) en un sistema operativo. Estas aplicaciones pueden ejecutar comandos y scripts en el sistema, acceder a archivos y directorios, configurar el sistema, y mucho más. Ejemplos de Terminal Applications incluyen la Terminal de macOS, el Símbolo del sistema de Windows, y la Terminal de Linux.
>
> Por otro lado, un Terminal Emulator es un programa que emula una terminal en un entorno gráfico como el de una computadora personal. Esto permite a los usuarios acceder a la línea de comandos en un sistema remoto a través de una red, como SSH (Secure Shell) o Telnet. En este caso, el Terminal Emulator actúa como una ventana que muestra la salida de la terminal remota. Ejemplos de Terminal Emulators incluyen PuTTY, iTerm2 y la Terminal de GNOME.
>
> En resumen, una Terminal Application se utiliza para proporcionar una interfaz de línea de comandos en un sistema local, mientras que un Terminal Emulator se utiliza para acceder a la línea de comandos en un sistema remoto a través de una red.

**Yo Humano:**

Primero comence analizando con que estaba trabajando , en este caso con Terminal
de GNOME que curiosamente ademas de ser una **Terminal Aplication** también es un
**Terminal Emulator** !!.

Como una aplicación de terminal, la terminal de GNOME proporciona una interfaz de
línea de comandos (CLI) para interactuar con el sistema operativo a través de
comandos y scripts

Y Como un emulador de terminal La Terminal GNOME proporciona una ventana que
emula la funcionalidad de un terminal físico en el entorno gráfico GNOME

Basicamente la diferencia radica en que un terminal aplication no emula un terminal fisico
y un terminal emulator si emula un terminal fisico , luego ambos pueden interactuar
como el SO a trávez de lineas de comandos .

Si no eres un usario casual de la linea de comandos es recomendable usar una terminal
aplication
Si ya eres un usuaro avanzado que trabala la linea de comandos frecuentemente con
necesitaras ejecutar comando complejos o trabajar con grandes cantidades de datos
y tambien terminal Emulator como Alcritty tienen mas funcionalidad que una terminal aplication

##🍎 ¿Por qué mv (mover) se usa para renombrar archivos o carpetas?

> **ChatGPT:**
> La razón por la que se usa el comando "mv" (mover) en lugar de un comando específico para renombrar archivos o carpetas es porque en Unix y sistemas operativos similares, la idea de "mover" un archivo o carpeta también implica cambiar su nombre o ubicación.
>
> Cuando se utiliza el comando "mv" para mover un archivo o carpeta, se le proporciona la ruta de origen y la ruta de destino. Si la ruta de destino es la misma que la ruta de origen, entonces se está renombrando el archivo o carpeta. En otras palabras, "mover" un archivo o carpeta a la misma ubicación con un nombre diferente es lo mismo que "renombrar" ese archivo o carpeta.
>
> Por ejemplo, si tienes un archivo llamado "archivo1.txt" en la carpeta "/home/usuario/documentos" y quieres renombrarlo como "archivo2.txt", puedes usar el comando "mv" de la siguiente manera:
>
> ```bash
> mv /home/usuario/documentos/archivo1.txt /home/usuario/documentos/archivo2.txt
> ```
>
> Al mover el archivo a la misma carpeta pero con un nombre diferente, estás renombrando el archivo.
>
> En resumen, el comando "mv" se utiliza para mover archivos o carpetas en Unix y sistemas operativos similares, y también se utiliza para cambiar su nombre o ubicación. Por lo tanto, es comúnmente utilizado para renombrar archivos o carpetas.
> <>

<h2>


<h2 align="center" ><b>Commands in linux terminal that learned</b>
</h2>


|COMMAND |CONCEPT|
|---|---|
|```mkdir```| Crea una nueva carpeta dado un nombre para esa carpeta.|
|```cat```|Imprime el contenido de un archivo dada su ruta.|
|```mv```|Nos permite mover un archivo o carpeta dada una ruta inicial y una ruta final. También nos permite cambiar el nombre de un archivo o carpeta.|
|```pwd```| Nos nuestra la ruta absoluta del directorio actual, así podemos saberen dónde estamos ubicados.|
|```ls```|Lista los archivos de la carpeta actual, o de la ruta dada.|



