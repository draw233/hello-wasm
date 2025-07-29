## rust 使用wasm

### 方式一

```shell
wasm-pack build --target web
python -m http.server
```

### 方式二 

```shell
wasm-pack build --target bundler

cd site 
npm install ../pkg

npm run serve

```