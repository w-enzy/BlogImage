# 1.配置Github

## 1.1 创建新仓库

![75d13b9e-4785-489c-b855-8fde4a0ed482](file:///C:/Users/34977/Pictures/Typedown/75d13b9e-4785-489c-b855-8fde4a0ed482.png)

- 设置为public，否则无法正常访问

- 勾选add a readme file

![3d357307-808b-43f5-b823-4f7c1c5cdc63](file:///C:/Users/34977/Pictures/Typedown/3d357307-808b-43f5-b823-4f7c1c5cdc63.png)

## 1.2 生成token

- 在个人主页setting里找到developer settings

- 用于picGo访问

![d6e5e008-9abe-4516-9cc9-2eaa494b0c14](file:///C:/Users/34977/Pictures/Typedown/d6e5e008-9abe-4516-9cc9-2eaa494b0c14.png)

- beta是用不上的，classic就够了

![15b94b12-6b12-4fdf-a84e-316203a311f7](file:///C:/Users/34977/Pictures/Typedown/15b94b12-6b12-4fdf-a84e-316203a311f7.png)

- 填写完note，修改expiration（默认30d，作者改成了无限期）

- 勾选repo

![6e3d0c41-f4ba-4a23-8636-8b64fe3b16be](file:///C:/Users/34977/Pictures/Typedown/6e3d0c41-f4ba-4a23-8636-8b64fe3b16be.png)

- token生成

- 只显示一次，记得单独保存

![51e12325-415c-4193-8d89-db65274d0eed](file:///C:/Users/34977/Pictures/Typedown/51e12325-415c-4193-8d89-db65274d0eed.png)

GitHub配置完成，接下来是picGo的相关设置

# 2.配置picGo

## 2.1 下载picGo

- 在[GitHub页面](https://github.com/Molunerfinn/PicGo/releases)找到适配windows64位且正式发布的安装包

- .dmg，for mac

- .exe，for Windows
  
  - 默认32bit
  
  - x64，for 64位

![b8e6bfd3-8303-4c29-9794-2af7136dd5e2](file:///C:/Users/34977/Pictures/Typedown/b8e6bfd3-8303-4c29-9794-2af7136dd5e2.png)

## 2.2 配置参数

- 仓库名是刚才在GitHub上建立的新仓库

- 分支名默认为master（2020.10.1以后GitHub不再使用此默认分支名），需要修改为main

- 填写token

- 存储路径：填写后会将图片存储在库内的img文件夹下

- 自定义域名格式：https://cdn.jsdelivr.net/gh/[github用户名]/[仓库名]@main
  
  - 原自定义域名为：https://raw.githubusercontent.com/[username]/[仓库名]
  
  - 访问图片很慢
  
  - 故修改为jsdelivr作为cdn加速

![6f456310-6c23-4fc3-a6ca-ee83f94d4572](file:///C:/Users/34977/Pictures/Typedown/6f456310-6c23-4fc3-a6ca-ee83f94d4572.png)

picGo配置完成

- 接下来就可以到主页面上传图片了

![d9e22dbf-d649-40af-bc82-035665565f59](file:///C:/Users/34977/Pictures/Typedown/d9e22dbf-d649-40af-bc82-035665565f59.png)
