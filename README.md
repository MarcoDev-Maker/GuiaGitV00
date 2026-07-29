# Guía Git

<h1 align="center">Hola, soy Marco <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="35"></h1>
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Time+New+Roman&color=%23C8BE25&size=25&center=true&vCenter=true&width=600&height=100&lines=Ingeniero+TI;Siempre+hay+algo+nuevo+que+aprender">
</p>

<p align = "center">
	<img src = "https://github.com/7oSkaaa/7oSkaaa/blob/output/github-contribution-grid-snake.svg?" alt = "Snake Game"/>
</p>

<p align = "center">
Este repositorio se crea con la finalidad de poner em práctica algunos de los comandos Git mas usados en un entorno laboral profesional.
</p>

</br>

<div>
<h2>  🖥 Comandos desde GitBash</h2>

📝 Pasos para subir cambios a una rama remota desde una rama local

- 1.- Desde nuestra rama local agregamos el o los cambios que realizamos
- git add <url/del/archivo>

- 2.- Desde nuestra rama local realizamos el commit
- git commit -m "mensaje"

- 3.- Desde nuestra rama local confirmamos el cambio, lo anexamos
- git push <url/de/nuestra/rama/remota>
- git push origin rama

- 4.- Desde nuestra rama local hacemos el cambio a nuestra rama remota
- git checkout <ramaRemota>

- 5.- Una vez estemos pocisionados en nuestra rama remota, vamos a verificar que esta tenga los cambios de nuestra rama principal, para que no genere conflicto al momento de hacer merge con la rama main
- git pull <url/de/la/rama/principal>
- git pull origin main

- 6.- Traemos el cambio desde nuestra rama Local a la rama que queremos actualizar
- git checkout <url/rama/commit/o/tag> -- <ruta/del/archivo>

- 7.- Una vez que ya tenemos el cambio que deseamos en la rama que queremos, preparamos el cambio para el siguiente commit
- git add <ruta/del/archivo>

- 8.- Ahora toca guardar el cambio en el historial de la rama actual
- git commit -m "Mensaje-historial"

- 9.- Por ultimo, publicamos el cambio desde la rama remota
- git push <url/rama/remota>
- git push origin <rama/remota>

</div>