# Plugin Naming Conventions

## Overview

Consistent plugin names are helpful for organizing and searching plugins, and for finding published plugins on npm.

This page lists our standard plugin naming conventions. If your plugin doesn't fit in any of the categories, use the generic plugin naming format at the end of the page.

We recommend you add the suggested tags in your `package.json` to make it easier to find your plugin on npm.

## Plugin types

### Field

A field plugin publishes a single custom field.

Loading a field plugin registers a new field type that can be used in all Blockly workspaces on the page.

read_more Read more about [creating custom fields](/guides/create-custom-blocks/fields/customizing-fields/overview).

| First Party        | Third Party       | Example                                                                                        | Suggested tags            |
| ------------------ | ----------------- | ---------------------------------------------------------------------------------------------- | ------------------------- |
| `@blockly/field-*` | `blockly-field-*` | [`@blockly/field-slider`](https://google.github.io/blockly-samples/plugins/field-slider/test/) | `blockly-plugin`, `field` |

### Theme

A theme plugin publishes a single Blockly theme.

Loading a theme plugin defines a new theme that can then be used in all Blockly workspaces on the page.

read_more Read more about [themes](/guides/configure/web/themes).

| First Party        | Third Party       | Example                                                                        | Suggested tags            |
| ------------------ | ----------------- | ------------------------------------------------------------------------------ | ------------------------- |
| `@blockly/theme-*` | `blockly-theme-*` | [`@blockly/theme-modern`](https://www.npmjs.com/package/@blockly/theme-modern) | `blockly-plugin`, `theme` |

### Block

A block plugin publishes one or more block definitions.

Loading a block plugin defines those blocks for all Blockly workspaces on the page.

read_more Read more about [creating custom blocks](/guides/create-custom-blocks/define-blocks).

| First Party           | Third Party          | Example                                                                                                 | Suggested tags                      |
| --------------------- | -------------------- | ------------------------------------------------------------------------------------------------------- | ----------------------------------- |
| `@blockly/block(s)-*` | `blockly-block(s)-*` | [`@blockly/blocks-plus-minus`](https://google.github.io/blockly-samples/plugins/block-plus-minus/test/) | `blockly-plugin`, `block`, `blocks` |

### Block Extension

A block extension plugin publishes one or more block extensions, which can be used to programmatically share behaviour between blocks.

Loading a block extension plugin registers the extensions for use on all Blockly workspaces on the page.

read_more Read more about [extensions](/guides/create-custom-blocks/extensions#extensions).

| First Party            | Third Party           | Example  | Suggested tags                     |
| ---------------------- | --------------------- | -------- | ---------------------------------- |
| `@blockly/extension-*` | `blockly-extension-*` | None yet | `blockly-plugin`,`block-extension` |

### Workspace

A workspace plugin adds behaviour to a single workspace.

Loading a workspace plugin does nothing until it is initialized on a Blockly workspace.

| First Party            | Third Party           | Example  | Suggested tags               |
| ---------------------- | --------------------- | -------- | ---------------------------- |
| `@blockly/workspace-*` | `blockly-workspace-*` | None yet | `blockly-plugin`,`workspace` |

### Generic plugin

This is the most general plugin type. Use this naming convention if your plugin doesn't meet the requirements of any other plugin type.

| First Party         | Third Party        | Example                                                                                 | Suggested tags   |
| ------------------- | ------------------ | --------------------------------------------------------------------------------------- | ---------------- |
| `@blockly/plugin-*` | `blockly-plugin-*` | [`@blockly/plugin-modal`](https://google.github.io/blockly-samples/plugins/modal/test/) | `blockly-plugin` |
