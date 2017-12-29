reactors-flex
===

# Install

```bash
npm install --save reactors-flex
// OR
yarn add reactors-flex
```

# Usage

```jsx
import * as Flex from 'reactors-flex';
import {Text} from 'reactors'

<Flex.Column>
  <Text>I am in a column</Text>
  <Text>I am in a column too</Text>
  <Flex.Row>
    <Text>I am in a row</Text>
    <Text>I am in a row too</Text>
  </Flex.Row>
</Flex.Column>
```

# Components

```jsx
import {Column, Row, Stack} from 'reactors-flex';
// Column and Stack are aliases to each other
```

# Props

All props are optional.

- `flex: number | string`
- `flexAround: true`
- `flexBetween: true`
- `flexCenter: true`
- `flexCenterHorizontal: true` alias `flexCenterY`
- `flexCenterVertical: true` alias `flexCenterX`
- `flexDown: true`
- `flexGrow: true | number`
- `flexReverse: true`
- `flexRight: true`
- `flexStretch: true`
- `flexUp: true`
- `flexWrap: true | false | 'around' | 'between' | 'center' | 'down' | 'stretch' | 'up'`
