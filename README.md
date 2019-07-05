修复node-sqlite3在electron中运行的bug

安装
```
npm install sqlite3-electron 
cd ./node_modules/sqlite3-electron
HOME=~/.electron-gyp node-gyp rebuild --target=your-electron-version --arch=x64 --dist-url=https://electronjs.org/headers
```

文档同[node-sqlite3](https://github.com/mapbox/node-sqlite3)