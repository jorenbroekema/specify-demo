# Button

Button CSS component

```js script
import '~/sd-output/variables.css';
import '../src/button.css';
```

## Demos

### Primary

Primary button

```js preview-story
export const base = () => `
  <button class="btn">Click me!</button>
`;
```

Disabled

```js preview-story
export const disabled = () =>
  ` <button class="btn" disabled>Click me!</button> `;
```

### Outline

```js preview-story
export const outline = () => ` <button class="btn" outline>Click me!</button> `;
```
