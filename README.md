# 工具连接


[https://github.com/winsw/winsw](https://github.com/winsw/winsw)\

[https://github.com/nginx/nginx](https://github.com/nginx/nginx)\



# 参数说明
```xml
<service>
  <id>a1235698d</id> 
  <name>MyService</name>
  <description>我的服务描述</description>
  <executable>serviceexe</executable>
  <arguments>-c</arguments>
  <log mode="roll"></log>
</service>
```
### id -- 唯一Id 必须
### name -- 显示在服务中的名字
### description -- 显示在服务中的描述
### executable -- 执行的 exe 文件名
### arguments -- exe 的参数
### log -- 日志

## 例子
```xml
<service>
  <id>nginx</id>
  <name>Anjoe-Service</name>
  <description>Anjoe-在线充值接口内网服务</description>
  <executable>nginx.exe</executable>
  <arguments>-c conf/nginx.conf</arguments>
</service>
```
