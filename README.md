## Installation

Tesseract.js works with a `<script>` tag via local copy or CDN, with webpack via `npm` and on Node.js with `npm/yarn`.

### CDN

```html
<!-- v4 -->
<script src="https://unpkg.com/tesseract.js@4.0.0/dist/tesseract.min.js"></script>
```

After including the script the `Tesseract` variable will be globally available.

### Node.js

**Requires Node.js v14 or higher**

```shell
# For latest version
npm install tesseract.js
yarn add tesseract.js

# For old versions
npm install tesseract.js@3.0.3
yarn add tesseract.js@3.0.3
```

## Documentation

- [Examples](./docs/examples.md)
- [Image Format](./docs/image-format.md)
- [API](./docs/api.md)
- [Local Installation](./docs/local-installation.md)
- [FAQ](./docs/faq.md)

## Use tesseract.js the way you like!

- Offline Version: https://github.com/jeromewu/tesseract.js-offline
- Electron Version: https://github.com/jeromewu/tesseract.js-electron
- Custom Traineddata: https://github.com/jeromewu/tesseract.js-custom-traineddata
- Chrome Extension #1: https://github.com/jeromewu/tesseract.js-chrome-extension
- Chrome Extension #2: https://github.com/fxnoob/image-to-text
- Firefox Extension: https://github.com/gnonio/korporize
- With Vue: https://github.com/jeromewu/tesseract.js-vue-app
- With Angular: https://github.com/jeromewu/tesseract.js-angular-app
- With React: https://github.com/jeromewu/tesseract.js-react-app
- Typescript: https://github.com/jeromewu/tesseract.js-typescript
- Video Real-time Recognition: https://github.com/jeromewu/tesseract.js-video

## Contributing

### Development

To run a development copy of Tesseract.js do the following:

```shell
# First we clone the repository
git clone https://github.com/naptha/tesseract.js.git
cd tesseract.js

# Then we install the dependencies
npm install

# And finally we start the development server
npm start
```

The development server will be available at http://localhost:3000/examples/browser/demo.html in your favorite browser.
It will automatically rebuild `tesseract.dev.js` and `worker.dev.js` when you change files in the **src** folder.

### Online Setup with a single Click

You can use Gitpod(A free online VS Code like IDE) for contributing. With a single click it will launch a ready to code workspace with the build & start scripts already in process and within a few seconds it will spin up the dev server so that you can start contributing straight away without wasting any time.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/naptha/tesseract.js/blob/master/examples/browser/demo.html)

### Building Static Files

To build the compiled static files just execute the following:

```shell
npm run build
```

This will output the files into the `dist` directory.
