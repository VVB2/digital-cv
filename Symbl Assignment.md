# Getting Started with this project

## About this project

This is a **`React`** self-project to show the skill of working with **API** calls.

---

## Prerequisite

You need to have [**node**](https://nodejs.org/en/) as well as [**npm**](https://nodejs.org/en/) installed on your machine

---

The working website can be found [**here**](https://relaxed-volhard-592c17.netlify.app) \
The API endpoint is located [**here**](https://react-sandwich-app.herokuapp.com/api/get-data)

---

## Client side project setup

### Steps to successfully run this project

-   Clone the github repository

    #### ```git clone https://github.com/VVB2/symbl.ai-client```

-   Change into the directory

    #### ```cd symbl.ai-client-main```

-   Install all the depenedencies using

    #### ```npm install```

-   The project is ready to be run in a development mode using

    #### ```npm start```

    Runs the app in the development mode.\
     Open [http://localhost:3000/](http://localhost:3000/) to view it in the browser.

    The page will reload if you make edits.\
     You will also see any lint errors in the console.

-   You can test your application using the

    #### ```npm test```

    Launches the test runner in the interactive watch mode.\
     See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

-   After making the required changes the production build of the project can be build using

    #### ```npm run build```

    Builds the app for production to the `build` folder.\
     It correctly bundles React in production mode and optimizes the build for the best performance.

    The build is minified and the filenames include the hashes.\
     Your app is ready to be deployed!

    See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### Project folders

-   **`public`** - contains the static files like `index.html`

-   **`src`** - contains all the `.js` files to render on the home page

```
.
├── [1.8K]  README.md
├── [4.0K]  build
│   ├── [ 962]  asset-manifest.json
│   ├── [2.1K]  index.html
│   ├── [ 492]  manifest.json
│   └── [4.0K]  static
│       ├── [4.0K]  css
│       │   ├── [561K]  2.7dce832d.chunk.css
│       │   └── [1.3M]  2.7dce832d.chunk.css.map
│       ├── [4.0K]  js
│       │   ├── [220K]  2.f726d6bd.chunk.js
│       │   ├── [1.4K]  2.f726d6bd.chunk.js.LICENSE.txt
│       │   ├── [801K]  2.f726d6bd.chunk.js.map
│       │   ├── [1.5K]  main.a01e40d6.chunk.js
│       │   ├── [3.5K]  main.a01e40d6.chunk.js.map
│       │   ├── [1.5K]  runtime-main.ff5b8ea4.js
│       │   └── [8.1K]  runtime-main.ff5b8ea4.js.map
│       └── [4.0K]  media
│           ├── [ 53K]  brand-icons.278156e4.woff2
│           ├── [ 96K]  brand-icons.65a2fb6d.ttf
│           ├── [496K]  brand-icons.6729d297.svg
│           ├── [ 62K]  brand-icons.cac87dc0.woff
│           ├── [ 96K]  brand-icons.d68fa3e6.eot
│           ├── [ 27K]  flags.99f63ae7.png
│           ├── [ 39K]  icons.38c6d8ba.woff2
│           ├── [ 49K]  icons.425399f8.woff
│           ├── [382K]  icons.62d9dae4.svg
│           ├── [104K]  icons.a01e3f2d.eot
│           ├── [103K]  icons.c656b8ca.ttf
│           ├── [ 30K]  outline-icons.53671035.ttf
│           ├── [ 12K]  outline-icons.687a4990.woff2
│           ├── [ 30K]  outline-icons.752905fa.eot
│           ├── [105K]  outline-icons.9c4845b4.svg
│           └── [ 14K]  outline-icons.ddae9b1b.woff
├── [4.0K]  images
│   └── [632K]  Home.PNG
├── [1.5M]  package-lock.json
├── [ 968]  package.json
├── [4.0K]  public
│   ├── [ 700]  index.html
│   └── [ 492]  manifest.json
└── [4.0K]  src
    ├── [2.3K]  App.js
    └── [ 189]  index.js
```

--- 

## Project Image

![Home Page](Home.PNG)
Home Page

---

## Server side project setup

### Steps to successfully run this project

-   Clone the github repository

    #### ```git clone https://github.com/VVB2/symbl.ai-server```

-   Change into the directory

    #### ```cd symbl.ai-server-main```

-   Install all the depenedencies using

    #### ```npm install```

-   To start a development server use

    #### ```npm run dev```

    Changes made to the **server** folder will be automatically reflected using this command

-   To start a production server use

    #### ```npm start```

### Project folders

-   **`data.json`** - contains the `.json` file to send all Peanut Butter Jelly Sandwich data to [Symbl.ai-client](https://github.com/VVB2/symbl.ai-client)
-   **`server.js`** - contains all the **API** endpoints.
-   **`steps.json`** - contains the `.json` file to send the steps of Peanut Butter Jelly Sandwich data to [Symbl.ai-client](https://github.com/VVB2/symbl.ai-client)
-   **`client.js`** - contains the `.js` file which implements API calls using **JavaScript**
-   **`client.py`** - contains the `.py` file which implements API calls using **Python**

```
.
├── [  20]  Procfile
├── [3.9K]  data.json
├── [125K]  package-lock.json
├── [ 408]  package.json
├── [ 512]  server.js
└── [3.2K]  steps.json
```

---
