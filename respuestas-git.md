# Respuestas Git

1. **¿Qué diferencia existe entre git add y git commit?**
   El add es como elegir qué cambios quiero meter, y el commit es cuando ya los guardo de verdad con su mensaje.

2. **¿Qué hace git push y por qué puede ser rechazado?**
   Sube mis commits a GitHub. Te lo rechaza si en GitHub hay algo nuevo que tú no tienes, y hasta que no te lo bajas no te deja.

3. **¿En qué se diferencian git fetch y git pull?**
   El fetch solo mira qué hay nuevo en GitHub pero no te cambia nada. El pull te lo baja y te lo mete en tus archivos.

4. **¿Qué significa origin/main?**
   Es la rama main de GitHub, o sea cómo estaba GitHub la última vez que hice fetch.

5. **¿Qué muestra git status antes y después de git add?**
   Antes te sale el archivo como modificado y en rojo, y después te sale en verde como listo para el commit.

6. **¿Para qué sirve git diff --cached?**
   Para ver lo que ya he metido con el add antes de hacer el commit, por si se me ha colado algo.

7. **¿Qué indica git log --oneline HEAD..origin/main?**
   Los commits que están en GitHub y yo todavía no tengo. Si no sale nada es que voy al día.

8. **¿Por qué conviene realizar commits pequeños y descriptivos?**
   Porque así sabes qué hiciste en cada uno, y si algo se rompe es más fácil saber dónde.

9. **¿Cómo resolviste el push rechazado y por qué no utilizaste --force?**
   Hice un fetch para ver qué había, luego un pull --no-rebase para juntarlo con lo mío y ya me dejó hacer el push. El --force no lo usé porque te cargas lo que subió el otro equipo.

10. **¿Qué diferencia hay entre un diagrama de clases y un diagrama de secuencia?**
    El de clases te dice cómo está montado el programa, con las clases y cómo se relacionan. El de secuencia te dice qué pasa y en qué orden se mandan los mensajes.

11. **¿Qué utilidad tienen los breakpoints durante una depuración?**
    Paras el programa en una línea y ves cuánto valen las variables en ese momento, así vas paso a paso hasta encontrar el fallo.

12. **¿Por qué son importantes las pruebas antes y después de refactorizar?**
    Para estar seguro de que después de cambiar el código sigue funcionando igual y no has roto nada.

13. **¿En qué carpeta y ventana de IntelliJ estabas cuando se rechazó el push?**
    En la carpeta dam-ets-equipo2, en la ventana de IntelliJ del equipo 2.