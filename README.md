# ht-solo-bors
ht solo bors.

Public
### Install
```bash
yarn add ht-solo-bors
npm i --save ht-solo-bors
```

### Register Global Component
```js
import { createApp } from 'vue';
import App from './App.vue'
import QrReader from 'ht-solo-bors';

const app = createApp(App);
app.use(QrReader);
app.mount('#app')
```

### Register Local Component
```js
import { QrStream, QrCapture, QrDropzone } from 'ht-solo-bors';

export default {
  components: {
    QrStream,
    QrCapture,
    QrDropzone
  },
};
```

## Project setup
```
yarn
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
