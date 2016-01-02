---
layout: defaulte
title: 第二
---
第二篇正文

```javascript
function exists(pth, mode) {
  try {
    fs.accessSync(pth, mode);
    return true;
  } catch (e) {
    return false;
  }
}
```

 ```ruby
  # ...ruby code
  ```

<p>{{ page.title }}</p>  
<p>{{ site.title }}</p>