## 运行于阿里云函数hostloc自动签到刷积分脚本

创建函数, 选择事件函数, 请求处理程序 `index.handler`, 运行时间300秒

打包本仓库全部上传

修改 `index.py` 的91行, 将 `username` 和 `password` 改为你的用户名和密码

设置触发，选择定时触发

选择云函数地区最好是境外