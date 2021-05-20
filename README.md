# LargeOpenApi

建立容易維護的 OPEN API文件

範例由 https://github.com/OAI/OpenAPI-Specification/blob/main/examples/v3.0/petstore.yaml 嘗試拆分

## 步驟

```
npm install
```

執行以下指令可以將多個檔案包裝成一個OPENAPI檔案，將於 `_build` 資料夾中產生 `openapi.yaml` 完整檔案。

```
npm run build
```

## 產生基本的 redoc Html 

```
npm run prod
```