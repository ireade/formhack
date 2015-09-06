# FormHack

FormHack is a hackable [SASS](http://sass-lang.com)-based css form reset. Although there are standard css resets for forms out there, I wanted to created one that I could easily customize for any site, without having to worry about cross-browser compatibility and differences. 

FormHack works by providing a few variables that allow you to change some common attributes such as border-radius, input height/width, and colours. By changing these attributes, you will get a beautiful form that is consistent across all major browsers. I have also organised the code in a way that is (hopefully) easy for you to edit if you want to alter more than the given settings.

If you have any questions or suggestions for how I can make this better, tweet me at [@ireaderinokun](https://twitter.com/ireaderinokun).


## Getting Started

You can use any of the following methods to start using Formhack -

Install with [Bower](http://bower.io/)

```
bower install formhack
```

Clone this repository

```
git clone https://github.com/ireade/formhack.git
```


## Config

This is the default config and the variables you can change -

```
// Font
$fh-font-family: 'Raleway', sans-serif;
$fh-font-size: 16px;
$fh-font-color: rgb(40, 40, 40);

// Borders
$fh-border-radius: 5px;
$fh-border-width: 1px;
$fh-border-style: solid;
$fh-border-color: rgb(200, 200, 200);

// Inputs, Textareas, Select, Option
$fh-input-height: 40px;
$fh-input-width: 100%;
$fh-input-max-width: 400px;
$fh-input-bg-color: #fff;
$fh-focus-bg-color: rgb(220, 220, 220);
$fh-focus-border-color: $fh-border-color;
$fh-focus-font-color: $fh-font-color;

// Select Vendor Styling
$fh-allow-vendor-styling: true;

// Fieldset & Legend Styling
$fh-fieldset-bare: false;

// Buttons & Input Submits
$fh-button-height: 40px;
$fh-button-width: 100%;
$fh-button-max-width: 200px;
$fh-button-font-color: $fh-font-color;
$fh-button-bg-color: $fh-focus-bg-color;
$fh-button-hover-bg-color: $fh-border-color;
$fh-button-hover-font-color: $fh-font-color;

// Layout
$fh-centered: false;
$fh-display: block;
```

### Variables

Here is an explanation of what some of the variables control.

Variable | Description
---------|-------------
`$fh-allow-vendor-styling` | Boolean. Specifies whether you want the `select` element to have the different browser styling
`$fh-fieldset-bare` | Boolean. Specifies whether you want the `fieldset` element to be styled or bare.
`$fh-centered` | Boolean. Specifies whether the elements should be centered
`$fh-display` | String. Specifies what value you want the `display` css property to be set to


