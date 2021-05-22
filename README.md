# @srdante/tailwind-base

A Tailwind CSS plugin that provides a css standard colors/font sizes for headers, paragraph and body tags.


## Installation

Install the plugin from npm:

```sh
# Using npm
npm install @srdante/tailwind-base

# Using Yarn
yarn add @srdante/tailwind-base
```

Then add the plugin to your `tailwind.config.js` file:

```js
// tailwind.config.js
module.exports = {
  theme: {
    // ...
  },
  plugins: [
    require('@srdante/tailwind-base'),
    // ...
  ],
}
```