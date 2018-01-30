# Install and Configure Redis on CentOS 7

### The link at the buttom shows how to install Redis on CentOS 7

#### Improved Command 

Use `redis-server &` instead of `redis-server`, so you can input commands after open redis server

Use `redis-cli --raw` instead of `redis-cli` and the results return from redis will transformed into UTF-8 format.
	
	[user@localhost ~]$ redis-cli
	XXX.X.X.X:6379> SET name 苹果
	OK
	XXX.X.X.X:6379> GET name
	"\xe8\x8b\xb9\xe6\x9e\x9c"
	XXX.X.X.X:6379> exit
	[user@localhost ~]$ redis-cli --raw
	XXX.X.X.X:6379> GET name
	苹果

[Install and Configure Redis on CentOS 7](https://github.com/northbright/Notes/blob/master/Redis/Install/Install_and_Config_Redis_on_CentOS.md)
