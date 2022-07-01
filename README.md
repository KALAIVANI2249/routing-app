## Services

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.0.2.
In angular a service is class which is decorated with
an annotation called as injectable

## Development server
that means service object does'nt need to be created by us,
we can get it injected through dependency injection [constructor based]

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.
generally we use services to call external apis and components will call 
service functions to receive and store data about

## Code scaffolding
service helps us to share functionality and data among multiple components.

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.
a service can be create by using the command

## Build
```
ng g s servicename
Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.
```

## Running unit tests
### HttpClient

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).
To call RESTAPI in angular, we use a service called HttpClient

## Running end-to-end tests
using this httpclient object you can make get,post, delete,put and patch requests 
all these request return an Observable object

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.
Observable

## Further help
  Observable is part of RXjs framework

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
  this is meant to deal with asynchronous code 

  When we call a rest service, we wont get the data immediatly,
  it ll take few millisec to seconds to receive the data

  Hence angular uses Observable to make the program
  wait for the data to be recieved

  using Subscribe method observable object you can wait
  until data is received

  to use HttpClient we need to import HttpClientModule
  to use HttpClient we need to import HttpClientModule

  ### Form Handling

  In angular , Form handling can be done in two ways

    * Template based approach [ngModel]
    * Model Based Approach [FormBuilder]

     ### pipes

  Pipes are generally used in template [html]

  it is represented by symbol |

  pipe is usually applied on scalar variable or an array 

  usually if you apply on a scalar variable [string,number,date], the data
  would formatted

  for example, some inbuilt pipes are

if data="raj" 

{{data | uppercase}}   - RAJ |

{{price | currency:"USD"}} - $5000

pipes can also be applied on array, currently there is no inbuilt pipe
that can be applied on array but we can implement it