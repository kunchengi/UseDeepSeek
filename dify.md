# Dify案例

## 生成专题论文工作流

### 准备工作

* 右上角头像->设置->模型供应商->选择深度求索、硅基流动、OpenAI-API-compatible->安装
* 进入[deepSeek开发平台] (https://platform.deepseek.com/api_keys)
    * 点击左侧API Keys->创建API Key->输入名称->点击创建->复制API Key
* 在dify模型供应商的深度求索中点击设置
    * 输入API Key
    * 输入https://api.deepseek.com/v1
    * 点击保存
* 返回dify首页->点击上方的工具
    * 安装google->点击图标->去授权->如何获取->点击API Key->复制API Key->粘贴回dify->点击保存
    * 安装firecawl->点击图标->去授权->如何获取->点击API Key->复制API Key->粘贴回dify->点击保存
    * 电子邮件->点击图标->去授权qq邮箱
        * 进入qq邮箱->设置->账号->POP3/SMTP服务->开启POP3/SMTP服务->点击开启->继续获取授权码->微信扫码->点击已发送->复制授权码
        * 输入邮箱
        * 密码: 复制的授权码
        * 加密方式选择STARTTLS加密
        * 端口选择587
        *服务器地址选择smtp.qq.com
        * 点击保存
* 返回dify首页->点击上方的工作室->创建空白应用->工作流
    * 应用名称 ：生成深度的专题论文
    * 应用描述 ：根据用户信息生成某个方向的深度专题论文
    * 点击创建