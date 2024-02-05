## Set up proxy
--------------------
set HTTPS_PROXY=http://es001-surf.zone2.proxy.allianz:8080
set HTTP_PROXY=http://es001-surf.zone2.proxy.allianz:8080
set PROXY_USER=eXXXXXX
set PROXY_PASSWORD=pwd

## Install environment
----------------------
conda env create -p .\venv -f .\bin\local\environment.yml

## Github
----------------------
git checkout name_rama_interes_remoto * **Cambia de rama en el repo local**
git merge name_rama_remoto * **Fusiona la rama remota con la rama local actual**
git push origin name_rama_actual_local:name_rama_remota * **Hace push de la rama local a la rama remota**
git add file_name * **Agregar un fichero específico antes de un commit**
git add . * **Agrega todos los cambios ante de un commit**
git commit -m "Mensaje descriptivo del commit" * **Crea un commit con ese mensaje**
git fetch origin * **Actualiza el repositorio local, pero no actualiza los ficheros automaticamente**
git push origin name_rama_remota * **Actualiza inmediatamente el repo local con la rama especificada**


## Developers
----------------------
The developers responsible for the development and maintaining of this project.

* **Julian Caro** - *Author/Maintainer* - [mateocivil10@gmail.com](https://github.developer.allianz.io/jesusmanuel-sono)

