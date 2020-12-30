# Testing Quirks

### No Provider For Store
[Stack Overflow #1](https://stackoverflow.com/questions/45849031/how-to-mock-ngrx-store-state-in-angular-4-unit-tests)

You have to call the StoreModule, define a root, and a feature from what I can tell.  More research later, as for the moment I am just trying to write tests.


### No Provider for FormBuilder
[Stack Overflow #1](https://stackoverflow.com/questions/40249065/no-provider-for-formbuilder)  

Just include the ReactiveFormsModule in the imports.  Why in the imports rather than the providers??  The module probably includes some sort of provider built in someplace.