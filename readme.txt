1. �ѹ����� ��ѹtoolschain.tar.gz ���õ�����Ŀ¼
	�� /opt Ŀ¼��
	cp toolschain.tar.gz /opt /   #ȷ��ӵ��Ȩ��
    tar �Czxvf  toolschain.tar.gz  #ȷ��ӵ��Ȩ��

2.��ӻ�������
 ����1 ��shell��
	export TOOLSHOME=/opt/toolschain/iros-tools  #��ղŴ��Ŀ¼һ��
export SWHOME=Դ���Ŀ¼
����2��
	��profile�����������������
		export TOOLSHOME=/opt/toolschain/iros-tools
              export TOOLSHOME=/~/����/toolschain/iros-tools
       export SWHOME=$PWD

3.����Դ���Ŀ¼ ִ��
	���� sh sheel_script.sh
	������ʾѡ��Ҫ����Ĳ�Ʒ
		 [1] make GT811D
[2] make GT811G
[3] make GT873_M_4F4S
[0] make clean
Select Product Type NO.:

