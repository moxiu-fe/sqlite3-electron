修复node-sqlite3在electron中运行的bug
安装
```
npm install sqlite3-electron --build-from-source --sqlite_libname=sqlcipher --sqlite=`brew --prefix` --runtime=electron --target=你的electron版本号 --dist-url=https://atom.io/download/electron
```

文档同[node-sqlite3](https://github.com/mapbox/node-sqlite3)