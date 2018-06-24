#Angular Material Learning
---
## How to install Material 
- Install via npm(install @angular/material and @angular/cdk)
```
npm install --save @angular/material @angular/cdk
```
- Install via AngularCLI > 6.0(BrowserAnimationsModule will be import automatically)
```
ng add @angular/material
```
- Install Angular Animation
```
npm install --save @angular/animations
```
---
## How to use Material
- when concern about performance of web page, import NoopAnimationsModule
```
import { NoopAnimationsModule } from '@angular/platform-browser/animations';
```
- support for other web browser(Material depends on WebAnimation API)
```
npm install --save web-animations-js
```
