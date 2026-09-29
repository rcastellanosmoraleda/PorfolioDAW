# GitHub: Funciones principales

## Rodrigo Castellanos

_GitHub_ es una plataforma que permite guardar y gestionar proyectos utilizando **Git** como sistema de control de versiones.

## ¿Qué es un [repositorio](https://docs.github.com/es/repositories)?

Un repositorio es el lugar de GitHub donde se almacenan los archivos de un proyecto, como el código, la documentación y el historial de todos los cambios realizados.

> Los repositorios pueden ser públicos o privados y también permiten añadir colaboradores para trabajar entre varias personas en un mismo proyecto.

Dentro del repositorio podemos crear un archivo **README.md**, que normalmente se utiliza para explicar el proyecto, su funcionamiento o indicar cómo utilizarlo.

> Cuando realizamos y guardamos cambios se crea un commit. Cada commit registra información como el autor, la fecha, un mensaje explicando el cambio y los archivos modificados. Gracias a esto podemos consultar versiones anteriores del proyecto si fuera necesario.

El historial de cambios se puede consultar desde el apartado de [commits](https://docs.github.com) del repositorio.

###### Comandos básicos de Git

Para trabajar con un repositorio desde nuestro ordenador, primero podemos clonarlo y después utilizar los comandos básicos de Git:

```bash
git clone https://github.com/cras700/pruebaGithub.git
git add .
git commit -m "Cambios realizados en el proyecto"
git push origin main
```

Con estos comandos podemos descargar el repositorio, preparar los archivos modificados, crear un commit y finalmente subir los cambios a GitHub.

![GitHub Mark](https://libraries.mit.edu/app/uploads/sites/4/2017/08/GitHub-Mark.png)

Después de utilizar `git push`, los cambios realizados aparecen en la rama correspondiente del repositorio, normalmente **main**.

## Ramas y colaboradores

Las ramas permiten realizar modificaciones sin cambiar directamente la rama principal. De esta forma podemos trabajar en una parte del proyecto y, cuando esté terminada, añadir los cambios mediante una [pull request](https://docs.github.com/es/pull-requests).

| Paso | Acción | Resultado |
| --- | --- | --- |
| 1 | Crear una rama | Se crea una rama independiente de `main` |
| 2 | Modificar archivos | Los cambios se realizan sin afectar a `main` |
| 3 | Crear pull request | Se pueden revisar los cambios realizados |
| 4 | Hacer merge | Los cambios pasan a formar parte de `main` |

### Funciones utilizadas en la práctica

* Crear un repositorio y su archivo README.
* Subir archivos y realizar commits.
* Consultar el historial de commits.
* Crear una rama.
* Realizar una pull request.
* Añadir colaboradores al repositorio.

### Pasos para añadir un colaborador

1. Entrar en **Settings** dentro del repositorio.
2. Acceder al apartado **Collaborators**.
3. Pulsar en **Add people**.
4. Buscar el nombre de usuario de la persona que queremos añadir.

## Conclusión

GitHub es una herramienta muy útil para guardar y organizar el código de nuestros proyectos. Además, permite llevar un control de los cambios realizados y facilita el trabajo en equipo mediante repositorios, commits, ramas, pull requests y colaboradores.

Conocer estas funciones básicas es importante para trabajar de una forma más organizada y también es algo habitual en el día a día de un desarrollador.

## Enlaces

* Herramienta: [github.com](https://github.com)
* Repositorio de la práctica: [github.com/cras700/Repositorio](https://github.com/rcastellanosmoraleda/PorfolioDAW)
* Documentación oficial: [docs.github.com](https://docs.github.com)
