# `useMotion`

Hook that uses device's acceleration sensor to track its motions.

## Example

```jsx
import React from 'react';
import { useMotion } from 'react-essential-tools';

const Demo = () => {
  const state = useMotion();

  return (
    <pre>
      {JSON.stringify(state, null, 2)}
    </pre>
  );
};
```