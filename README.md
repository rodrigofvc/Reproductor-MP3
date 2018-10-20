# Reproductor-MP3

Reproductor de MP3 programado en Go

Modelado y Programacion

Go version 1.10.1

# Autor

Velázquez Cruz Rodrigo Fernando

Numero de cuenta UNAM: 315254565

## Ejecucion:

Los paquetes van en el directorio `$GOPATH`
```bash
$ go get github.com/RodrigoVelazquez99/Reproductor-MP3
```
!!!IMPORTANTE¡¡¡ se debe crear una carte en src/Base para que la base de datos de guarde.

```bash
$ cd src
$ mkdir Base
$ cd Reproductor/
$ go run Reproductor.go
```

## Busquedas

Para las busquedas, basta con poner "T:" antes del titulo de la cancion, "P:" antes del interprete y "A:" antes del album, separadas por coma.
Por ejemplo; 
  `T:SongTest, P:PerformerTest, A:AlbumTest`

### Bibliotecas

```bash
$ go get -u github.com/bogem/id3v2
```
```bash
$ go get github.com/gotk3/gotk3/gtk
```
```bash
$ go get github.com/mattn/go-sqlite3
```

### Dependecias

* libgtk-3-dev
* libglib2.0-dev
* libcairo2-dev
* GTK+ 3.20
```bash
$ sudo apt-get install libgtk-3-dev
```
```bash
$ sudo apt-get install libcairo2-dev
```
```bash
$ sudo apt-get install libglib2.0-dev
```
```bash
$ sudo apt-get install build-essential
```
### Errores Conocidos

Faltan pruebas unitarias.

Al abrir la ventana de editar etiquetas mas de una vez ya no permite la entrada de texto.

