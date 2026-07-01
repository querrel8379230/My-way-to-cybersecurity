## git config

**Qué hace:** guarda tu nombre y correo en tu sistema.

**Para qué sirve:** cada commit lleva tu nombre y correo pegados, como firma.

**Por qué se necesita:** git fue diseñado para que varias personas trabajen juntas. Necesita saber quién hizo cada cambio.

Comandos:
git config --global user.name "tu nombre"
git config --global user.email "tu correo"




## git clone

Descarga el repositorio de GitHub a mi máquina (carpeta local).
Se usa una sola vez, la primera vez.

git clone https://github.com/querrel8379230/My-way-to-cybersecurity
git clone https://github.com/"usuario"/"repositorio"


## subir cambios a GitHub


git add "arcivo que quieres subir".md — selecciona el archivo, le dice a git "este quiero subir".
git commit -m "descripción" — toma la foto del archivo con un mensaje describiendo qué cambiaste.
git push — sube esa foto a GitHub. Este es el que realmente lo pone en la nube.
