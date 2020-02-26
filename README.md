<p align="center">
  <img src="./resetti.png" alt="Mr. Resetti">
</p>

<h1 align="center">resetti.css</h1>

<p align="center">A tiny, modern CSS reset with great defaults | <b><a href="https://unpkg.com/resetti/demo.html" title="See a demo">Demo</a></b></p>

<hr />

## 📦 Install

You can install Resetti as a package:

```sh
yarn add resetti
```

Or use it from a CDN:

```html
<link rel="stylesheet" href="https://unpkg.com/resetti/resetti.min.css" />
```

## 🎨 Customize

Resetti allows you to set some sane default values using CSS variables:

- `--root-font-size`: set the root font size of the document, changing the value of the `rem` unit

You can set these values like this:

```
:root {
  --root-font-size: 18px;
}
```

Note that Resetti doesn't make any assumptions about your project. If you don't set these values, they will remain undefined. 

## 🛠 Extras

Resetti sets a few CSS variables on the `:root` scope that may be useful in your project:

- `--system-fonts`: system font stack
