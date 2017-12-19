# Install_win7_in_USB_HDD

use DISKPART make active in CMD

list disk 

 磁碟 ###  狀態           大小     可用     Dyn  Gpt
 
  --------  -------------  -------  -------  ---  ---
  
  磁碟 0    連線              931 GB      0 B        *
  
  磁碟 1    連線               22 GB      0 B
  
  磁碟 2    連線              931 GB   488 GB
  
  
 list PARTITION

  磁碟分割  ###  類型              大小     位移
  
  -------------  ----------------  -------  -------
  
  磁碟分割  1    主要                 931 GB  1024 KB

DISKPART> select PARTITION 1

磁碟分割 1 是所選擇的磁碟分割。

DISKPART> list PARTITION

  磁碟分割  ###  類型              大小     位移

-------------  ----------------  -------  ------

* 磁碟分割  1    主要                 931 GB  1024 KB

DISKPART> active

DiskPart 已標記目前的磁碟分割為使用中。
