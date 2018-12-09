

### tsc is doing some weird things

1. if you remove src/zoom.ts and run `tsc`, then dist folder structure is different than if you run tsc with src/zoom.ts present.


2.  I want to include src/.test and transpile it to dist/.test, but if I put this in tsconfig.json:


```json

"include":[
 "src/.test/**/*.ts",
 "src"
]

``` 


