# Figma embeds in your Bit Components

Example components with Figma embeds so Designers and Developers can work side by side with live updates to desings, the possibility to zoom in and out and clicking the link to take you right to the Figma file so you can properly inspect the Deign.

<img width="1917" alt="CleanShot 2021-08-19 at 18 01 24@2x" src="https://user-images.githubusercontent.com/13063165/130102696-e6986fb3-79fa-423c-9519-ab4e63e47ed8.png">

Components are hosted [here](https://bit.dev/learn-bit-react/figma-example)

If you would like to import(clone) the project to take it for a test run make sure you have [bit installed](https://harmony-docs.bit.dev/getting-started/installing-bit).

```bash
npm i -g @teambit/bvm
bvm install
```

Note: You can also use git to clone this project and test it out. However if you want to use this as a base project that you can then export to your own remote scope use the method below. 

Create an empty workspace. (skip this step if you want to import the components into an already created workspace)

```bash
bit new react my-workspace --empty
```

Use the `bit import` command to import all components into your workspace. This is similar to cloning a project.

```bash
bit import "learn-bit-react.figma-example/*"
```

Copy the `workspace.jsonc` file from this repository and replace the one in your workspace. This will ensure you have the correct dependencies and environments set.

Start the dev server

```bash
bit start
```

You should now see all the ecommerce components on [localhost:3000](http://localhost:3000)

Learn more about [how to embed Figma into your Dev environment](https://harmony-docs.bit.dev/tutorials/embed-figma-in-bit) and how to [create your own Figma Component](https://harmony-docs.bit.dev/tutorials/embed-figma-in-bit#create-a-figma-component).
