# OpenAPI Generator Example

Generate api files via [openapi-generator](https://openapi-generator.tech/).

### OpenAPI Source

https://raw.githubusercontent.com/openapitools/openapi-generator/master/modules/openapi-generator/src/test/resources/3_0/petstore.yaml

### Command

```shell
openapi-generator generate -g typescript-redux-query -o out -i https://raw.githubusercontent.com/openapitools/openapi-generator/master/modules/openapi-generator/src/test/resources/3_0/petstore.yaml
```
