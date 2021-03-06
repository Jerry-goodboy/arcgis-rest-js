# ArcGIS Rest JS / Vue JS Demo

This demo uses VueJS along with Webpack and Babel and implements OAuth2 using
the `arcgis-rest-js` libraries.

## Running this demo

1. Like all the other demo apps, run `npm run bootstrap` in the root directory.
1. Register a new application using [https://developers.arcgis.com](https://developers.arcgis.com).
1. Add a redirect URL of `http://localhost:8080` to your new app.
1. Either copy the `.env.template` file and rename it to `.env` and hard-code your clientid or enter your clientid in the prompt when the application is launched.
1. Run `npm start` to spin up the development server.
1. Visit [http://localhost:8080](http://localhost:8080).

## Build

1. Run `npm run build` to bundle up the application using[Webpack](https://webpack.js.org/).
