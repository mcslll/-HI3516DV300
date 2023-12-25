设置静态IP地址  
ifconfig <网络接口> <IP地址> netmask <子网掩码>  
例如：  
ifconfig eth0 192.168.1.2 netmask 255.255.255.0

海思HI3516DV300：LINUX服务器SDK安装、NFS挂载(https://www.freesion.com/article/3108546957/)  
挂载目录到开发板命令（参数询问chatgpt）：  
mount -t nfs -o nolock <serverip>:<server's folder> <Local folder>  
例如:  
mount -t nfs -o nolock -o tcp 10.0.1.107:/home/lotogram/Desktop/xwx/nfs ./nfs  
mount -t nfs -o nolock 10.0.1.107:/home/lotogram/Desktop/xwx/nfs ./nfs
