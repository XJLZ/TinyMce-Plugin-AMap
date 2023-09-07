# TinyMce-Plugin-AMap
TinyMce富文本编辑器插入高德地图插件

# 使用
## 获取代码
1. 在tinymce的plugins文件夹下创建名为gdmap的文件夹
2. 下载仓库的代码到gdmap下
## 添加到插件列表
1. 引入插件，例如：
   ```
    plugins: {
      type: [String, Array],
      default:
        "gdmap print preview"
   }
   ```
3. 添加图标， 例如：
   ```
   toolbar: {
      type: [String, Array],
      default:
        "gdmap undo redo"
   }
   ```
   

