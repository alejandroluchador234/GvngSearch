# ***GvngSearch: V1.0***
<p align="center">
  <img width="200" height="200" src="https://i.postimg.cc/Pr2sJ29t/Blue-and-Black-Hexa-Games-Logo.png" alt="Logo de GS">
</p>
<hr>

### Es una Dox-Tool enfocada en dos niveles:
 * <b>Dox Personal</b>: Orientado al doxeo de personal o usuario de internet.
 * <b>Dox Web</b>: Orientado al doxeo general de una página o servidor web.

![BETA][version]
![Tested][tested]

![Previsualización][preview]

<hr>

# Pre-Requisitos:

Tanto para usuarios <b>Linux</b> como <b>Termux</b> los requisitos son los mismos: disponer de las herramientas en el sistema necesarias.

* [x] Mantener las herramientas y sistema actualizadxs.
* [x] En Caso de Termux tener pre-instalado Git y dnsutils.
* [x] Tener pre-instalado curl.

<hr>

# Instalación:

![Instalación][install]


[GvngSearch Linux:][GSLinux] O [GvngSearch Termux][GSTermux]

<br>


* _En la carpeta donde queremos clonar el git:_

```sh
  git clone https://github.com/ByDog3r/GvngSearch
```

* _Entramos a la carpeta que se nos ha creado:_
```sh
  cd GvngSearch
```
* _Borramos los datos imnecesarios desde la terminal_

```sh
  rm README.md && rm -r -f .git/
```

* _Damos permisos de ejecución:_
```sh
   chmod +x *
```

* _Finalmente ejecutamos el script:_

<b>_Linux:_</b>
```sh
   ./gvngs.sh
```

<b>_Termux:_</b>
```sh
    bash Tgvngs.sh
```
<hr>

# Disfruta: 


![Resultado][portada]

<!-- MarkDown Links & Images -->
[version]: https://img.shields.io/badge/Version%3A-BETA%3A%20V.1.0-orange "Versión del script"
[tested]: https://img.shields.io/badge/Probado%3A-Termux%20%7C%20Kali%20Linux%20%7C%20Parrot-informational
[preview]: https://user-images.githubusercontent.com/37609857/83977438-c1af5500-a8bd-11ea-9cd2-4fab90dae874.png "Observa una previsualización"
[install]: https://user-images.githubusercontent.com/37609857/83977451-d5f35200-a8bd-11ea-9334-b2ba25a46097.png "Mira el proceso de instalación."
[GSLinux]: https://github.com/ByDog3r/GvngSearch/blob/master/gvngs.sh
[GSTermux]: https://github.com/ByDog3r/GvngSearch/blob/master/Tgvngs.sh
[portada]: https://user-images.githubusercontent.com/37609857/83976991-e5bd6700-a8ba-11ea-9236-19cfc1db79a4.jpg "Resultado Final"
