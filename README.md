<!--
👋 Hello! As Nova users browse the extensions library, a good README can help them understand what your extension does, how it works, and what setup or configuration it may require.

Not every extension will need every item described below. Use your best judgement when deciding which parts to keep to provide the best experience for your new users.

💡 Quick Tip! As you edit this README template, you can preview your changes by selecting **Extensions → Activate Project as Extension**, opening the Extension Library, and selecting "AstroNova" in the sidebar.

Let's get started!
-->

<!--
🎈 Include a brief description of the features your extension provides. For example:
-->

**AstroNova** provides integration with the **[Astro static site builder](https://astro.build)**, utilizing the [Astro language server](https://www.npmjs.com/package/@astrojs/language-server) tools.

<!--
🎈 It can also be helpful to include a screenshot or GIF showing your extension in action:
-->

![](https://nova.app/images/en/dark/editor.png)

## Requirements

<!--
🎈 If your extension depends on external processes or tools that users will need to have, it's helpful to list those and provide links to their installers:
-->

AstroNova requires some additional tools to be installed on your Mac:

- [Node.js 16.13.0](https://nodejs.org) and NPM 8.4.1 or newer

<!--
✨ Providing tips, tricks, or other guides for installing or configuring external dependencies can go a long way toward helping your users have a good setup experience:
-->

> To install the current stable version of Node, click the "Recommended for Most Users" button to begin the download. When that completes, double-click the **.pkg** installer to begin installation.

## Usage

AstroNova runs any time you open a local project, automatically lints all open .astro files, then reports errors and warnings in Nova's **Issues** sidebar and the editor gutter:

![](https://nova.app/images/en/dark/tools/sidebars.png)

### Configuration

<!--
🎈 If your extension offers global- or workspace-scoped preferences, consider pointing users toward those settings. For example:
-->

To configure global preferences, open **Extensions → Extension Library...** then select AstroNova's **Preferences** tab.

You can also configure preferences on a per-project basis in **Project → Project Settings...**