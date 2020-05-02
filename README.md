# dockerpackage
## 1.修改docker.repo里的包的路径,并将这个文件放到/etc/yum.repos.d/里
## 2.执行命令：createrepo -v 包的路径
## 3.执行命令安装docker:

  yum install -y yum-utils device-mapper-persistent-data  lvm2
  
  yum install docker-ce docker-ce-cli containerd.io -y
