设置用户参数
arMail="jiangdouu88@126.com" arPass="jd2"

检查更新域名
arDdnsCheck "jiangdoudou.uni.me" "www"

-----------------------------------------------以下是注释-----------------------------------------------------------
arMail="jiangdouu88@126.com" //是https://www.dnspod.cn 登录的账号
arPass="jd2" //是 https://www.dnspod.cn 登录的密码
arDdnsCheck "jiangdoudou.uni.me" "www" //是你申请的域名
修改vi /etc/cront
1 * * * * root /linshi/dnspod.sh

定时每隔1小时运行目录下/linshi/ 的 dnspod.sh
