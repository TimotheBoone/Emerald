Permet d'obtenir son EUID

# Includes nécessaires 
```c
#include <sys/types.h>
#include <unistd.h>
```

# Définition de la fonction
```c
uid_t geteuid(void)
```

## Valeurs de retour
- Le EUID du processus courant.

**Exemple d'utilisation :**
```c
uid_t monEuid = geteuid();
printf("Mon EUID : %d\n", monEuid);
```
