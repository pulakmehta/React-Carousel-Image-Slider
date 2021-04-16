### Installation

### Basic Usage

```tsx
import React from "react";
import useSlider from "use-slider";

const App = () => {
  const { ref } = useSlider();
  const list = [1, 2, 3, 4, 5];
  return (
    <div ref={ref}>
      {list.map(item => (
        <div key={item}>{item}</div>
      ))}
    </div>
  );
};
```

