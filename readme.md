# Initialiser le projet
```c
sudo rm .git
```

# Comment `run` le projet
```sh
chmod 777 run.sh
./run.sh
```

# Gestion des imports

Lorsque vous créez un nouveau fichier dans `src` les deux premières lignes doivent toujours être :

*fichier.c*
```c
#pragma once
#include "global.h"
```