# Introduccion a Git
* Git es solo uno de los varios VCS que hay.
* Es el mas popular y fue creado por la comunidad de desarrollo de Linux. Especificamente por Linus Torvalds.

## Funcionamiento de Git
* Cuando se hace una confirmacion (commit) se crea, comprime y guarda 3 objetos:
    * **Snapshot** (Tree Object)
    * **File(s)** (Blob Object)
    * **Commit** (Commit Object)
* Cada archivo en Git se identifica por un Key (SHA-1 hash)
* Como cada hash esta relacionado con otro Snapshot con Files, y Commit con Snapshot > **Integridad**: es imposible cambiar algo sin que git se entere.
* Git es distribuido: DVCS. Significa que cada colaborador tiene una copia del proyecto entero en su computadora.
* Esto permite que se pueda trabajar de forma offline. A diferencia de otros VCS como Subversion que son centralizados.
* En git hay 3 estados: 
    * *MODIFIED* (Working Tree)
    * *STAGED* (Staging/Index Tree)
    * *COMMITTED* (Local Repository)
