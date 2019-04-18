# Smart Attendance Project


## Overview
SmartAttendance Attendence solution that is ASP.NET Core based with a MS Server 2017 or higher backend database.


## Architecture
 "N" tier/layer architecture.


## Framework/Library/Technology/Service

### Back-End Technology
1. ASP.NET Core SDK 2.0 or higher

### Front-End Technology
1. Node - 10.15.3,
1. NPM - 6.4.1,
1. Typescript : 2.5.3,
1. Angular : 5.2.11,
1. Angular CLI: 1.7.4
1. @aspnet/signalr : 1.0.2
1. @progress/kendo-angular-dateinputs: 3.4.4
1. @progress/kendo-angular-intl: 1.4.1
1. @progress/kendo-angular-l10n: 1.2.0
1. ngx-bootstrap: 2.0.5
1. ngx-device-detector: 1.3.0

### Tools
1. Visual studio 2017 (API Project)
1. Microsoft SQL Server Management Studio 
1. Visual studio code (UI Project)

### Installation & Run
> * **To install and run the project perform the following steps (For API)** 
>   * Install ASP.NET core - https://dot.net
>   * Open the .sln file in Visual Studio 2017
>   * Build and run the application (F5)
>   * Browse to http://localhost:58138
> * **To install and run the project perform the following steps (For UI)**
>   * Install Node.js 10.15.3 - https://nodejs.org
>   * Install the Angular CLI: npm install -g @angular/cli
>   * Open a command prompt and cd into the project's Client folder.
>   * Run `npm install`.(For install node-package-manager).
>   * Run `npm start` or "ng serve" 
>   * Visit http://localhost:4200 in the browser

### Repo Structure
```bash
├── e2e
├── src (Source Code)
│   ├── app
│   ├── assets
│   ├── enviroments
│   ├── wcu
│   ├── favicon.ico
│   ├── index.html
│   ├── main.ts
│   ├── media.css
│   ├── polyfills.ts
│   ├── styles-kendo.css
│   ├── styles-wcu.css
│   ├── styles.css
│   ├── test.ts
│   ├── tsconfig.app.json
│   ├── tsconfig.spec.json
│   ├── typing.d.ts
├── dist (or build)
├── .angular-cli.json
├── .editorconfig
├── karma.conf.js
├── package-lock.json
├── package.json
├── protractor.conf.js
├── README.md
├── tsconfig.json
├── tslint.json
└── 
```

### Environment 
* Path : /Cvue/CvueIntegrationAPI/api/

* Environment URL:
> * Development :  http://10.163.90.146
> * Production : http://webapps.americancareer.com
> * Test : http://10.163.90.146

