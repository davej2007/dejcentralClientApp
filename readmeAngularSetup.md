**** Angular 7 setup

ng new OurEngagementApp --routing --skip-tests=true

**** boot strap instalation

npm i -s bootstrap @ng-bootstrap/ng-bootstrap

**** angular.json ****

"options": { "outputPath": "../dejCentralNodeServer/public",

"styles": [ 
    "node_modules/bootstrap/dist/css/bootstrap.min.css",
    "src/styles.css" ],
"scripts": []

**** App.Module.ts ****

import {NgbModule} from '@ng-bootstrap/ng-bootstrap';

imports: [NgbModule, ...],

// restart NG SERVE //

**** Generate Components

1. ng g c components/pages/page-not-found --skipTests=true --prefix 
1. ng g c components/pages/section0/employeeProfile --skipTests=true --prefix 
2. ng g s components/service/auth --skipTests=true 
3. ng s -o ==== ng serve 
4. ng build --prod ==== ng build
