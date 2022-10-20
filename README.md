# Return change-list action

This action helps you to return changelist for users

## Outputs

### `Get changed files on github`

- Will return folder information by default
- Will only return file information if explicitly mentioned true
- Will filter according to keyword mentioned in `keyword`
  - Note: Will return all files containing the mentioned keyword. (JavaScript includes)

## Example usage

```yaml
uses: actions/return-changelist
with:
  keyword: "-spa"
  folder: true
  file: true
```