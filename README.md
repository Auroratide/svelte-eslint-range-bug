# Eslint crash with typescript and svelte

**Error:**
```
TypeError: Cannot read properties of null (reading 'range')
Occurred while linting /Users/auroratide/Projects/tmp/svelte-eslint-range-bug/src/Root.svelte:1
Rule: "indent"
```

**What to do:**
```
pnpm install
pnpm lint
```

* Seems to only happen with Typescript
* Only happens if the `indent` rule is set in eslint config
