# drink-order
## 平台简介

包含外卖与自取、商品管理(多规格sku)、店铺管理、云小票打印、图片素材库、订单管理、积分兑换(积分+金额)、充值、优惠券、充值、多门店、微信公众号、商家中心、提前预约、桌面扫码点餐(单人或者多人协同)、收银台(支持扫码枪与扫码盒子收款)、会员卡、桌台点餐等功能，更适合企业或个人二次开发.



## 项目说明
    

```
    yshop-drink.             Java工程
    yshop-drink-vue          后台前端vue3工程
    yshop-drink-uniapp-vue3  移动端uniapp(vue3版本)工程，支持微信小程序、h5
```


## 本地快速启动
  ##### 1、环境要求
   
    ```
        jdk17
        mysql8
        redis6+
        node16+
        maven3.8+
    
    ```
  ##### 2、开发工具
   
    ```
        idea
        vscode
        hbuilder
    
    ```
 ##### 3、后端启动


-   3.1 请使用idea打开Java工程，自动会安装依赖
-   3.2 创建数据库且导入工程目录下sql/yixiang-drink.sql 文件
-   3.3 找到项目下的yshop-server 的yml,修改数据库相关信息和redis相关信息，如图：
     ![输入图片说明](assets/image.png)
-   3.4 工程下输入
    ``` 
    mvn clean install package '-Dmaven.test.skip=true
    ```
-   3.5 启动项目，如图
    ![输入图片说明](assets/1702544439568.jpg)

##### 4、后台vue启动

 - 4.1 vscode 打开vue工程，在目录下输入命令: 
    ``` 
    pnpm install
    ```
 - 4.2 配置api如图
 ![输入图片说明](assets/1702544756749.jpg)
 - 4.3 本地启动:
    ```
     npm run dev
    ```

##### 5 移动端uniapp启动
 
  - 5.1 hbuilder导入uniapp项目，
  - 5.2 配置api
   ![输入图片说明](assets/WX20231214-171211@2x.png)
  - 5.3 配置小程序
   ![输入图片说明](assets/WX20231214-171416@2x.png)
  - 5.4 运行小程序
    ![输入图片说明](assets/WX20231214-171514@2x.png)
  - 5.5 运行h5
   
    ![输入图片说明](assets/1702545370856.jpg)
-



## 小程序截图

| ![输入图片说明](assets/1000.jpg)| ![输入图片说明](assets/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20260309235851_552_6.png) |
|---|---|
| ![输入图片说明](assets/200000.jpg)  |  ![输入图片说明](assets/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20260309235857_557_6.png) |
| ![输入图片说明](assets/10003.jpg)  | ![输入图片说明](assets/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20260309235856_556_6.png) | 

## 后台截图

| ![输入图片说明](assets/3000.png) | 
|---|---|
| ![输入图片说明](assets/3001.png)  | 
| ![输入图片说明](assets/3002.png)  | 
| ![输入图片说明](assets/3003.png)  | ![输入图片说明](assets/3004.png) |
![输入图片说明](assets/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20260310000501_559_6.png)
![输入图片说明](assets/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20260310001028_564_6.png)
![输入图片说明](assets/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20260310001057_565_6.png)


## 技术栈
- Spring Boot3

- Spring Security oauth2

- MyBatis

- MyBatisPlus

- Redis

- lombok

- hutool

- Vue3

- Element UI

- uniapp(vue3)
