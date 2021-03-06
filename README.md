# Frontend Boilerplate

- Has a Parcel based boilerplate in place
- Has my usual `_reset`, `_fonts` and `_variables` sass partials
- Assumes that you have Parcel installed globally

```bash
# yarn global add parcel-bundler
npm i -g parcel-bundler

git clone git@github.com:aamnah/frontend-bolierplate.git
cd frontend-bolierplate

# yarn install
npm install
```

```
src
├── index.html
├── js
│   └── main.js
└── scss
    ├── _fonts.scss
    ├── main.scss
    ├── _reset.scss
    └── _variables.scss

2 directories, 6 files
```

## Dev
- `npm run dev`
- Runs Parcel on default port: `http://localhost:1234`
- You can find out your computer's IP with `ifconfig` to get the external URL to view on other devices, it'd be something like `http://192.168.10.5:1234`
- Live reloads the browser on all devices, foregoing the need for Browsersync.

## Build
- `npm run build`
- output dir: `dist`
- Minifies and compiles stuff for release
