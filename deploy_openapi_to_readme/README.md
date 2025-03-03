# Upload OpenAPI docker action

This action uploads an OpenAPI specification file to README.io using the [README.io CLI](https://github.com/readmeio/rdme/tree/v9).

## Inputs

### `openapi_spec_path`

**Required** The path to the OpenAPI specification file.

### `application_id`

**Required** The application ID  on README.io to upload the OpenAPI specification file to.

## Example usage
```yaml
uses: albycom/actions/deploy_openapi_to_readme@main
with:
  openapi_spec_path: 'https://api-preprod.alby.com/apps/openapi.json'
  application_id: '12345678-1234-1234-1234-123456789012'
```
