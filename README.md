# Figma Plugin Svelte

This is a base template to create a figma plugin using svelte.

The code is based on this [article](https://www.lekoarts.de/javascript/creating-a-figma-plugin-with-svelte).

Here's [the documentation](https://www.figma.com/plugin-docs/) to learn how to make figma plugins.

## Using the template

Don't forget to edit the package.json and the manifest.json to match your project's name.

You can do `pnpm dev` to watch for changes and bundle the project every time or `pnpm build` to build the project.

To use the plugin in figma, open the app and register a new plugin using the option "import plugin from manifest".

Once this is done, you should be able to use the plugin by doing:
right clik a figma file -> plugins -> development -> your-plugin
