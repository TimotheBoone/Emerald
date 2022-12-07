**Définition de la fonction :**
```c
gid_t getgid(void)
```

Permet d'obtenir son GID

**Includes nécessaires :** 
```c
#include <sys/types.h>
#include <unistd.h>
```

**Valeurs de retour :**
- Le GID du processus courant.

**Exemple d'utilisation :**
```c
gid_t monGid = getgid();
printf("Mon GID : %d\n", monGid);
```
