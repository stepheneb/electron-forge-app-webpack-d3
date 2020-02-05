Initial conditions:
```
node: v12.14.1
npm: 6.13.4
```

Install more development dependencies:
```
npm install -g yarn
npm install -g @electron-forge/cli
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
electron-forge make
```
This generates a platform-specific executable in the `out` directory.

Running the Windows executable:
```
> .\out\electron-forge-app-webpack-d3-win32-x64\electron-forge-app-webpack-d3.exe
```

Running the MacOS app:
```
$ open out/electron-forge-app-webpack-d3-darwin-x64/electron-forge-app-webpack-d3.app
```


Initial creation:
```
$ npx create-electron-app electron-forge-app-webpack-d3 --template=webpack
$ cd electron-forge-app-webpack-d3
$ npm install && npm start
```
