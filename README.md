# 前言

自学vue以后，打算在公司推vue，所以就把公司后台管理系统的部分业务拿出来用vue重构，既然都写了索性就放上来吧，和大家共同探讨。

此项目共 14 个页面，涉及登录、客户管理和编辑、报关单管理和修改等等。

数据是通过nodejs开发的后端接口提供的真实数据，需先下载并启动后端项目以获取数据，

__注：此项目纯属个人瞎搞__




## 技术栈
vue2 + vuex + vue-router + webpack + ES6/7 + fetch



# 项目运行

#### 注意：由于涉及大量的 ES6/7 等新属性，nodejs 必须是 6.0 以上版本 ，node 7 是先行版，有可能会出问题，建议使用 node 6 稳定版

```
git clone https://github.com/Brass-neck/xbn_member-admin.git

cd xbn_admin

npm install

```

### 编译环境
```
npm run dev

访问 http://localhost:8110
```


### 线上版本
```
npm run build

生成的xbn文件夹放在服务器即可正常访问
```




# 说明

>  本项目主要用于熟悉如何使用 vue2 开发项目

>  如果对您有帮助，您可以点右上角 "Star" 支持一下 谢谢！ ^_^

>  或者您可以 "follow" 一下，我会不断开源更多的有趣的项目

>  开发环境 WebStorm 11.0.2  Chrome 56  nodejs 6.10.0

```
