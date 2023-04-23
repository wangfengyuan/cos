# cos
图片存储服务

# 搭建流程
1、cloudflare 上选择pages标签，导入github仓库并部署
![](https://cos.codefe.top/images/cloudflare_add_git.png)

2、绑定自定义域名
上一步完成后会生成一个默认域名，在自定义域名中添加自己域名，并在域名管理服务商添加一条CNAME记录将自己域名指向生成的默认域名
![](https://cos.codefe.top/images/cloudflare_custom_cos_domain.png)

比如： https://cos.codefe.top 指向 https://cos-367.pages.dev
