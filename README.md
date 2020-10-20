# ionic-ngrx-boilerplate

Inspired by ngrx-mobile. 

### Issues found
`Schematics` doesn't support multiple collections, have to switch manually between `ionic` and `ngrx` in `angular.json`: 
```
  "cli": {
    "defaultCollection": "@ionic/angular-toolkit"
  },
```

```
  "cli": {
    "defaultCollection": "@ngrx/schematics"
  },
```
