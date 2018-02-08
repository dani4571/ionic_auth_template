Authentication template for firebase.

Need to set values in src/app/app.firebase.config.ts

```
export const FIREBASE_CONFIG = 
  {
    apiKey: "",
    authDomain: "",
    databaseURL: "",
    projectId: "",
    storageBucket: "",
    messagingSenderId: ""
  };
```

to recreate:
1. ionic start auth_template blank
2. cd auth_template
3. npm install --save firebase
4. import firebase from 'firebase' in app.component.ts



