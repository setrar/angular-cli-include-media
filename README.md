# angular-cli-include-media


## Frontend

```bash
$ ng new frontend --style=scss
```

### Libraries

### Include Media  
```bash
$ npm install --save include-media
```

### Material  
https://material.angular.io/guide/getting-started

```bash
$ npm install --save @angular/material
$ npm install --save @angular/animations
```

* Include a theme in .angular-cli.json

```javascript
      "styles": [
        "styles.scss",
        "../node_modules/@angular/material/prebuilt-themes/indigo-pink.css"
      ],
```

* Gesture Support 

```bash
$ npm install --save hammerjs
```

### Bootstrap 

* install the packages

```bash
$ npm install ngx-bootstrap bootstrap --save
```

* Include a theme in .angular-cli.json

```javascript
      "styles": [
        ...
        "../node_modules/bootstrap/dist/css/bootstrap.min.css",
	...
      ],
```

### font-awesome 

* install the package

```bash
$ npm install font-awesome-sass --save
```
* setup angular-cli

```javascript
   "apps": [
      ...

      "styles": [
        ...  
        "../node_modules/font-awesome-sass/assets/stylesheets/_font-awesome.scss"
	...
      ],

   ],
   "addons": [
      "../node_modules/font-awesome-sass/assets/fonts/font-awesome/*.+(otf|eot|svg|ttf|woff|woff2)"
   ],
   "e2e": {
   	...
   }

```  

* import in styles.scss 

 - locate the font's path  
 - import the stylesheet

```  
$fa-font-path: "~font-awesome-sass/assets/fonts/font-awesome/" !default;

@import "~font-awesome-sass/assets/stylesheets/_font-awesome.scss";
```  
