---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@microsoft/rush-lib](./rush-lib.md) &gt; [CommonVersionsConfiguration](./rush-lib.commonversionsconfiguration.md) &gt; [preferredVersions](./rush-lib.commonversionsconfiguration.preferredversions.md)

## CommonVersionsConfiguration.preferredVersions property

A table that specifies a "preferred version" for a given NPM package. This feature is typically used to hold back an indirect dependency to a specific older version, or to reduce duplication of indirect dependencies.

<b>Signature:</b>

```typescript
get preferredVersions(): Map<string, string>;
```

## Remarks

The "preferredVersions" value can be any SemVer range specifier (e.g. `~1.2.3` ). Rush injects these values into the "dependencies" field of the top-level common/temp/package.json, which influences how the package manager will calculate versions. The specific effect depends on your package manager. Generally it will have no effect on an incompatible or already constrained SemVer range. If you are using PNPM, similar effects can be achieved using the pnpmfile.js hook. See the Rush documentation for more details.

After modifying this field, it's recommended to run `rush update --full` so that the package manager will recalculate all version selections.
