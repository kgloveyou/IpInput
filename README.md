## IpInput

### About

IpInput component for antd.

Based on http://lizheming.github.io/Iput。

### Usage

#### basic Usage

```javascript
  import React from 'react';
  import ReactDOM from 'react-dom';
  import IpInput from 'IpInput';

  ReactDOM.render(
    <IpInput />,
    document.getElementById('app')
  );
```

### API

#### IpInput props

| name         | type                   | default | description                           |
|--------------|------------------------|---------|---------------------------------------|
| className    | String                 |         | additional css class of root dom node |
| defaultValue | String\|Array\<String\>|         | specify the default ip                |
| onChange     | Function(value:string) |         | called when input value change        |
| isError      | Function               |         | custom function to check value        |

### Example

run `npm start` and open `http://localhost:8080`

online example: https://codesandbox.io/s/a-ipinput-demo-y7vxw

### License

IpInput is released under the MIT license.
