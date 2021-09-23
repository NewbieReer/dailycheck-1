# 使用说明

> [代码全都来自该项目](https://github.com/windiboy/BUAAAutoUpdate)

1. 打开该网页获取提交的表单信息，`https://app.buaa.edu.cn/site/buaaStudentNcov/index`；

2. 填好表格，打开控制台，进入`Network`选项卡，然后提交；

3. 找到提交的save包中的`form`，然后`view source`，内容复制保留备用；

4. 创建一个`action`，配置文件仿照着写；

5. 在`settings`中添加自己的`secret`；

   > `YOUR_NAME`：学号
   >
   > `YOUR_PWD`：密码
   >
   > `WECHAT_KEY`：[server酱](https://sct.ftqq.com/)的sendkey，用来发送打卡成功的消息
   >
   > `FORM`：第3步中保存的内容

