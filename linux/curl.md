# CURL

-a/–append 上传文件时，附加到目标文件
-b/–cookie <name=string/file> cookie字符串或文件读取位置
-c/–cookie-jar <file> 操作结束后把cookie写入到这个文件中
-C/–continue-at <offset> 断点续转
-d/–data <data> HTTP POST方式传送数据
-D/–dump-header <file> 把header信息写入到该文件中
-G/–get 以get的方式来发送数据
-h/–help 帮助
-w/–write-out [format]输出完成后
-e/–referer 来源网址
-E/–cert <cert[:passwd]> 客户端证书文件和密码 (SSL)
-f/–fail 连接失败时不显示http错误
–ftp-create-dirs 如果远程目录不存在，创建远程目录
-F/–form <name=content> 模拟http表单提交数据
-form-string <name=string> 模拟http表单提交数据
-u/–user <user[:password]>设置服务器的用户和密码
-s/–silent静音模式。不输出任何东西
-S/–show-error 显示错误
-T/–upload-file <file> 上传文件
-U/–proxy-user <user[:password]>设置代理用户名和密码
-A/–user-agent 设置用户代理发送给服务器
-i/–include 输出时包括protocol头信息
-I/–head 只显示protocol头信息
-o/–output 把输出写到该文件中
-O/–remote-name 把输出写到该文件中，保留远程文件的文件名
-p/–proxytunnel 使用HTTP代理
-m/–max-time <seconds> 设置最大传输时间
-N/–no-buffer 禁用缓冲输出
-l/–list-only 列出ftp目录下的文件名称
-R/–remote-time 在本地生成文件时，保留远程文件时间
-v/–verbose
-V/–version 显示版本信息


[curl详解常用示例](http://blog.csdn.net/chen8238065/article/details/53304300)
