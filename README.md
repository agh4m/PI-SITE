# Website for PI

This is a static website hosted in Github pages to detail the progress in our Project DiSA (Digitaly Signed Archive)

### Development

This website uses TailwindCSS for its styling, this can be compiled with

```sh
npx tailwindcss -i ./css/input.css -o ./docs/output.css --watch
```

after tailwindcss has been installed with


```sh
npm i -D tailwindcss
```

While developing it might be useful to serve the website localy using an utility such as [serve](https://www.npmjs.com/package/serve) which can be started with

```sh
npx serve
```

This will serve the website on `http://localhost:3000`

