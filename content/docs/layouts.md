---
title: Layouts
---

We have 3 layouts in this project:

## Default

This is the layout that is used if no layout is defined. This contains the `nuxt` tag which loads the page components and the `footer`and `header`. This is the main tempalte that we use across most pages

## Basic

This is the layout that is used for the pages that have a basic look and feel. This contains the `header` component and `nuxt` tag which loads the page components and the `footer`. This is the tempalte that we use for simple pages such as privacy, cookies etc. If we want to use this layout in our page we must add the following:

```js
export default {
  layout: 'basic',
}
```

## Error

Athough not technically a layout this needs to live in the layout folder. We then call the components we want to show when a 404 is found. Remember to add which layout you want the error page to use.

```js
export default {
  layout: 'basic',
}
```
