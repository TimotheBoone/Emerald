Termine un processus avec un status de fin.

# Includes nécessaires
```c
#include <stdlib.h>
```

# Définition de la fonction
```c
void exit(int __status)
```

## Arguments 
- ```c int _status``` : Status de sortie

# Exemple d'utilisation
```c
bool erreur;
if (erreur)
{
	// On quitte avec un status d'erreur
	exit(-1);
}
// On quitte avec un status de succès
exit(0);
```
