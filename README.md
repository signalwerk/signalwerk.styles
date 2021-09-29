# Signalwerk Style

[![Build Status](https://ci.signalwerk.ch/api/badges/signalwerk/signalwerk.styles/status.svg)](https://ci.signalwerk.ch/signalwerk/signalwerk.styles)

## Versioned

```html
<link rel="preconnect" href="https://fonts.signalwerk.ch" />
<link
  href="https://fonts.signalwerk.ch/css/latest/family=Open+Sans:ital,wght@0,300..800;1,300..800.css"
  rel="stylesheet"
/>
<link
  rel="stylesheet"
  href="https://rawcdn.githack.com/signalwerk/signalwerk.styles/885bd9d/styles/main.critical.css"
  media="all"
/>
<link
  rel="preload"
  as="style"
  onload="this.onload=null;this.rel='stylesheet'"
  href="https://rawcdn.githack.com/signalwerk/signalwerk.styles/885bd9d/styles/main.rest.css"
  media="all"
/>
```

## Fonts from Google

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300..800;1,300..800&display=swap" rel="stylesheet">
```
## Usage

```html
<link rel="preconnect" href="https://fonts.signalwerk.ch" />
<link
  href="https://fonts.signalwerk.ch/css/latest/family=Open+Sans:ital,wght@0,300..800;1,300..800.css"
  rel="stylesheet"
/>
<link
  rel="stylesheet"
  href="https://raw.githack.com/signalwerk/signalwerk.styles/gh-pages/styles/main.critical.css"
  media="all"
/>
<link
  rel="preload"
  as="style"
  onload="this.onload=null;this.rel='stylesheet'"
  href="https://raw.githack.com/signalwerk/signalwerk.styles/gh-pages/styles/main.rest.css"
  media="all"
/>
```

## ToDo
* No ligatures in Code/pre
Set Build with [static site generator webpack plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin).
