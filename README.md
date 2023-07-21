# CV-proyecto-diplomado- HTML y CSS
Este proyecto consiste en la creación de 2 CV (Currículum Vitae) utilizando HTML y CSS. Cada integrante del equipo ha trabajado en su propio CV en ramas separadas, llamadas "atilio_dev" y "sara_dev". Luego, se ha consolidado el código en la rama "dev" para revisión y, una vez aprobado, se ha fusionado con la rama "main".

# Estructura del repositorio

- master (main)
    - atilio_dev
    - sara_dev
    - dev
La rama "atilio_dev" contiene el CV de Atilio.
La rama "sara_dev" contiene el CV de Sara.
La rama "dev" se utiliza para combinar los CV de Atilio y Sara antes de llevarlos a main.

# Instalación

Para ver el proyecto en tu máquina local, sigue estos pasos:

 1. Clonar el repositorio: Abre una terminal o consola en tu computadora y ejecuta el siguiente comando:
    git clone https://github.com/st1nkyd00d/CV-proyecto-diplomado.git
    
  2.Cambiar a la rama main:
    git checkout main
    
  3.Visualizar los CV: Ahora, simplemente abre los archivos HTML de los CV en tu navegador para ver los resultados. 

# Contribuciones

  1.Crear una rama de trabajo: Antes de realizar cambios en el código, crea una nueva rama a partir de la rama dev. Nombra la rama de manera descriptiva, por ejemplo:
  - git checkout dev
  - git pull origin dev
  - git checkout -b feature/nueva_funcionalidad

  2.Realizar cambios: Realiza los cambios en el CV que consideres necesarios utilizando HTML y CSS.

  3. Hacer commit: Después de realizar tus cambios, haz un commit y agrega un mensaje descriptivo:
  - git add .
  - git commit -m "Agrega nueva funcionalidad al CV de Atilio"

  4.Subir los cambios: Sube tus cambios a GitHub en tu rama:
    - git push origin feature/nueva_funcionalidad

  5.Crear una Pull Request: Ve a la página del repositorio en GitHub y crea una Pull Request (PR) desde tu rama hacia la rama dev. Describe los cambios que has realizado en la PR.

Una vez revisada y aprobada la PR, los cambios se fusionarán en la rama dev. Posteriormente, cuando se considere que la rama dev tiene todas las actualizaciones necesarias, se podrá llevar a la rama main siguiendo un proceso similar mediante una PR.


