Torres Carol

## Proyecto de App
Sebastian Mejia

En esta clase se ve un proyecto que se va a desarrollar durante el semestre

## Sistemas operativos

Osiel Morales

En esta clase se ve ciberseguridad y mantenimiento de sistemas operativos

## Lenguajes interpretados

Jon mircha

En esta clase vemos visualcode y repositorios en git

## Diseño de Videojuegos

Hector Guerrero

En esta clase vemos como diseñar videojuegos de una manera bonita

## Composición y diseño

Roberto Melo

en esta clase vemos principios sobre composición y diseño grafico


## Parcial2 Practica2
# ¿Como se inicializa un repositorio en git?
Se debe tener git instalado primeramente, luego cambiar nombre e email de usuario con 
1. git config --local user.name "Carol"
1. git config --local user.email ikkilink@hotmail.com
para poder realizar cambios, tras hacerlo ya podemos trabajar
# ¿Cómo creas un repositorio en gitHub?
Al entrar a github y ver tu perfil hay una opción que dice tus repositorios, ahí te va a dar la opción de crear uno nuevo, al seleccionarla debes ponerle un nombre y NO AGREGARLE ALGO is vas a trabajr en git ya que no va a funcionar.
# ¿Cómo vinculas un repositorio local de Git con uno remoto en GitHub?
Abres una nueva carpeta y pones el comando 
git clone https://github.com/usuario/repositorio.git
Si quieres trabajar en un repositorio de github en git que ya está trabajado primero tienes que configurar todo localmente, cambiar ramas, email, nombre, etc, sino no va a funcionar. 
1. git config --local user.name "Carol"
1. git config --local user.email ikkilink@hotmail.com
lo que local va a hacer es solo generar cambios dentro de el repositorio en vez de en todo el dispositivo, despues ya puedes trabajar en el

# ¿Cuál es el flujo básico de trabajo en Git y GitHub?

(solo si el repo es nuevo)
1. git init 
1. git add .  (agregacambios)
1. git commit -m "commit" (nombre del commit)
1. git branch -M main (cambia de branch a la main)
1. git remote add origin Linkdelrepositorio (agrega el origen del repo)
1. git push -u origin main (pushea los cambios )

para repos ya hechos  se saltan algunos pasos

1. git branch -M main
1. git remote add origin https://github.com/usuario/repositorio.git
1. git push -u origin main 

