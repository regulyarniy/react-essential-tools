# `useUnmount`

Hook that calls a function after the component is unmounted.

## Example

```jsx
import React from 'react';
import { useUnmount } from 'react-essential-tools';

const Demo = () => {
  useUnmount(() => alert('UNMOUNTED'));

  return null;
};
```