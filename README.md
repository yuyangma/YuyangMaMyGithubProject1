# YuyangMaMyGithubProject1
1.下载Git，安装Git，配置Git,通过Git Bash命令

2.注册Github账号

3.创建Github仓库（repository）,仓库名字以姓名+项目名方式命名，使用驼峰命名法

4.创建公钥私钥

	通过Git Bash $ssh-keygen –t rsa –C '邮箱地址'
	
	.ssh文件夹下id_rsa.pub复制，创建密匙
	
5.cmd——>要克隆下载的文件夹 git clone SSH密匙。

	这步有问题，多试几次

6.执行同步脚本'syn.bat',同步到Github上，也就是提交。

	以后可以直接在本页面下载该文件到你的仓库，每次修改完，点击执行bat文件同步到Github
	
	也可以在ide中进行同步，下面会介绍
	
7.idea中进行Git操作

	可以使用syn.bat进行同步，也可以使用IDEA进行操作：使用VCS下的commit提交至本地仓库，使用Git->push更新到Github远程仓库。
	
	不是idea操作的文件，就不会被提交至Github，仍需使用syn.bat进行同步