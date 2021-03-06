
# [Common Web Codec](https://hackily.github.io/common-web-codec/app/index.html)

Encodes and decodes some of the web's most commonly used formats:
* JWT
* Base64
* Hex
* HTML
* Binary
* LZ Compression

### Use
Please visit the webapp to use. An [NPM module](https://github.com/hackily/coco) is a work in progress.


## Development
The following shows how to get started with developing on this app

1. Clone repository

  ```
  $ git clone
  ```

2. Install dependencies

  ```
  $ npm install
  ```

3. Compile project

  ```
  $ npm run build
  ```

  > Browserify and Watchify are included as developer dependencies. You do not need them globally installed. Do note that you must run them via the npm scripts, as their respective commands are not available in your environment.


4. Start static fileserver

  ```
  npm start
  ```

  > http-server is included as a developer dependency, and will create a static fileserver to serve up the app.

5. Development

  ```
  npm run watch
  ```

  > This will enable Watchify, which will watch for any changes made to any javascript files associated with ./src/scripts/startup.js and bundle them into ./app/scripts/bundle.js


