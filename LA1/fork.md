Permet de créer un processus fils.



# Includes nécessaires
```c
#include <unistd.h>
#include <sys/types.h>
```

# Définition de la fonction
```c
pid_t fork(void)
```

## Valeurs de retour
- -1 : en cas d'erreur
-  0 : Si le processus est le processus fils
- Autre : PID du processus fils si le processus est le processus père

# Exemple d'utilisation
```c
pid_t resFork = fork();

if (resFork == -1)
{
    printf("Erreur lors de la création du processus fils !\n");
    return -1;
}

else if (resFork == 0)
{
    printf("Processus fils !\n");
}
else
{
    printf("Processus père !\n");
}
```
