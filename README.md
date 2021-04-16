### Installation

#### yarn

`yarn add use-slider`

#### npm

`npm install use-slider`

#### include css

```js
import "use-slider/lib/slider.min.css";
```

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

