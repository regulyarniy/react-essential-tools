# `useFirstMountState`

Hook that returns `true` if component is just mounted (on first render) and `false` otherwise.

## Example

```jsx
import { useFirstMountState } from 'react-essential-tools';

const Demo = () => {
  const isFirstMount = useFirstMountState();
  const update = useUpdate();

  return (
    <div>
      <span>This component is just mounted: {isFirstMount ? 'YES' : 'NO'}</span>
      <br />
      <button onClick={update}>re-render</button>
    </div>
  );
};
```