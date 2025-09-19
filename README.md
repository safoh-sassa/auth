
# SignInDialog ES Module

This project exports a React component `SignInDialog` as an ES module, suitable for CDN import in other React apps.

## Usage

After deployment (e.g., to Vercel), you can import the component in another React app like this:

```js
import { SignInDialog } from "https://auth-module-js.vercel.app/dist/SignInDialog.js";
// or
import { SignInDialog } from "https://auth-module-js.vercel.app/SignInDialog.js";
```

## Component

The `SignInDialog` renders:

```jsx
<div>My ES Module</div>
```

## Build

```
npm run build
```

The output is in the `dist/` folder as `SignInDialog.js` (ES module format).

## External dependencies
- `react`
- `react-dom`

These must be available in the consuming app.
