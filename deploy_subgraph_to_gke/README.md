# deploy_subgraph_to_gke action

This action deploys a GKE subgraph to Apollo

## Inputs

| Name | Description | Required |
| ---- | ----------- | -------- |
| service_name | service name | true |
| service_stage | service stage | true |
| apollo_graph_ref | Apollo graph ref | true |
| apollo_key | Apollo API key | true |
| apollo_routing_url | Apollo routing URL | true |

## Example usage

```yaml
uses: albycom/actions/deploy_subgraph_to_gke@main
with:
  service_name: ${{ env.SERVICE_NAME }}
  service_stage: ${{ env.SERVICE_STAGE }}
  apollo_graph_ref: ${{ env.APOLLO_GRAPH_REF }}
  apollo_key: ${{ env.APOLLO_KEY }}
  apollo_routing_url: ${{ env.APOLLO_ROUTING_URL }}
```
