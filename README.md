# @rickbrown/use-clipboard

> A custom React hook to simplify using local clipboard

[![NPM](https://img.shields.io/npm/v/@rickbrown/use-clipboard.svg)](https://www.npmjs.com/package/@rickbrown/use-clipboard) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
npm install --save @rickbrown/use-clipboard
```

## Usage

```jsx
import React, { Component } from 'react'

import { useMyHook } from '@rickbrown/use-clipboard'

const Example = () => {
  const example = useMyHook()
  return (
    <div>{example}</div>
  )
}
```

## License

MIT © [RickBr0wn](https://github.com/RickBr0wn)

---

This hook is created using [create-react-hook](https://github.com/hermanya/create-react-hook).
