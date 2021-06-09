# Requisitos

Para poder usar este contenido de manera local necesitará tener acceso al comando `conda` y opcionalmente a `git`

## Instalando `conda`

El comando `conda` puede ser obtenido mendiante la instalación de Anaconda o miniconda. La descarga de dichas distribuciones la puede encontrar en sus páginas oficiales:

- [Descargar Anaconda](https://www.anaconda.com/products/individual)
- [Descargar Miniconda](https://docs.conda.io/en/latest/miniconda.html)

:::{note}
Ambas distribuciones proveen el comando `conda`, la diferencia entre Anaconda y miniconda radica en la cantidad de paquetes adicionales que traen consigo. Anaconda contiene varios paquetes útiles para comenzar con el análisis de datos; debido a ello, la descarga es más pesada que miniconda, el cual comprende una instalación minimalista
:::

## (Opcional) Instalando `git`

Si desea puede hacer uso del comando `git` para descargar una copia del contenido de este libro. En los sistemas operativos Unix `git` viene instalado por defecto, en caso de estar usando un sistema operativo distinto (Windows, MacOS) , o no contar con el comando, deberá instalar git desde su [página oficial](https://git-scm.com/downloads) y luego ejecutar Git Bash desde donde podrá hacer uso del comando `git`.

Para clonar el repositorio deberá usar el siguiente comando:

```bash
git clone git@github.com:intro-python-clima/intro-python-clima.git
```

Esto creara una carpeta con el mismo nombre del repositorio al cual podra acceder para iniciar su sesion de Jupyter.