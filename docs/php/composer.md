## Getting Started

composer安装：https://packagist.org/

## 常用命令

##### 查看全局镜像

> composer config -l -g

##### 查看当前项目镜像

> composer config -l

##### 取消全局镜像

> composer config -g --unset repos.packagist

##### 取消当前项目镜像

> composer config --unset repos.packagist

##### 版本升级

> composer self-update --preview

##### 清除缓存命令

> composer clear-cache

##### 将 Composer 镜像设置为阿里云镜像，加速国内下载速度

> composer config -g repo.packagist composer https://mirrors.aliyun.com/composer

##### 华为云镜像

> composer config -g repo.packagist composer https://repo.huaweicloud.com/repository/php/


reference:
> composer 中文文档：https://learnku.com/docs/composer/2018  
> LX2 PHP 扩展包实战教程：https://learnku.com/courses/creating-package