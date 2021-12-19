PARTIE 2 :
2- Pourquoi les tests prennent autant de temps ?
    Parce que dans SortAlgorithmsTest.java, il y a un test (isWellSortedLargeArrays()) où on a la variable maxSize qui est initialisée avec une valeur qui est énorme !

PARTIE 3 :
A :
2- Relancer les tests à nouveau. Qu'avez-vous remarqué?
    Nous avons une erreur à la compilation : "20:12 java: class, interface, or enum expected"

4- Demandez aux autres membres du groupe de récupérer les derniers changements ? Que remarquez-vous ? 
    Nous remarquons que tous les membres arrivent à réucupérer la méthode, et que chacun a l'erreur de compilation.

B :
6-  Que remarquez-vous ? 
    Error:  Failed to execute goal org.apache.maven.plugins:maven-compiler-plugin:3.1:compile (default-compile) on project CDCI: Fatal error compiling: error: invalid target release: 11.0.11 -> [Help 1]
    Error:  
    Error:  To see the full stack trace of the errors, re-run Maven with the -e switch.
    Error:  Re-run Maven using the -X switch to enable full debug logging.
    Error:  
    Error:  For more information about the errors and possible solutions, please read the following articles:
    Error:  [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MojoExecutionException
    Error: Process completed with exit code 1.

9- On remarque que les tests ne passent plus à cause de la fonction badTest.

10- On constate que le code se compile à chaque fois que l'on pull le projet sur sa machine.

13- On remarque que les tests s'exécutent à chaque fois que l'on pull le projet sur sa machine.

NB : On a eu un problème avec le git (maven) qui nous empêcher de compiler le projet, c'est pour ça qu'on avait très souvent les mêmes erreurs 
On a essayé de le résoudre en appelant le prof et en recherchant de notre côté sur internet mais on a pas réussi à trouver une solution.

Partie 4 :

1- email : iuts3.class@gmail.com
NB : jsp si vous y avez accès, mais j'ai paramétré les notifications du Git sur cet email

2- Il y avait 2 méthodes : 
j'ai choisi la méthode où on invite un bot sur un slack (lien du slack en question : https://join.slack.com/t/tdfm33tp2tout-y3i3795/shared_invite/zt-10ezmp1t2-AagKD0d5JN9lfPalMqITkQ)