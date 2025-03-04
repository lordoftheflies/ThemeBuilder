# Plutonium Theme Assembler
 
The Plutonium Theme Assembler (PTA) allows us to modify themes shipped with Plutonium or create custom themes. This tool is available [online](https://plutonium.cherubits.hu/theme-assembler/).
 

## Run locally

If you need to run the PTA locally (for example, when working with a pre-release version or a version with a hotfix applied), clone this repository and follow the instructions below.

### Prerequisites

You will need Node.js 8.9 or higher and npm 5.5.1 or higher. The app is built using angular-cli. Run `npm install @angular/cli -g` to install it.

### Install required packages and Launch

Run the following commands:
 
```
npm install
npm start
```

Go to http://localhost:4200/.

If you need a specific version of the `plutonium` package, change it in the `package.json` file. Note that the `plutonium-theme-assembler` and `plutonium-angular` packages' version should
 also be the same.


