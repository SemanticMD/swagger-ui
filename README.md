# SemanticMD Swagger Docs Generator

## What's Swagger?

The goal of Swagger™ is to define a standard, language-agnostic interface to REST APIs which allows both humans and computers to discover and understand the capabilities of the service without access to source code, documentation, or through network traffic inspection. When properly defined via Swagger, a consumer can understand and interact with the remote service with a minimal amount of implementation logic. Similar to what interfaces have done for lower-level programming, Swagger removes the guesswork in calling the service.


Check out [Swagger-Spec](https://github.com/swagger-api/swagger-spec) for additional information about the Swagger project, including additional libraries with support for other languages and more.


## How to Use It

### Download
You can use the swagger-ui code AS-IS!  No need to build or recompile--just clone this repo and use the pre-built files in the `dist` folder.  If you like swagger-ui as-is, stop here.

##### Browser support
Swagger UI works in all evergreen desktop browsers (Chrome, Safari, Firefox). Internet Explorer support is version 8 (IE8) and above.

### Build
You can rebuild swagger-ui on your own to tweak it or just so you can say you did.  To do so, follow these steps:

1. `npm install`
2. `gulp`
3. You should see the distribution under the dist folder. Open [`./dist/index.html`](./dist/index.html) to launch Swagger UI in a browser

### Development
Use `gulp watch` to make a new build and watch for changes in files.

## Swagger License

Copyright 2011-2015 SmartBear Software

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at [apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
