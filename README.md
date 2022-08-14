# Curso de aprendizaje profundo 2023-1, PCIC-UNAM
Este repositorio contiene las diapositivas, libretas y tareas del curso de aprendizaje profundo del [Posgrado en Ciencia e Ingeniería de la Computación](http://www.mcc.unam.mx/) de la [UNAM](https://www.unam.mx/).


## Temario
1. Redes densas
2. Redes convolucionales
3. Redes recurrentes
4. Redes basadas atención
5. Estrategias de entrenamiento
6. Redes generativas
7. Temas selectos

## Clonar rama
Este repositorio contiene el material de cursos anteriores y puede ser algo pesado clonarlo completamente. Para clonar únicamente la rama del curso 2023-1, debes hacerlo con el siguiente comando:

```
git clone --branch 2023-1 --single-branch https://github.com/gibranfp/CursoAprendizajeProfundo.git
```

## Ambiente de programación
Para ejecutar los ejercicios y las libretas de este repositorio se tienen dos opciones:

* Servicios de libretas en la nube
 * [Google Colab](https://colab.research.google.com/)
 * [Kaggle](https://www.kaggle.com/)
 * [Paperspace](https://www.paperspace.com/)
* Ambiente local

### Ambiente local
Para instalar el ambiente en nuestra computadora primero debemos instalar Anaconda siguiendo las [instrucciones](https://docs.anaconda.com/anaconda/install/) oficiales. Después, desde una terminal creamos el ambiente con el archivo de dependencias:

```
conda env create --file environment.yml
```

Enseguida, activamos el ambiente:

```
conda activate cap
```

Posteriormente, para comenzar a trabajar con las libretas ejecutamos:

```
jupyter notebook
```

Este comando abrirá una pestaña o ventana en tu navegador web, como se muestra en la siguiente captura de pantalla:

![](figs/jupyter_notebook.png)

Aquí puedes crear una nueva libreta seleccionando el botón `New` y posteriormente `Python 3`. También puedes cargar una existente seleccionando un archivo con extensión `.ipynb` dentro del directorio donde se lanzó el comando. Con `Upload` agregas archivos que se encuentran en otra parte de tu computadora a este directorio. Para salir, simplemente presiona el botón `Quit` y cierra la pestaña o ventada correspondiente.

Para desactivar el ambiente

```
conda deactivate
```
