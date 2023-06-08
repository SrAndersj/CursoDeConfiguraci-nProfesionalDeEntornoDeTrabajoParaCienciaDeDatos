# INSTALL   

first 

install conda

```commandline
mkdir cookiecutter-personal

#agregamos el canal conda forge
# es decir de donde va a buscar conda
# para descargar un paquete


conda config --add channels conda-forge

conda create --name cookiecutter-personal cookiecutter=1.7.3



# To activate this environment, use
#
#     $ conda activate cookiecutter-personal
#
# To deactivate an active environment, use
#
#     $ conda deactivate



conda activate cookiecutter-personal


conda env export --from-history --file enviroment.yml

ls

cat enviroment.yml



```

# repositorio github del curso 

https://github.com/platzi/curso-entorno-avanzado-ds
## SSH
git@github.com:platzi/curso-entorno-avanzado-ds.git

rama cookicuter-personal-platzi

copiar el comando crear nuevo proyecto 

cookiecutter https://github.com/platzi/curso-entorno-avanzado-ds --checkout cookiecutter-personal-platzi


code cookiecutter_testing/

a




