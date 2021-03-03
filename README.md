# ng-siret-validator
[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)
## About
#### A simple SIRET validator for Angular :

* SIRET Entreprises
* SIRET La Poste 
## Installation

Run the following command to install the package :

```sh
npm install ng-siret-validator --save
```

## Setup

You must import the validator ``` ValidateSiret ``` in your component

```ts

import { ValidateSiret } from "ng-siret-validator";


 this.siretForm = this.formBuilder.group({
      siret: ['', [Validators.required, ValidateSiret]]
 });

```
