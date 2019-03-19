# Renovate Config
Package containing kube-js' configs for renovate.

### Usage
1. Create a "renovate.json" file in the root of your repository 
### Renovate Config Example
```json
{
  "extends": ["@kube-js:webapp"]
}
```

or

```json
{
  "extends": ["@kube-js:lib"]
}
```

2. Enable Renovate for your repository using [Renovate's Github integration](https://github.com/apps/renovate/installations/new).

Credits: 
[ryansmith94](https://github.com/ryansmith94)
