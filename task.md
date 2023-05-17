## Bastion-Host

执行：
```
chmod 400 labsuser.pem
ssh -i "labsuser.pem" ec2-user@xxx

ssh-add -K labsuser.pem
ssh -A ec2-user@xxxx
```


## PHP部署教程
- 教程：https://blog.csdn.net/weixin_45118728/article/details/100070437


## 子网信息
Public Subnet 2   subnet-058c42465951f6d76
Public Subnet 1   subnet-01cfb9f6d591bea48

Private Subnet 2  subnet-07c6d5b12f6ec3b8d
Private Subnet 1  subnet-018547b30cecc6731


# RDS
创建在private subnet中。
Database：exampledb
user: admin
PW：

SubnetGroup: us-east-1a  us-east-1b


# ALB

# System Manger
Paramter Store

/example/endpoint
/example/username
/example/password
/example/database

