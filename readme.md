[![Circle CI](https://circleci.com/gh/segmentio/deku-checklist.svg?style=svg&circle-token=undefined)](https://circleci.com/gh/segmentio/deku-checklist)

# deku-checklist

A checklist component for Deku.

![Demo](https://cldup.com/ESh2T4sQ81.png)

## Usage

```js
import { List, Item } from 'deku-checklist';

function render() {
  return (
    <List>
      <Item isChecked text="foo" />
      <Item text="bar" />
    </List>
  );
}
```
