#### ClusterEngineV4.0_RCE
浪潮集群管理ClusterEngine是专门为浪潮天梭系列HPC产品定制的一款作业管理软件。在web登录界面，通过精心构造后的命令，可执行任意命令。造成命令执行漏洞

#### 漏洞详情

此工具利用的是 http://ip/sysShell 处的命令执行漏洞，登录处的命令执行漏洞暂时不适用，后续考虑会增加登录处的exp

#### 工具使用

只需要输入http://ip:port 即可进行漏洞检测
![image](https://user-images.githubusercontent.com/46400438/114844618-8d75c080-9e0d-11eb-9b9c-443789279c23.png)

执行命令则需要同时输入url、nodeid、cmd可以
![image](https://user-images.githubusercontent.com/46400438/114844841-c3b34000-9e0d-11eb-910f-fd38e5f1077b.png)
![image](https://user-images.githubusercontent.com/46400438/114844905-d594e300-9e0d-11eb-9856-69794d18822c.png)
