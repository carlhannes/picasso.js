---
title: Sequential color
---

## Usage

```js
picasso.chart({
  data,
  element,
  settings: {
    scales: {
      myScale: {
        type: 'sequential-color',
        min: 0,
        max: 100,
        range: ['red', 'blue']
      }
    },
    components: [
      {
        type: 'some-component',
        scale: 'myScale'
      }
    ]
  }
});
```

## API Referance

### Settings

```js
{
  type: 'sequential-color', // Optional
  range: [  // Optional
    : /* string */,
  ],
  invert: false, // Invert range // Optional
  min: /* number */, // Set an explicit minimum value // Optional
  max: /* number */, // Set an explicit maximum value // Optional
}
```

