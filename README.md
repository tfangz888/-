# 备份文件前先在手机上安装 Termux, 并且打开sshd 服务
手机文件备份到LINUX电脑

# 备份照片
## run 'sshd' on mobile phone
rsync -av -e 'ssh -p 8022' u0_a153@192.168.0.101:/sdcard/DCIM/Camera/ /media/sf_f/picture/

# 备份orgzly笔记
## run sshd in termux
rsync -av -e 'ssh -p 8022' u0_a153@192.168.0.101:/sdcard/notebook/ /media/sf_f/notebook/orgzly/
