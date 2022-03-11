---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/heft-webpack4-plugin](./heft-webpack4-plugin.md) &gt; [IWebpackBundleSubstageProperties](./heft-webpack4-plugin.iwebpackbundlesubstageproperties.md)

## IWebpackBundleSubstageProperties interface

<b>Signature:</b>

```typescript
export interface IWebpackBundleSubstageProperties extends IBundleSubstageProperties
```

<b>Extends:</b> [IBundleSubstageProperties](./heft.ibundlesubstageproperties.md)

## Properties

| Property                                                                                                 | Type                                               | Description                                                                                                                                                                                                                                             |
| -------------------------------------------------------------------------------------------------------- | -------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [webpackConfiguration?](./heft-webpack4-plugin.iwebpackbundlesubstageproperties.webpackconfiguration.md) | webpack.Configuration \| webpack.Configuration\[\] | <i>(Optional)</i> The configuration used by the Webpack plugin. This must be populated for Webpack to run. If webpackConfigFilePath is specified, this will be populated automatically with the exports of the config file referenced in that property. |