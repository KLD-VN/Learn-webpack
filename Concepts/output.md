# Output

* **output** (đầu ra) -> nơi webpack bundle ra các file
* Mặc định -> **./dist/main.js**

```js
const path = require('path');

module.exports = {
   entry: './path/to/my/entry/file.js',
   output: {
      path: path.resolve(__dirname, 'dist'),
      filename: 'my_file_bundle.js',
   },
};
```

* **path** -> vị trí gói được chuyển tới
* **filename** -> tên gói