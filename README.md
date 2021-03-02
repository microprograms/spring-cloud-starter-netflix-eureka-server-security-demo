# Eureka 注册中心（密码验证）

- `默认端口：` 8761
- `默认账号：` eureka
- `默认密码：` password
- `默认注册地址：` http://eureka:password@localhost:8761/eureka/

#### 编译打包

```shell
sh bin/package.sh
```

#### 启动

```shell
sh bin/start.sh
```

#### 查看控制台输出

```shell
tail -f server.nohup.out
```

#### 停止

```shell
sh bin/stop.sh
```
