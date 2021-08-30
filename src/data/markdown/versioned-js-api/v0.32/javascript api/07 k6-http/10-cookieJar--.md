---
title: 'cookieJar()'
slug: '/v0.32/javascript-api/k6-http/cookiejar-method'
description: 'Get active HTTP Cookie jar.'
excerpt: 'Get active HTTP Cookie jar.'
---

Get the active cookie jar.

| Type                                                 | Description         |
| ---------------------------------------------------- | ------------------- |
| [CookieJar](/v0.32/javascript-api/k6-http/cookiejar) | A CookieJar object. |

### Example

<CodeGroup labels={[]}>

```javascript
import http from 'k6/http';

export default function () {
  let jar = http.cookieJar();
}
```

</CodeGroup>