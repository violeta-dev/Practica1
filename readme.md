- ¿Qué comando utilizaste en el paso 11? ¿Por qué?

git reflog
git reset --hard 27a92ad
reset hard te cambia el working y te apunta al último cambio al que quieres ir ( con reflog ves el hash al que quieres apuntar)

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
 git reflog
 git reset --hard c352aa7
 Para estar igual que antes y tener el mismo archivo en working area

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
No, porque no se ha modficado la información , solo estilo

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Sí, porque cambiamos fin de linea/datos

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No, porque no hay distinta información

- ¿Qué comando o comandos utilizaste en el paso 25?
git log --pretty=oneline --graph

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
Sí, porque master y title están en la misma lista

- ¿Qué comando o comandos utilizaste en el paso 27?
git reflog
git reset c352aa

- ¿Qué comando o comandos utilizaste en el paso 28?
git reflog
git reset --hard 30f703c

- ¿Qué comando o comandos utilizaste en el paso 29?
git branch -D title

- ¿Qué comando o comandos utilizaste en el paso 30?
git reset --hard c398ecf 

- ¿Qué comando o comandos usaste en el paso 32?
git reset --hard 30f703c

- ¿Qué comando o comandos usaste en el punto 33?
git reset --hard c398ecf
