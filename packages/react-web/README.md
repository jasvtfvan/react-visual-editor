# bricks-web

> 功能组件集 web 版

## Usage

```jsx
import { LegoProvider } from 'brickd-core';
import {BrickDesign,BrickTree} from 'brickd';
import {BrickPreview} from 'bricks-web'


const App = () => (
  <LegoProvider config={{...}}>
<div>
    <BrickPreview componentsCategory={...}/>
    <BrickDesign />
<BrickTree/>
</div>
  </LegoProvider>

);
```
