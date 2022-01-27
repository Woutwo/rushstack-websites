---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/node-core-library](./node-core-library.md) &gt; [IExecutableResolveOptions](./node-core-library.iexecutableresolveoptions.md) &gt; [environment](./node-core-library.iexecutableresolveoptions.environment.md)

## IExecutableResolveOptions.environment property

The environment variables for the child process.

<b>Signature:</b>

```typescript
environment?: NodeJS.ProcessEnv;
```

## Remarks

If `environment` and `environmentMap` are both omitted, then `process.env` will be used. If `environment` and `environmentMap` cannot both be specified.
