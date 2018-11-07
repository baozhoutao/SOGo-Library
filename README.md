
[SOGo如何自定义HTML？](https://sogo.nu/support/faq/how-to-customize-the-html.html)

# 项目创建过程

## 创建文件夹
`mkdir -p ~sogo/GNUstep/Library/SOGo/Templates/MainUI`

## 拷贝template文件
cp /usr/lib*/GNUstep/SOGo/Templates/UIxTopnavToolbar.wox     ~sogo/GNUstep/Library/SOGo/Templates/

## 拷贝资源文件
cp -r /usr/lib*/GNUstep/SOGo/MailerUI.SOGo/     ~sogo/GNUstep/Library/SOGo/MailerUI.SOGo/

# 使用方式

## clone 项目到 ~sogo/GNUstep 文件夹下 `https://github.com/baozhoutao/SOGo-Library.git Library`

## 重启SOGo 服务 `systemctl restart sogod.service`