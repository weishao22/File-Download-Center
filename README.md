# File-Download-Center
文件下载中心

## 1. 添加新文件教程

### 1.1 修改JavaScript文件数据
在`index.html`文件中找到JavaScript的`files`数组，添加新文件对象：

```javascript
// 在files数组中添加新条目
const files = [
  // ...已有文件...
  {
    id: 9,  // 唯一ID（递增）
    name: "新文件名称.扩展名",
    type: "文件类型", // pdf/image/video/audio/archive/document
    size: "文件大小",
    date: "2025-08-10", // YYYY-MM-DD格式
    desc: "文件描述",
    url: "文件下载URL"
  }
];
```

## 1.2 文件类型对照表

文件类型	type值	图标颜色

PDF文档	pdf	红-橙渐变

图片文件	image	蓝-青渐变

视频文件	video	粉红-玫红渐变

音频文件	audio	紫色-蓝色渐变

Word文档	document	绿色-青绿渐变

压缩文件	archive	浅红-米色渐变

代码文件	code	紫色-粉红渐变

其他文件	other	蓝色-紫色渐变

