### Vue坏境搭建 【Windows】

```shell
#安装包下载地址:
https://nodejs.org/zh-cn/download/prebuilt-installer
 
 #查看node 版本
 node -v

 #查看npm 版本
 npm -v

#修改npm 镜像源地址：
#临时指定淘宝镜像源：
npm --registry https://registry.npm.taobao.org install express
#永久指定淘宝镜像源：
npm config set registry https://registry.npm.taobao.org
#安装 cnpm
npm install -g cnpm --registry=https://registry.npm.taobao.org
 

# 清理缓存
npm cache clean --force
# 取消ssl验证
npm config set strict-ssl false


#安装脚手架
npm i -g @vue/cli
#查看Vue版本
vue -V

```


### Vue项目搭建

```shell
#1.创建项目命令
#命令创建方式：
vue create my-project
#图形化创建
vue ui
#npm+vite
npm init vite

#安装npm依懒
npm i

#运行项目
npm run dev



```

