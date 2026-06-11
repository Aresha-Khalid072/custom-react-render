# Custom React Renderer

A vanilla JavaScript implementation of React's `render` function — no React needed!

## How It Works

A plain JS object (type, props, children) gets converted into a real DOM element:

```javascript
const reactElement = {
    type: 'a',
    props: { href: 'https://google.com', target: '_blank' },
    children: "Click me to visit page"
}
```

`customRender()` reads this object and injects it into the DOM dynamically.

## Run

Just open `index.html` in a browser — no installs required!

## Goal

Understand how React handles elements under the hood.