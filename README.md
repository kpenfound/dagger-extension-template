# dagger-extension-template
A dagger extension for extension-template operations

## Supported Commands
- Anything extension-template can do!

## TODO
- TODO

## Include this in your cloak.yaml
```yaml
  - git:
      remote: git@github.com:kpenfound/dagger-extension-template.git
      ref: main
      path: cloak.yaml
```

## Example
```gql
{
  host {
    workdir {
      read {
        extension-template() {
          id
        }
      }
    }
  }
}
```
