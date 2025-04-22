# UseVCharts

Features:

- Bundle with [tsup](https://github.com/egoist/tsup)
- Test with [vitest](https://vitest.dev)

# Usage

### 安装

```bash
pnpm add @oiij/v-charts
```

### 使用

```vue
<script setup lang="ts">
import type { ISpec } from '@oiij/v-charts'
import { useVCharts } from '@oiij/v-charts'
import { ref } from 'vue'
const option: ISpec = ref({
  // ...
})
const { domRef } = useVCharts(option)
</script>

<template>
  <div ref="domRef" style="width: 100%; height: 100%;" />
</template>
```

## License

MIT
