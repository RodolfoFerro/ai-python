# Taller de AI con Python

Taller de AI con Python compartido para la comunidad de AI Gaming LATAM.

Nota, puedes ejecutar el código directamente desde Google Colab dando click [**aquí**](https://colab.research.google.com/github/RodolfoFerro/ai-python/blob/master/AI_Python.ipynb).


## Instalación

Los siguientes comandos te ayudarán a completar la instalación de dependencias, todos ellos se ejecutan desde la terminal.

1. Clona este repositorio y accede a la carpeta:
    ```bash
    git clone https://github.com/RodolfoFerro/ai-python.git
    cd ai-python
    ```

2. Crea el entorno virtual e instala las dependencias:
    ```bash
    conda env create -f environment.yml
    ```

3. Activa el entorno:
    ```bash
    conda activate ai-python
    ```

    > Para desactivar el entorno virtual:
    > ```bash
    > conda deactivate
    > ```

4. ¡Listo! Puedes comenzar a trabajar con Jupyter:
    ```bash
    jupyter lab
    ```

#### Extras

- Como tip, si tienes instalado Node.js, te recomiendo instalar un tema para tu Jupyter Lab:

    ```bash
    jupyter labextension install @yeebc/jupyterlab_neon_theme
    ```
- Igualmente, si quieres mejorar los gráficos, puedes utilizar Plotly. Para instalarlo y correrlo en Jupyter, con tu entorno activado:
    ```bash
    conda install -c plotly plotly
    ```

    E instala también las dependencias para Jupyter:
    ```bash
    jupyter labextension install jupyterlab-plotly@4.8.2
    jupyter labextension install @jupyter-widgets/jupyterlab-manager plotlywidget@4.8.2
    ```

## Conjuto de datos

Los datos pueden ser descargados desde acá y es un conjunto con dos tipos: [https://nasadata.blob.core.windows.net/nasarocks/Data.zip](https://nasadata.blob.core.windows.net/nasarocks/Data.zip)