# mojibu

> Simple button library using [bootstrap](https://getbootstrap.com/docs/4.0/components/buttons/) button styling.

[![NPM](https://img.shields.io/npm/v/mojibu.svg)](https://www.npmjs.com/package/mojibu) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
npm install --save mojibu
```

## Usage

```jsx
import React, { Component } from 'react'

import { Button } from 'mojibu'
import 'mojibu/dist/index.css'

class Example extends Component {
  render() {
    return (
      <>
        <Button type='btnPrimary' />
        <Button type='btnSecondary' />
        <Button type='btnSuccess' />
        <Button type='btnInfo' />
        <Button type='btnWarning' />
        <Button type='btnDanger' />
        <Button type='btnLight' />
        <Button type='btnDark' />
        <Button type='btnLink' />
      </>
    )
  }
}
```

## License

MIT © [ugurkiymetli](https://github.com/ugurkiymetli)
