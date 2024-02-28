# Eslint crash with typescript and svelte

```
TypeError: Cannot read properties of null (reading 'range')
Occurred while linting /Users/auroratide/Projects/tmp/svelte-eslint-range-bug/src/Root.svelte:1
Rule: "indent"
```

* Seems to only happen with Typescript
* Only happens if the `indent` rule is set in eslint config
