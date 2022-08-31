# Use modular CSS with tailwind

Add a prefix in _tailwind.config.js_

```
module.exports = {
  ...
  prefix: 'tw-',
};
```

Import all module css files into _global.css_, eg:

```
@tailwind base;
@tailwind components;
@tailwind utilities;

@import '../components/my-component/my-component.module.css';
```
