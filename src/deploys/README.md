---
sidebar: auto
---

# Menu


## Netlify

1. con el proyecto listo, ejecutar en la carpeta vue
```
npm run build
```

2. netlify, Sites, Deploy Manually (arrastrar carpeta)


## Firebase


1. crear proyecto en firebase e instalar modulo firebase con

```
npm install firebase @angular/fire --save
```

2. crar firestore db en firebase, configurar, importar en app.module

```
import { AngularFireModule } from '@angular/fire';
import { environment } from '../environments/environment'


imports: [

    AngularFireModule.initializeApp(environment.firebaseConfig)
    
],
```

3. importar servicios de firestore en app.module y en el servicio.

```
import { AngularFirestoreModule } from '@angular/fire/firestore'; 
```

## VuePress

1. iniciar servidor 
```
yarn dev
```

2. generar carpeta dist 
```
yarn build
```

3. deploy a github pages



## Github

1. ubicarse en la carpeta raíz del proyecto, luego ejecutar
```
git init
git add .
git commit -m "message"
git remote add origin "github.com/your_repo.git"
git push -u origin master 
```

2. asegurarse de haber agregado primero, y luego hacer el push.

3. ir a Settings, apartado GitHub Pages, Seleccionar Main branch y carpeta proyecto (/docs).


