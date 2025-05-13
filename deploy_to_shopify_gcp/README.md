# deploy_to_shopify_gcp action

This action deploys the Shopify service

## Inputs

| Name | Description | Required |
| ---- | ----------- | -------- |
| service_name | service name | true |
| shopify_cli_partners_token | shopify cli partners token | true |
| commit_url | commit url | true |

## Example usage

```yaml
uses: albycom/actions/deploy_to_shopify_gcp@main
with:
  service_name: ${{ inputs.service_name }}
  shopify_cli_partners_token: ${{ secrets.SHOPIFY_CLI_PARTNERS_TOKEN }}
  commit_url: ${{ env.COMMIT_URL }}
```
