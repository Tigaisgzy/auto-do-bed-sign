>
>**[doSignIn AND goToBed](#dosignin-and-gotobed)**

# auto-do-bed-sign

    对于不需要的时间段，可直接注释掉对应的yaml文件
    doSignIn是签到
    gotobed是查寝
    定时任务时间要修改在 .github/workflows/doSignIn.yaml 或 gotobed.yaml中修改
    如若使用的是QQ邮箱，第一次请检查是否被当做垃圾邮件，是的话，请将邮件标记为非垃圾邮件

## 变量在仓库的Settings --> Secrets中配置

## [学工平台](https://ids.gzist.edu.cn/lyuapServer/login)
### 首先进入学工平台，点击登录，找到账号密码登录

![img.png](gzlg助手/img/Snipaste_2025-10-30_23-28-02.png)
### 无顺序要求，需要按照将每个参数一个个的添加到Repository secrets中

    USERNAME # 上面学工平台的账号
    PASSWORD # 上面学工平台的密码
    EMAIL_ADDRESS # 结果发送邮箱地址
    TOKEN # 打码平台密钥
    # 出现二次验证的情况需要配置以下两个变量 在学工系统--》安全中心--》密保
    PRINCIPAL # 密保问题
    CREDENTIAL # 密保答案

![img.png](gzlg助手/img/img.png)

## 自动打码 注册地址 免费300积分

[云码](https://console.jfbym.com/register/TG66434)

## 具体教程:

1. 先fork仓库
   ![img.png](gzlg助手/img/img4.png)
2. 在仓库的Settings --> Secrets中配置变量
   ![img_1.png](gzlg助手/img/img_1.png)
   ![img_2.png](gzlg助手/img/img_2.png)
3. 配置定时任务

4. 配置成功后，在仓库的Actions中查看运行情况
![img.png](gzlg助手/img/Snipaste_2025-10-30_23-30-31.png)

5. 效果图

![img.png](gzlg助手/img/img5.png)
![img.png](gzlg助手/img/img6.png)
