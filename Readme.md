## Instalation
* If repository does have a `package.json`
  * Add this code to the `package.json`

  ``  
  "devDependencies": {
    "eslint-config-fliplet": "github:YaroslavOvdii/FlipletEsLint"
  },
  ``

  ``
  "dependencies": {
    "babel-eslint": "^10.0.3",
    "eslint": "^6.8.0"
  },
  ``

  * Run `npm install`
  * Add `.eslinrc` file with this line in it

    ``
    {
      "extends": "eslint-config-fliplet"
    }
    ``

* If we doesn't have a `package.json`
  * Run `npm init` to create a `package.json`
  * Add this code to the `package.json`

  ``  
  "devDependencies": {
    "eslint-config-fliplet": "github:YaroslavOvdii/FlipletEsLint"
  },
  ``
  
  ``
  "dependencies": {
    "babel-eslint": "^10.0.3",
    "eslint": "^6.8.0"
  },
  ``
  
  * Run `npm install`
  * Add `.eslinrc` file with this line in it
    
    ``
    {
      "extends": "eslint-config-fliplet"
    }
    ``