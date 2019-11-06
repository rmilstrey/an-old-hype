# An old Hyper Jedi

[![CircleCI](https://circleci.com/gh/erikmueller/an-old-hype.svg?style=svg)](https://circleci.com/gh/erikmueller/an-old-hype)

> Hyper theme inspired by a galaxy far far away...

Based on [An Old Hype](https://github.com/erikmueller/an-old-hype) - a splendid hyper theme by Erik Mueller

## Usage

Open the `~/.hyper.js` file (on Mac you can simply press `Cmd`+`,`) and go to the plugins section and add


```js
plugins: ['an-old-hype']
```

to the plugins array.

## Features

* __Transparent background__ - Opacity can be customized
* __Visible divider__ - lets you see where tiled terminals begin and end
* __6 theme styles to choose from__
    * `vader`
    * `yoda`
    * `threePO`
    * `r2`
    * `luke` (default)
    * `falcon`

## Settings

You can customize the __background opacity__ and the __style__ as well as the __active tab marker__.
To do so, provide a `themeSettings` object in the `config` property of your `~/.hyper.js`:

```js

config: {
    ...
    // Customize the theme
    themeSettings: {
        // Do not make background transparent (default is 0.6)
        opacity: 1,
        // Switch from luke's orange uniform to master yoda (check the available styles above)
        style: 'yoda',
        // Change the character that mars a tab active
        tabActiveMarker: '💁'
    },
    ...
}
```
