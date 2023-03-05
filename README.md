# **Quick Media**

To all the **Frontend Developers** out there, We have came up with the solution
called "**Quick Media**" to write the media queries in more faster and convinient way than usual. As we all know, Maintaining the responsiveness of website, Sometimes we need the help of media queries. And **Quick Media** will surely help you out to achieve the same.

## Features

---

There are three keys this extension mainly provides.

1. min-media
1. max-media
1. between-media
1. retina-media

The main purpose of this keys is _Specificity_.

## Overview

---

> min-media

```css
@media only screen and (min-width: 991px) {
  ...;
}
```

> max-media

```css
@media only screen and (max-width: 991px) {
  ...;
}
```

> between-media

Above key will generate following css code

```css
@media only screen and (max-width: 991px) and (min-width: 768px) {
  ...;
}
```

> retina-media

Above key will generate following css code

```css
@media only screen and (min-width: 768px) {
  @media (min-device-pixel-ratio: 2), (min-resolution: 192dpi), (min-resolution: 2dppx) {
    ...;
  }
}
```

## Installation

---

You can simply [install Quick Media](https://marketplace.visualstudio.com/items?itemName=YK911.quickmedia) on your machine.

Or

Open the extension tab in VS Code and search for **Quick Media**.
