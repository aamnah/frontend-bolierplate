# Frontend Boilerplate

- Has a Parcel based boilerplate in place
- Has my usual `_fonts` and `_variables` sass files
- Assumes that you have Parcel installed globally

```bash
# yarn global add parcel-bundler
npm i -g parcel-bundler
git clone git@github.com:aamnah/frontend-bolierplate.git
cd frontend-bolierplate
npm install
```

```
src/
├── img/
├── index.html
├── js/
│   └── main.js
└── scss/
    ├── _fonts.scss
    ├── main.scss
    └── _variables.scss

3 directories, 5 files
```

## Dev
- `npm run dev`
- Runs Parcel on default port: `http://localhost:1234`
- You can find out your computer's IP with `ifconfig` to get the external URL to view on other devices, it'd be something like `http://192.168.10.5:1234`
- Live reloads the browser on all devices, foregoing teh need for Browsersync.

## Build
- `npm run build`
- output dir: `prod`
- Minifies and compiles stuff for release