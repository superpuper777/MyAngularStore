# My Angular Store

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.1.1.

I used in this project HttpClient, [Material Design](https://material.angular.io/guide/getting-started), [Faker data](https://github.com/Marak/faker.js), Pagination, mocking a REST API and eventually [deployed it on Firebase](https://firebase.google.com/docs/web/setup?hl=ru).

## Json server

Install json-server from npm in your project:

```sh
$ npm install --save json-server
```

And run it:

```sh
$ npm run server
```

Server will be available from the  `http://localhost:3000/`  address.

## Faker data

Install Faker.js from npm:

```sh
npm install faker —save
```

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Develoy on Firebase

You should have created a [Firebase](https://firebase.google.com/docs/web/setup?hl=ru) project before deploying

Run it:

```sh
ng add @angular/fire
```

The CLI will prompt you to Paste authorization code here: and will open your default web browser and ask you to give Firebase CLI permissions to administer your Firebase account.
After you sign in with the Google account associated with your Firebase account, you'll be given the authorization code.
Next, you'll be select your project and deploy your application to Firebase:

```sh
ng deploy
```
