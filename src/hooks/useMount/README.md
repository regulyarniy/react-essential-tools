# `useMount`

Hook that calls a function after the component is mounted.

## Example

```jsx
import React from 'react';
import { useMount } from 'react-essential-tools';

const Demo = () => {
  useMount(() => alert('MOUNTED'));

  return null;
};
```