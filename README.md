# Cookiecuter - personal templates

Create a project template with cookiecutter.

## Requirements

- [Anaconda](https://www.anaconda.com/download/) >= 4.x
- [git](https://git-scm.com/) >= 2.x
- [Cookiecutter Python package](http://cookiecutter.readthedocs.org/en/latest/installation.html) >= 1.4.0:

You can install cookiecutter through `pip` or `conda`, depending on how manage your python packages:

``` bash
pip install cookiecutter
```

or

``` bash
conda install -c conda-forge cookiecutter
```

## Usage

Execute the following right where you want the project to be created:

```bash
cookiecutter https://github.com/tasc333/cookiecutter-personal --checkout cookiecutter-personal
```


## Folders and files distribution

    {{ cookiecutter.project_slug }}
        ├── data
        │   ├── processed      <- The final, canonical data sets for modeling.
        │   └── raw            <- The original, immutable data dump.
        │
        ├── notebooks          <- Jupyter notebooks.
        │
        ├── .gitignore         <- Files to ignore by `git`.
        │
        ├── environment.yml    <- The requirements file for reproducing the analysis environment.
        │
        └── README.md          <- The top-level README for developers using this project.

---

Project created as part of the course *Configuración Profesional de Entorno de Trabajo para Ciencia de Datos* by [Platzi](https://platzi.com/). Based on [Cookiecuter Personal Platzi](https://github.com/platzi/curso-entorno-avanzado-ds/tree/cookiecutter-personal-platzi) by [@jvelezmagic](https://twitter.com/jvelezmagic). 