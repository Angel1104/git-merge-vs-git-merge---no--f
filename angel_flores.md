## Diferencia entre "git merge" y "git merge --no--ff"
### git merge
- Fusiona las ramas de manera automatica.
- Combina dos o mas ramas.
- los junta en la rama que indicamos sin importar la rama master.

### git merge --no-- ff
- Apunta la rama actual hasta la punta de rama del destino.
- Se creara un nuevo objeto de confirmacion.
- Evita un 'avance rapido'.
- crea un nuevo commit para no perder los cambios realizados.
  
  > Lo mejor es actualizar las ramas a pesar de que en las ultimas actualizaciones evitan que se ralice el marge.

