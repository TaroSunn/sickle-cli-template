# 业务组件库

## 安装和使用

```bash
// 安装
npm install lego-components --save
```

```javascript
import Lego from 'lego-components'
// 加载样式
import 'lego-components/dist/lego-components.css'

const app = createApp(App)
// 全局引入 目前包括 FinalPage, LText, LImage , Lshape三个组件
app.use(Lego)

app.mount('#app')
```
