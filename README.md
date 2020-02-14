# gatsby-plugin-emotion

Provide support for using the css-in-js library
[Emotion](https://github.com/emotion-js/emotion) including server side
rendering. Uses the [@emotion/babel-preset-css-prop](https://emotion.sh/docs/@emotion/babel-preset-css-prop).

This plugin is based on and adapted from the [gatsby-plugin-emotion](https://github.com/gatsbyjs/gatsby/tree/master/packages/gatsby-plugin-emotion) code.

**This plugin supports Emotion v10+**

## Install

```shell
npm install --save gatsby-plugin-emotion-css @emotion/core @emotion/css
```

## How to use

Add the plugin to your `gatsby-config.js`.

```js
module.exports = {
	plugins: [
		{
			resolve: `gatsby-plugin-emotion-css`,
			options: {
				// Accepts all options defined by `@emotion/babel-preset-css-prop` plugin.
			},
		},
	],
};
```
