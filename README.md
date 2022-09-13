# AERIE Monaco Editor Customizations

This repository contains the source code for a typescript worker that provides additional EDSL diagnostics
for the AERIE Command EDSL

# Build

First update the typescript version so it is built into the worker (should be done whenever updating the typescript version)
```bash
npm run import-typescript
```

Then build the worker
```bash
npm run build
```

# Publish

Ensure the version is updated appropriately first

```bash
npm publish
```
