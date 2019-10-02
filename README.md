﻿<!--prettier-ignore-start-->

# @smotaal/vscode-frictionless-theme
## SMotaal's Frictionless Theme for Visual Studio Code

<!--prettier-ignore-end-->

Frictionless light and dark themes that work for me personally.

<center>
<img width=100% src="./assets/2019-10-02-frictionless-theme.png">
</center>

> **Note**: This effort is a constant work-in-progress, it evolves with time, and is never really finished — see the [CHANGELOG](./CHANGELOG.md) for updates.

## Light/Dark

This theme defines light and dark variants using a fine-tuned alpha/blending approach. This eliminates the need to actually coerce actual color values and instead (with only a subtle runtime cost) simply rely on the renderer to blend the colors nicely.

The benefits of doing it this way is to avoid hard-coded values showing up where not expected. The pitfalls (aside from slight overhead) is the need to sometimes still override certain elements when the layering does not yield the expected results.

## Tokens

**Stubs** include invariant markup aspects:

- Best rendered using neutrals with high contrast and low saturation.

  > **Recommendations**: Overrides for `light`/`dark` themes.

- Usually applies longer body text.

- Sometimes applies to dominant identifiers — ie unambiguous subject(s).

**Marks** includes marked markup aspects:

- Best rendered using symbolic colors with high contrast and saturation.

- Usually applies to comments, errors, warnings, diffs… etc.

**Hints** includes styled markup aspects:

- Best rendered using the implied formatting and/or colors.

- Usually applies to bold/italics, headings… etc.

## Icons

This theme borrows from [PKief/vscode-material-icon-theme](https://github.com/PKief/vscode-material-icon-theme) and continues to find ways to simplify things while retaining the absolutely pleasing aspects of this work.
