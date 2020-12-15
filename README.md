1. Crear repositorio en gitlub
2. Clonar repositorio
	git clone https://github.com/VictorCM1995/Victor_markdown.git
3. Crear archivo README.ms
4. Realizar el primer commit
5. Crear privado y privado.txt
6. Crear archivo .gitignore, añadirlo, comentarlo y añadir los datos anteriores
	Para ver los ignorados pon git status --ignored
	Esto debe hacerse antes de crear los archivos
7. Creamos un fichero nuevo, lo editamos, lo añadimos al git y lo comentamos.
8. Creamos un tag con git tag v0.1
9. Subimos los cambios con git push origin master (Nos pedira credenciales)

CompañeroA|CampañeroB
--|--
Victor|Cuevas

[GitHub](https://github.com/)

# TAREA DE RAMAS
1. Crear nueva rama. git branch Victor
	Posicionarme. git checkout Victor
2. Añadir fichero de despliegue.md y hacer commit desde esa rama
	Subir cambios a la rama. git push origin Victor
3. Fusionar rama. git merge Victor master (Usar antes: git diff Victor master)
4. Desde master hacer cambios y comentarlo.
	Desde Victor hacer cambios y comentarlo.
	Fusionar ramas. git merger Victor master(Resultado: Conflicto)
5. Añadir el archivo y realizar commit para resolver el conflicto
6. Crear tag. git tag v0.2
	Borrar rama. git branch -d Victor
7. Todo realizado.
