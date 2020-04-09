# 项目标题
### 开发配置
```html
<!-- 添加cms_id，「0001」频道ID依据创建项目时的频道名,「xxxx」为发布器对应频道新建专题名，需要发布到发布器的项目，该项必填 -->
<meta name="cms_id" content="0001xxxx" />
<!-- 公共导航头 -->
<!--#include virtual="/special/ntes_common_model/nte_commonnav2019.html" -->
<!-- 频道导航头 -->
<!--#include virtual="/special/sp/post_1603_header.html" -->
```
```
多页面只需在src/pages/新建文件夹，内部文件依然保留index命名。
```

### 用户配置
```js
// gulpfile.js
const account = require('/Users/xxx/code/openID') // 配置路径
```

### Project setup
```bash
# 安装依赖
$ npm i

# 开启本地服务
$ npm run dev

# 打包（上传前需先打包）
$ npm run build

# 上传静态资源
$ gulp upload

# 发布到cms
$ gulp publish

# 清空本地缓存文件，使所有文件重新上传
# （默认每次上传只上传增量文件）
$ gulp clear
```
