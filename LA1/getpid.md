Permet d'obtenir son PID

# Includes nécessaires 
```c
#include <sys/types.h>
#include <unistd.h>
```

# Définition de la fonction
```c
pid_t getpid(void)
```

## Valeurs de retour
- Le PID du processus courant.

## Exemple d'utilisation
```c
pid_t monPid = getpid();
printf("Mon PID : %d\n", monPid);
```
