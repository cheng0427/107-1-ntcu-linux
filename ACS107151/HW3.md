## 1

+ ����root�n�J�A�إ�examuser1,examuser2,examuser3
+ ��Juseradd examuser1�ӫإ�examuser1�o�ӥΤ�
+ ��Jpasswd examuser1�Aexamuser1���K�X��ltlsExam
+ examuser2��examuser3�]�ΦP�˨B�J�إ�
+ 2.��Juserdel -r examuser3�R��examuser3���b���M�ؿ�
+ 3.��J id examuser1�A�d��examuser1��UID�MGID�A�O1001�A�A��Jadduser -u 1001 examuser1�A���s�إ�examuser1���b��
+ # ����
***
+ 1.���n�Jroot�A��Juseradd examuser4�ӫإ�examuser4�o�ӥΤ�
+ 2.��Jpasswd examuser4�A�]�w�K�X  
+ 3.���ۿ�Jcp/etc/securetty/home/examuser4/�A��/etc/securetty/�ƻs��examuser4 
+ 4.�A��chown examuser4 securetty�A��chmod u=rwx, g=rwx, o=rwx examuser4�Ϧ��b���֦�����ϥ��� 
+ 5.��mkdir examdata�A����cd�i�hexamdata�̭� 
+ 6.��Jtouch change.txt�إߪ��ɮסA��chown sshd change.txt�N�֦��̧אּsshd 
+ 7.�A��Jchgrp users change.txt�N�s�էאּusers�A��chmod u=rw,g=r,o= change.txt�Nsshd�iŪ�i�g 
+ 8.�̫��touch -t 20121221 change.txt�N�ɮת��ק����վ㦨 2012 �~ 12 �� 21 �� 
+ # ���� 
***
+ 1.�^��a�ؿ��A��Jmkdir dev�ӫإ�dev�o�Ӹ�Ƨ��A��Jcd dev/�i�Jdev��Ƨ�
+ 2.��Jmkdir shm�A�bdev����Ƨ��̦A�]�@�ӥs�@shm���l��Ƨ��A��Jcd shm�A�i�Jshm
+ 3.��Jmkdir unit05�A�Х�unit05�o�Ӹ�Ƨ��A��Jcd unit05�A�i�Junit05
+ 4.��Jchmod u=rwx, g=rwx, o=rx���unit05����Ƨ��v���A���ᱵ�۫إ�dir1-4����Ƨ�
+ 5.��Jls -1/dev/shm/unit05/dir[1-4]�A�i�H�o�{dir1�����G�O�iŪ�Adir2�����G�O�i����Adir3�����G�O�iŪ�i����Adir4�����G�O�iŪ�i�ק�i����
+ 6.�A��Jls -1/dev/shm/unit05/dir1/file[1-4]�A�i�H�o�{file1�����G�O�iŪ�Afile2�����G�O�iŪ�Afile3�����G�O�iŪ�i��g�Afile4�����G�O�S���v��
+ # ����
