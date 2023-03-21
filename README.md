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
