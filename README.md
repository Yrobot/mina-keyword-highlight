# mina-keyword-highlight

`mina-keyword-highlight`，一个方便、轻量的 **小程序** 关键词高亮组件  
零依赖，小而精。

## change log：

1. 2021.01.26 init package

## 组件参数

- text: String, 需要处理的字符串
- keyword: String, 关键词
- color: String, 高亮词颜色

## demo 展示

1. demo1：支持各类文字样式继承: 对齐，fontsize，fontweight，单行省略，多行省略，颜色等等   

   | ![](https://636f-could-test-1258393788.tcb.qcloud.la/README/mina-keyword-highlight-demo1.jpeg) | ![](https://636f-could-test-1258393788.tcb.qcloud.la/QRCode/pages-mina-keyword-highlight-demo1-index_qrcode%3D1.jpg) |
   | -------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |

[查看demo代码](https://github.com/Yrobot/mina-tools-client/tree/master/miniprogram/pages/mina-keyword-highlight/demo1)
<!-- 2. demo2：支持动态高亮
   | ![](https://636f-could-test-1258393788.tcb.qcloud.la/README/touchmove.gif) | ![](https://636f-could-test-1258393788.tcb.qcloud.la/QRCode/pages-mina-keyword-highlight-demo1-index_qrcode%3D1.jpg) |
   | -------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | -->

## 使用方法

**大致可以分为 4 步：**

1. npm 安装 mina-keyword-highlight，开发工具构建 npm
2. json 引入 mina-keyword-highlight 组件
3. wxml 使用组件

### 命令行

`npm install mina-keyword-highlight `  
安装完成后，开发工具构建 npm

### \*.json

```json
{
  "usingComponents": {
    "keyword-highlight": "mina-keyword-highlight"
  }
}
```

### \*.wxml

在 wxml 上利用 keyword-highlight 处理渲染逻辑

```html
<keyword-highlight class="text" text="{{text}}" keyword="{{keyword}}" color="#FF4A56"> </keyword-highlight>
```

---

以上简单几步即可使用 mina-keyword-highlight
