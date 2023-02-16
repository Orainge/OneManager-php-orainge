# onemanager-php-orainge

- onemanager-php的自定义修改版本
- Fork from: [https://github.com/qkqpttgf/OneManager-php](https://github.com/qkqpttgf/OneManager-php)

- [官方readme](readme_official.md)  

# 修改后的特性

- 新增自定义主题`nginx-orainge.html`
- 管理页登录参数由`?login={参数值}`为`?toLogin={参数值}`。
- 新增系统变量`guestuploadtoken`，设置后，公共图床上传接口需要新增token后才可以上传，即在请求接口时，携带请求头`auth:{你设置的值}`。
- Picgo 插件 [Orainge/picgo-plugin-onemanager-orainge](https://github.com/Orainge/picgo-plugin-onemanager-orainge) 已经支持上传接口设置token。

