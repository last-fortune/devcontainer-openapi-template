## 1. 操作方法

### 1.1 Preview
```sh
redocly preview-docs src/openapi.yaml 
```

### 1.2 Validation
recdocly と openapiでバリデーションが異なるため 
```sh
openapi-generator-cli validate -i ./src/openapi.yaml 
```

### 1.3 Generate Html
```sh
bin/build
```

### 1.4 差分比較
```sh
bin/diff
```
