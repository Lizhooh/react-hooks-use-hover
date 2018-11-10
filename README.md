
## react-hooks-use-hover
react hook like css hover.

> Note: This is using the new [React Hooks API Proposal](https://reactjs.org/docs/hooks-intro.html) which is subject to change until React 16.7 final.
> You'll need to install react, react-dom, etc at ^16.7.0-alpha.0

### Install

```bash
npm install react-hooks-use-hover
npm install react@^16.7.0-alpha.0 react-dom@^16.7.0-alpha.0
```

### Usage

```js
import React from 'react';
import useBind from 'react-hooks-use-hover';

function App() {
    const [hoverRef, isHovered] = useHover();

    return (
        <div ref={hoverRef}>
        {isHovered ? '😁' : '☹️'}
        </div>
    );
}
```
