# CustomApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.2.3.

## Reproduction

Build [test-library](https://github.com/moonbeamglitterblossom/test-library) with `nx build test-library`
 and run app with `ng serve -o`. 

Browser console will show the following error: 
`Error: NG0203: inject() must be called from an injection context such as a constructor, a factory function, a field initializer, or a function used with EnvironmentInjector#runInContext.`

Running [test-app](https://github.com/moonbeamglitterblossom/test-library) with `nx serve test-app` works as expected.
