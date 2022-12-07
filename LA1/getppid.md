Permet d'obtenir le PID du processus parent

# Includes nécessaires
```c
#include <sys/types.h>
#include <unistd.h>
```

# Définition de la fonction
```c
pid_t getppid(void)
```

## Valeurs de retour
- Le PID du processus parent.

# Exemple d'utilisation
```c
pid_t pidPere = getppid();
printf("Le PID de mon père : %d\n", pidPere);
```
