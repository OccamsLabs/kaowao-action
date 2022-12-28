# kaowao github action

This action monitors files for changes and will break the build if this happens

## Inputs

## `args`
**Required** cli arguments for the scanner
example:
`scan config.yaml`



## Example usage

```
- name: kaowao-scan
  uses: OccamsLabs/kaowao-action@v0.0.2
  with:
    args: scan kaowao.yml
```
