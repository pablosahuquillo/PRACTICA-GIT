# PracticaGit - Respuestas

--

**1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?**

`git reset --hard HEAD~1` 

"Porque así borro el comming y el resto de información innecesaria"

**2. ¿Qué comando o comandos utilizaste en el paso 12 ? ¿Por qué?**

`git reset --hard 8dd42eb 

Para conseguir recuperar el commit borrado hemos colocado el resetet con el numero identificador y así se recupera automaticamente el commit

--

**3.El  merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**

No, me dice se ha actualizado la pagina.

--

**4. El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**

Nos sale un conflicto al hacer merge, por la incopativilidad de archivos.Hay que volver a hacer un commit dentro de la rama "htmlify".

--

**5. El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**

No me causo conflicto. Ya que acababamos de corregir el merge anterior.

--

**6. ¿Qué comando o comandos utilizaste en el paso 25?**

`git graph

--

**7. El merge del paso 26,¿Podría ser fast forward?¿Por qué?**

No, dado que las ramas no se encuentan en la misma línea.

--


**8. ¿Qué comando o comandos utilizaste en el paso 27? **

`git reset HEAD~1`

--

**9. ¿Qué comando o comandos utilizaste en el paso 28? **

`git reset -- *.md`

--

**10. ¿Qué comando o comandos utilizaste en el paso 29? **

`git branch -D title`

--

**11. ¿Qué comando o comandos utilizaste en el paso 30? **

`git reflog`
     &
`git reset --hard 309db6f`

--
**12.¿Qué comando utilizaste en el paso 32?*

`git reflog`
`git reset --hard be33048`

--

**13. ¿Qué comando o comandos utilizaste en el paso 33? **

`git reflog`
`git reset --hard be33048`

--