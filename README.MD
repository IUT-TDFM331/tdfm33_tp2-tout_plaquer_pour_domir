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

10- On constate que voilà

11-