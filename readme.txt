1. 把工具链 解压toolschain.tar.gz 放置到任意目录
	如 /opt 目录，
	cp toolschain.tar.gz /opt /   #确保拥有权限
    tar –zxvf  toolschain.tar.gz  #确保拥有权限

2.添加环境变量
 方法1 ：shell中
	export TOOLSHOME=/opt/toolschain/iros-tools  #与刚才存放目录一致
export SWHOME=源码根目录
方法2：
	在profile中添加以上两个变量
		export TOOLSHOME=/opt/toolschain/iros-tools
              export TOOLSHOME=/~/下载/toolschain/iros-tools
       export SWHOME=$PWD

3.进入源码根目录 执行
	命令 sh sheel_script.sh
	根据提示选择要编译的产品
		 [1] make GT811D
[2] make GT811G
[3] make GT873_M_4F4S
[0] make clean
Select Product Type NO.:

