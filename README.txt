�޸�hosts����Ч�ķ�������ˢ�� dns ���

һ��Windows
��ʼ -> ���� -> ����cmd -> ��CMD��������:
ipconfig /flushdns



����Linux
�ն����룺
sudo rcnscd restart


����systemd���а棬��ʹ�����
sudo systemctl restart NetworkManager



����Mac OS X�ն����룺
sudo killall -HUP mDNSResponder
