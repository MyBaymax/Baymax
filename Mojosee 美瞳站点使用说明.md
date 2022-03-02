# Mojosee 美瞳站点使用说明

## 置顶链接

### 1、将系列模版设置为toplink模版

**<span style="color:red;">注意：想要使用置顶链接的系列其产品总数量最大值为50</span>**

![image-20220210155247519](https://raw.githubusercontent.com/MyBaymax/assets/master/img/image-20220210155247519.png)

### 2、设置置顶链接

#### 置顶连接格式

| key     | 说明                      | value                                         |
| ------- | ------------------------- | --------------------------------------------- |
| handles | 指定要置顶的产品          | el：`产品1handle`,`产品2handle`,`产品3handle` |
| page    | 当前页码（可选，默认为1） | el: 1                                         |

/collections/`系列handle`?handles=`产品1handle`,`产品2handle`,`产品3handle`

例子：https://mojosee.com/collections/top-link?handles=gf10,mojosee-angel-ice-angel-drops-blue-colored-contact-lenses,mojosee-aurora-grey-colored-contact-lenses

**[如何查看handle](https://shopify.dev/api/liquid/objects/handle)**
<<<<<<< Updated upstream
=======



## 男瞳退回女瞳站方法（删除男瞳cookie）

### 1、打开开发者工具

按 F12、或者如下图片选择打开 开发着工具

![image-20220302124541359](https://raw.githubusercontent.com/MyBaymax/assets/master/img/image-20220302124541359.png)



#### 2、删除男瞳cookie

1、在开发工具中选择 控制台/console(标记1) 界面

2、在 控制台 > （标记2）处输入下方命令后按回车

```javascript
setCookie('cookie_mojo_mens', '', 0)
```

![image-20220302124719098](https://raw.githubusercontent.com/MyBaymax/assets/master/img/image-20220302124719098.png)



### 3、关闭当前页面，打开mojosee女瞳的链接，即可访问女瞳，如首页
>>>>>>> Stashed changes
