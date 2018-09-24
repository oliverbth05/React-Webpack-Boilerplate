## Boilerplate code for creating a webpack project with react, babel and css modules
* Transpiles ES5+ Javascript as well as JSX.
* Implements CSS Modules

### Development

To start the dev-server with hot-reloading: run ```npm run start```.

By default, the sever will run on ```localhost:8080```.

### Production

To concatenate the modules into a servable bundle, run ```npm run build``` from the root folder.

You can serve ```index.html``` and ```bundle.js``` from the newly created ```dist``` folder.

For production, the app uses a separate webpack config file called ```webpack.prod.config.js``` that uses the Uglify plugin and creates a source map for browser debugging.

