- # notes for each branch below:

- # 1. boilerplate-with-notes

  - # package.json
    - to build this I just created a package.json file with an eslint configuration to assist us while writing our JSX code.
    - there are also dependencies and dev dependencies used to create this app.
    - we have a babel configuration with a single preset which transpiles our JSX code to JavaScript so it can be used in modern browsers.
    - we use an npm script, "start," in order to run our application with webpack on port 3000.
  - # webpack.config.dev.js
    - configured "devtool" to be able to view our source code in ther browser.
    - used an output key to specify where our build path is for our app except note that in development mode the app is served from memory instead of the actual directory.
    - we still need to specify a file name although it is being served from memory.
    - devServer key:
    - the historyApiFallback is used in order to assist us with being able to route traffic to index.html so that later on when we use react router we can just have routing handled by our app.
    - modules object
    - for our rules we just set up the babel loader to assist with transpiling our JSX to JavaScript.
    - we also set up eslint on our source files to assist us with development.
    - we also use both style and css loaders to be able to import CSS (such as bootstrap.min.css) and eventually webpack can bundle and minify this into our final bundle.js file.
  - # src/index.js
    - The application's entry point/top component..
  - # src/components/App.js
    - The application's main component.

- #2. React with routing.

  - TBA

- #3. React with routing and redux.
  - TBA
