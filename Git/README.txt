README

name: Cristian Emir de la Cruz de la Cruz
registration: 3008935
number: 9931467532
degree: 6° Semestre
semester: 6

1.	Comprobar el estado de un repositorio local.
git status

2.	Agregue archivos individuales o globalmente.
git add [nombre del archivo]

3.	Agregue comentarios a la confirmación.
git commit -m "Tu mensaje de commit"

4.	Cargue los cambios en el repositorio remoto.
git push
git push origin [nombre de la rama]

5.	Crear, examinar y eliminar ramas.
•	Crear una nueva rama:
git branch [nombre de la nueva rama]
•	Cambiar a una rama específica:
git checkout [nombre de la rama]
•	Eliminar una rama:
git branch -d [nombre de la rama]

6.	Revertir un repositorio a una confirmación específica.
•	Primero, encuentra el identificador del commit al que quieres revertir usando:
git log			
•	Luego, usa el siguiente comando para revertir:
git reset --hard [identificador del commit]
