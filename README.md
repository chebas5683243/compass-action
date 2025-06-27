# Compass Metric Reporter Action

This GitHub Action posts a metric value to Atlassian Compass.

## Inputs

- `metricSourceId`: The metric source ID from Compass
- `value`: The numeric value to report
- `email`: Your Atlassian email
- `apiToken`: Your Atlassian API token

## Example

```yaml
- uses: chebas5683243/compass-action@v1
  with:
    metricSourceId: ${{ secrets.METRIC_ID }}
    value: 5
    email: ${{ secrets.COMPASS_EMAIL }}
    apiToken: ${{ secrets.COMPASS_TOKEN }}
```
