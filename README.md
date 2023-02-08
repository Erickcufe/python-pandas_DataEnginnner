# python-pandas_DataEnginnner

## Entornos de python

Esto para crear un entorno vacío:
```
nvim setup-env.sh
source setup-env.sh
```


Para ver la documentación de pip:
```
pip help
```

Para ver la documentación del comando install:
```
pip help install
```

Para instalar el paquete **request**:

```
pip install requests
```

Para ver los paquetes instalados en el entorno actual:

```
pip list
```

Para ver las versiones disponibles del paquete **request**:
```
pip install requests==
```

Elija una versión anterior de **request** e instale esa versión:
```
pip install requests==2.25.1
```

Upgrade to the latest version:
```
pip install requests --upgrade
```

Guardar archivo de requisitos en Python:
```
pip freeze > requierements.txt
cat requierements.txt
```

Para desinstalar los requisitos:
```
pip uninstall -r requirements.txt
```

## Creación y uso de un entorno virtual Python

A partir de Python 3.5 se pueden generar entornos con la funcion `venv`:
```
python -m venv enviroment-name
```

Los pasos para la creacion del entorno virtual en un projecto son los siguientes:
```
mkdir my_new_project
cd my_new_project
python -m venv env
ls env 
source env/bin/activate
```

A partir de ahora todo lo que se instale con **pip** será guardado exclusivamente en este entorno virtual.

Para desactivar el entorno virtual se usa el comando `deactivate`













