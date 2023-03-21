��#� �M�i�P�a�g�i�n�a�
�
�

- *Avanzar en carpetas: cd "nombreCarpeta"*
- *Volver en carpetas: cd..*

<b>Ejemplo de como subir de a un archivo al repositorio de GitHub:</b><br>
En el terminal de VS Code chequeamos que la direccion sea en la cual se encuentre el archivo que queremos subir.

- git add nombreArchivo
- git commit -m "El commit que queremos"
- git push -u origin main


<b>En caso de que nos aparezca "error: failed to push some refs to"</b><br>
En el terminal de VS Code ponemos:

- git fetch origin main:tmp
- git rebase tmp
- git push

*Clonar completamente el repositorio*
(CLICK DERECHO EN LA CARPETA DONDE QUEREMOS GUARDAR LOS ARCHIVOS Y DAR CLICK EN "GIT BASH HERE", Y EN LA CONSOLA PONER)
- git clone aquiURL

*Descargar unicamente los cambios que hubieron en nuestro repositorio*
(CLICK DERECHO EN LA CARPETA DONDE QUEREMOS GUARDAR LOS ARCHIVOS Y DAR CLICK EN "GIT BASH HERE", Y EN LA CONSOLA PONER)
- git pull origin main
