# Validate OpenAPI docker action

This action validates an OpenAPI specification file using the [README.io CLI](https://github.com/readmeio/rdme/tree/v9).

## Inputs

### `openapi_spec_path`

**Required** The path to the OpenAPI specification file.

## Example usage
```yaml
uses: albycom/actions/validate_openapi_on_readme@main
with:
  openapi_spec_path: 'https://api-preprod.alby.com/apps/openapi.json'
```
