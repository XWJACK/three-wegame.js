# Three.js for WeGame

- Three.js (r100)
- WeChat debug base library (1.9.94)

## OrbitControls

- Add three required
- Fix dispatchEvent is not a function

```js
/// Import
import * as THREE from 'three'
require('controls/OrbitControls')

/// Usage
const control = new THREE.OrbitControls(camera)
```


