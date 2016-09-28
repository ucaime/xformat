#采集后文章格式处理

只实现了标签部分的清理,图片链接补全和替换将在后期增加

## 使用

    composer require ucaime/xformat

```
 <?php
 include vendor/autoload.php;
 Fromat::parse($html);
```