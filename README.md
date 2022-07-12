# code-generation

docker run --rm -v "${PWD}:/local" openapitools/openapi-generator-cli generate -i https://raw.githubusercontent.com/terra-rebels/code-generation/main/terra-lcd-swagger-openapi-3-0.yaml -g go -o /local/build/go

# swagger 2.0 to openapi 3.0 converter
https://mermade.org.uk/openapi-converter

# openapi-generator
https://github.com/OpenAPITools/openapi-generator