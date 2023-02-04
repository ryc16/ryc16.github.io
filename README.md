# Angular app in Githib page.

## Create Repository on github
- Create a new repository named username.github.io, where username is your username (or organization name) on GitHub. 
- Repository must be public.
> it won’t work if the first part of the repository doesn’t exactly match your username.

## Install [Angular CLI](https://angular.io/guide/setup-local) if needed
```
$ npm install -g @angular/cli
```

## Create and configure your Angular application locally

***Clone the newly created repository***
```
$ git clone https://github.com/username/username.github.io.git
$ cd username.github.io
```

***Create a new angular project in the root directory of the repo:***
```
$ ng new myApp --directory ./ 
```

***Build the angular application in production mode***
```
$ ng build --prod
```
