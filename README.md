<img src="https://www.mintjams.jp/img/cr.svg" alt ="" width="64">

# vue-appbase
A reusable AppBase component for Vue.js 2.x used by webtop applications.

## Installation

```sh
npm install --save-dev @mintjamsinc/vue-appbase
```

## Usage

```vue
<AppBase>
  <template v-slot:menubar>
    <!-- Defines the menu content that appears at the top of your application -->
  </template>
  <!-- Defines the primary content of your application -->
</AppBase>
```

```js
import AppBase from '@mintjamsinc/vue-appbase';

export default {
  components: {
    AppBase: AppBase,
  },
}
```

## License

[MIT](https://opensource.org/licenses/MIT)

Copyright (c) 2021 MintJams Inc.