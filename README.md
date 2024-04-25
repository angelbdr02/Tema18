## Primer Paso
Lo primero que he hecho ha sido un commit en el Main,  donde a partir de ese primer commit he creado 2 nuevas ramas; Hotfix y Develop

## Segundo Paso
Me meto en la rama Hotfix y hago un commit con un cambio, después me meto en la rama main y hago un merge de hotfix por lo que consigo que se me modifique el main con lo que tenía puesto en el Hotfix

## Tercer Paso
Desde la rama Develop creo una nueva rama que se llama Feature2 y en esa rama hago 3 commit con cambios poco significativos.
Vuelvo a Develop y hago un commit, desde ese commit hago una nueva rama que se va a llamar Feature1 y desde esa rama hago un nuevo commit

## Cuarto Paso
Situado en la rama Develop hago un merge con Hotfix por lo que consigo que se me modifique el Develop con lo que tenía puesto en el Hotfix

## Quinto Paso
Situado otra vez en la rama Develop hago un merge de Feature1 donde en los pasos anteriores hice un commit por lo que en el develop aparecerá el commit de Feature1

## Sexto Paso
Me situo en Develop y creo una nueva rama llamada Release dond hago lo mismo, un nuevo commit con algún cambio.

## Séptimo Paso
Por último, nos situamos en el main y hacemos un merge de Release y nos situamos en Develop y hacemos un merge de Release y en ambos hacemos un commit final
