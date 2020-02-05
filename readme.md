Initial conditions:
```
node: v12.14.1
npm: 6.13.4
```

Install more development dependencies:
```
npm install -g yarn
```

To run:
```
git clone https://github.com/stepheneb/electron-forge-app-webpack-d3.git
cd electron-forge-app-webpack-d3
npm install
npm start
```

Build application using cli:
```
npm run make
```
This generates a platform-specific executable in the `out` directory.

Run the Windows executable:
```
> .\out\electron-forge-d3-win32-x64\electron-forge-d3.exe
```

Run the MacOS app:
```
$ open out/electron-forge-d3-darwin-x64/electron-forge-d3.app
```

Initial creation:
```
$ npx create-electron-app electron-forge-app-webpack-d3 --template=webpack
$ cd electron-forge-app-webpack-d3
$ npm install && npm start
```
