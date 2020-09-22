# Curso de aprendizaje profundo 2021-I, PCIC-UNAM
Este repositorio contiene las diapositivas, los cuadernos y código de ejemplo del curso de [aprendizaje profundo del PCIC-UNAM](http://turing.iimas.unam.mx/~gibranfp/cursos/aprendizaje_profundo/) 2021-I.

## Temario
1. Redes densas
2. Redes convolucionales
3. Redes recurrentes
4. Estrategias y trucos de entrenamiento
5. Mecanismos de atención y memoria externa
6. Modelos generativos
7. Redes generativas
8. Sesgo e imparcialidad
9. Temas selectos

El código de acceso del Google Classroom es el siguiente: jc2wc4k


<!-- ## Ambiente de programación
Para ejecutar los ejercicios y *notebooks* de este repositorio se requiere lo siguiente:

* Python (>= 3.6)
* [Tensorflow 2](https://www.tensorflow.org/), que adopta [Keras](https://www.tensorflow.org/versions/r2.0/api_docs/python/tf/keras) como interfaz de alto nivel para construir y entrenar redes neuronales.
* [Tensorflow Probability](https://www.tensorflow.org/probability/)
* [Tensorboard](https://www.tensorflow.org/tensorboard/)
* [Tensorflow Hub](https://www.tensorflow.org/hub/)
* [scikit-learn 0.21.3](https://scikit-learn.org/)
* [matplotlib 3.1.1](https://matplotlib.org/)
* [seaborn 0.9.0](https://seaborn.pydata.org/)

Puedes usar [Google Colab](https://colab.research.google.com) o crear un ambiente local en tu computadora usando [Anaconda](https://www.anaconda.com/).

### Google Colab
[Google Colab](https://colab.research.google.com) es un servicio para crear, editar, alojar y ejecutar *noteboos* en la nube. Ofrece ambientes con CPU, GPU y TPU de forma gratuita, aunque con un tiempo máximo de ejecución.

Se sugiere trabajar en un ambiente GPU, el cual puedes activar de la siguiente manera:
* Abre el menú `Entorno de ejecución`
* Elige la opción `Restablecer todos los entornos de ejecución...` .
* Vuelve a abrir `Entorno de ejecución`
* Elige `Cambiar tipo de entorno de ejecución`
* Selecciona Python 3 como `Tipo de ejecución` y GPU de la lista de `Acelerador por hardware`

![](figs/escoge_acelerador.png)

Puedes crear un nuevo *notebook* desde Colab, subir uno existente desde tu computadora o importarlo de Google Drive o GitHub.

### Ambiente local
Para instalar el ambiente completo en tu computadora, se sugiere usar [Anaconda](https://www.anaconda.com/) con el archivo `environment_cpu.yml` de la siguiente manera:

```
conda env create -n cursoap -f environment_cpu.yml
```

Si tu computadora cuenta con GPU NVIDIA y deseas aprovecharlo, instala los controladores y cambia el archivo `environment_cpu.yml` por `environment_gpu.yml`, es decir

```
conda env create -n cursoap -f environment_gpu.yml
```

Puedes cambiar el nombre del ambiente por el que tu prefieras. Finalmente, debes activar el ambiente cuando desees utilizarlo

```
conda activate cursoap
```

Una vez activado, puedes lanzar Jupyter Notebooks

```
jupyter notebook
```

Este comando abrirá una pestaña o ventana en tu navegador web, como se muestra en la siguiente captura de pantalla:

![](figs/jupyter_notebook.png)

Aquí puedes crear un nuevo *notebook* seleccionando el botón `New` y posteriormente `Python 3`. También puedes cargar uno existente seleccionando un archivo con extensión `.ipynb` dentro del directorio donde se lanzó el comando. Con `Upload` agregas archivos que se encuentran en otra parte de tu computadora a este directorio. Para salir, simplemente presiona el botón `Quit` y cierra la pestaña o ventada correspondiente.

Para desactivar el ambiente

```
conda deactivate
``` -->
