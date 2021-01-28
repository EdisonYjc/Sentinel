# Sentinel
Sentinel AOP Demo with dashboard
## 运行sentinel-dashboard-1.8.0.jar包
java -Dserver.port=8080 -Dcsp.sentinel.dashboard.server=localhost:8080 -Dproject.name=sentinel-dashboard -jar sentinel-dashboard-1.8.0.jar
## 登录账号和密码
账号：sentinel
密码：sentinel
## jvm参数配置
-Dcsp.sentinel.dashboard.server=localhost:8080
-Dproject.name=DemoApplication
