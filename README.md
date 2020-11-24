![Simplicit&eacute; Software](https://www.simplicite.io/resources/logos/logo250.png)
* * *

Web demo
========

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=simplicitesoftware_web-demo&metric=alert_status)](https://sonarcloud.io/dashboard?id=simplicitesoftware_web-demo)

This project is a **very basic** web front-end demo using
the [Simplicit&eacute;&reg; node.js &amp; browser JavaScript library](https://github.com/simplicitesoftware/nodejs-api)
to connect to a Simplicit&eacute;&reg; demo backend instance from the **client-side**.


Install:

```bash
npm install
```

Run in development mode:

```bash
npm run watch & npm run start
```

Build for production:

```bash
npm run build
```

Run in production mode:

```bash
npm run serve
```

Frameworks tips &amp; tricks
----------------------------

In [Angular&reg;](https://angular.io) or in [Vue.js](https://vuejs.org/),
after adding the dependency `"simplicite": "latest"`in the `package.json`,
you can include the Simplicit&eacute;&reg; node.js &amp; browser library like this.

```typescript
import Simplicite from 'simplicite';
```

Then you can start an application session by:

```typescript
let app = Simplicite.session({ /* Your application's parameters */ });
```

The usage is similar to the example of this repository.

License
=======

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at:

[](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
