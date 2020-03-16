# real-world-vue

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).


## Real World Vue
Real world vue tutorial


# Install Vue CLI 3

Start by installing Vue CLI 3 (Command Line Interface) using node.js and npm with entering
```
npm i -g @vue/cli
```

Now that it is installed we will create the project with the terminal using
```
vue create real-world-vue
```

With the down arrow select manually select features and select with the down arrow and enter with the space bar: "Babel", "Router", "Vuex" and "Linter / Formatter".

Choose "ESLinter + Prettier" and select "Lint on save". In the next step choose "dedicated config files" and don't save this settings for future configurations by entering "n". As last step you might be prompted to select a package manager in this case we select "npm".

Go into the folder with
```
cd real-world-vue
```

and run
```
npm run serve
```
to build the project and serve it at a local host. It will be served at the shown URL
```
Local: http://localhost:8080/
```

The project that was created by the CLI consists of several folders:

The "node_modules"-folder is where the libraries that are needed to build vue are stored. (Dependecies that are needed to build the project)

"public"- folder is where to put images and files that should not be processed through Webpack.

"src"-folder is where all application specific code goes.

"assets"-folder to store assets such as images, fonts etc.

"components"-folder is to store components and building blocks of the Vue app

"views"-folder is where the files for the different vies or pages of the app are stored.

"App.vue"-file is the root component that are all other components are nested within.

"main.js" is the file that renders the app and mounts it to the DOM.

"router.js" will be covered later

"store.js" is for Vuex

The "package-json" helps npm identify this projects and handle its dependencies.

## VSCode extention for Vue development

### Vetur

The Vetur extention highlights html and javascript code in .vue files. 

Shortcuts for Vetur:

To search for a file we want to open:
```
ctrl + p
```
Now type the files name and press enter when higlighted.



