# Angular training

This training is a combination of the theory and practice. A trainee will learn fundamental concepts of building applications in scope of this training. At the end of this training a TODO list Angular application should be developed based on the similar tech stack and approaches which are used in MS app.

Fundamental concepts to be covered in the training:

1. Angular CLI. This is a command-line interface tool that you use to initialize, develop, scaffold, and maintain Angular applications directly from a command shell.

2. UI-Router for Angular (https://ui-router.github.io/ng2/). The library provides state based routing to the Angular (2+) ecosystem. NOTE: Angular has awesome built-in router, but we use UI-Router because it supports communication between AngularJS and Angular apps.

3. NgXs libary for application state management.


## LESSONS

1. 
  - Quick introduction to frontend frameworks (What's problem they are solved and why they exist)
  
    <https://www.quora.com/As-a-web-developer-can-you-explain-why-React-is-needed/answer/Jérôme-Cukier> (it is about React, but it can be applied to any frontend framework)
  
  - NPM (package manager for node)
   	<https://medium.com/beginners-guide-to-mobile-web-development/introduction-to-npm-and-basic-npm-commands-18aa16f69f6b>
  
  - Angular CLI. Create our first Angular app
  
    <https://angular.io/cli>
  
  - Explain structure of created app
  
    <https://angular.io/guide/file-structure>
  
  
  > **HOMEWORK:** create a GitHub repository. Install NPM and then Angular CLI via NPM globally. Create an Angular app using Angular CLI. Run app in dev mode, create prod build. Push project to repository.

***
  
2.
  - Explain component based architecture in common
  
    <https://www.sparkbit.pl/component-based-architecture-angular-2/>
  
  - Components in Angular
  
    <https://angular.io/guide/architecture#components>
  
  - What's directives? Difference directive types
  
    <https://angular.io/guide/built-in-directives>
  
  - Angular modules
  
    <https://angular.io/guide/architecture-modules>
  
  
  > **HOMEWORK:** HOMEWORK: Create a new module in the app. Add a stub component which will be used as dashboard with TODO list. Import the module to App module and use the created component.

***

3. 
  - Routing in single page applications.

    <https://dev.to/marcomonsanto/routing-in-spas-173i>
    
  - Angular UI-Router

    <https://ui-router.github.io/ng2/>

  - Angular project structure.

    <https://itnext.io/choosing-the-right-file-structure-for-angular-in-2020-and-beyond-a53a71f7eb05>
  
  - Feature modules. Lazy-loaded feature modules

    <https://angular.io/guide/feature-modules>
    
    UI-Router lazy-loaded modules <https://ui-router.github.io/guide/lazyloading>

  - Debugging web/Angular app.

    Debugging in Google Chrome <https://stackoverflow.com/a/51941277>
  
    Debug Angular app in IDEA <https://www.jetbrains.com/help/idea/angular.html#angular_running_and_debugging_debug>
    
    Debug Angular app in Visual Studio Code <https://code.visualstudio.com/docs/nodejs/angular-tutorial#_debugging-angular>
  
    Angular DevTools <https://angular.io/guide/devtools>
  
  > **HOMEWORK:** HOMEWORK: Refactor app structure. Uninstall Angular router and replace it with Angular UI-Router. Create feature modules for TODO list page(s) and for About page. Add navigation between TODO and About pages to main app component. Use lazy loading for the feature modules. Try to debug app using DevTools in Google Chrome.

***

4. 
  - Angular services

    <https://angular.io/guide/architecture-services>

  - Dependency injection pattern. Dependency injection in angular.

    <https://angular.io/guide/dependency-injection>

  - Reactive forms.

    <https://angular.io/guide/reactive-forms>
  
  > **HOMEWORK:** create form component to add TODO item (Use reactive form). Register a new page with this component. Add "Create TODO item" button to TODO list page and navigate to new TODO item page by click.

***
  
5.
  - How Angular sync model and view. Zone.js, change detection.
  - Different change detection strategies.
  - RxJS library. How it is used by Angular
  
  
  > **HOMEWORK:** HOMEWORK: Add service(s) to work with TODO list data (retrive list, add new item).

***
  
6. 
  - Application state management. Redux pattern.

    <https://www.linkedin.com/pulse/understanding-state-management-front-end-paradigm-jitendrasinh-gohil/?articleId=6691234562036563968>

  - Angular libraries for state management. NgXs.

    <https://www.ngxs.io/getting-started/why>
  
  
  > **HOMEWORK:** HOMEWORK: add NgXs library to the app. Refactor the app and add application state management based on NgXs.
  
***

7.
  - CSS preprocessors. SCSS. How to add styles to components in angular.
  - Some tools to increase code quality (TSLint/ESlint, Prettier)
  
  
  > **HOMEWORK:** HOMEWORK: Run TSLint using Angular CLI. Add styles to components in app. Try different ViewEncapsulation modes.

***
