# Swagger

* [公式サイト](https://swagger.io/)

## swagger editor
```
docker run -d -p 80:8080 swaggerapi/swagger-editor

```

## swagger codegen
[README](https://github.com/swagger-api/swagger-codegen/blob/master/README.md)

[templatates](https://github.com/swagger-api/swagger-codegen/tree/master/modules/swagger-codegen/src/main/resources)

### ヘルプ

```
java -jar swagger-codegen-cli.jar help generate
java -jar swagger-codegen-cli-3.0.0.jar config-help -l jaxrs-spec
java -jar swagger-codegen-cli-3.0.0.jar config-help -l typescript-angular
```

### 生成例

```
java -jar swagger-codegen-cli-3.0.0.jar generate -i swagger.yaml -o ./api-clients -l typescript-angular

```