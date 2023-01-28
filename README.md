# Fake Shop

This project is a sample e-commerce website built with Vue 3 and TypeScript. It features a login system, a product listing page, a product detail page, and a user profile page.

It includes the following features:

- Vue 3 with the Composition API
- TypeScript
- Vue Router for client-side routing
- Vuex for state management
- Axios for HTTP requests
- ESLint and Prettier for linting and code formatting
- https://api.escuelajs.co/api for product database and user authentication
- Designed for colour blindness accesibility 

## Getting Started

```sh
git clone https://github.com/<YOUR-USERNAME>/<YOUR-REPO>.git
cd <YOUR-PROJECT-NAME>
npm install
```

Then, start the development server:

```sh
npm run serve
```

This will start a development server on http://localhost:8080. The application will automatically reload if you make changes to the code.

## Building and Deployment

To build the application for production, run:

```sh
npm run build
```

This will create a production-ready build in the `dist` directory. You can then deploy the contents of this directory to your web server.

## Project Structure

The project is structured as follows:

```yaml
├── public                          # Contains the static assets for the application.
├── src                             # Contains the source code for the application.
│   ├── assets                      # Contains the assets such as images, fonts, etc. 
│   ├── components                  # Contains the Vue components for the application.
│   ├── router                      # Contains the configuration for the Vue Router.
│   ├── store                       # Contains the configuration for Vuex.
│   │   ├───authentication          # Contains the authentication store.
│   │   └───products                # Contains the products store.
│   ├── views                       # Contains the Vue views for the application.
│   ├── App.vue                     # The root Vue component for the application.
│   └── main.ts                     # The entry point for the application.
├── .eslintrc.js                    # File for configuring ESLint.
├── package.json                    # File that contains information about the project and its dependencies. 
├── tsconfig.json                   # File for configuring Typescript.
├── vue.config.js                   # File for configuring the Vue CLI.
└── README.md                       # The file you are reading right now.
```

## How to Log In and Website Usage

In order to use the website, you must log in. You may log in with one of the following users:

```json
"email": "john@mail.com", "password": "changeme"
"email": "maria@mail.com", "password": "12345"
"email": "admin@mail.com", "password": "admin123"
```

Once logged in, you will have access to the following views:

- Profile: where you can see your user information.
- Product Listing: where you can see the available products and search them by name.
- Product Detail: where you can see all the the product available photos.

Please note that the search bar only allows you to use it when you type at least three characters.

## Images

<details>
<summary>Click to open the dropdown</summary>
<br>

![main page](https://imgur.com/QC90MSv.png)
![detail page](https://imgur.com/NTcEYu3.png)
![search bar use](https://i.imgur.com/xNyUTtJ.png)

</details>
