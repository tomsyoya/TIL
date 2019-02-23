## 依存関係を考慮してカーネルモジュールをロードまたはアンロードするコマンドは?
A. `modprobe`  
  
**※カーネルモジュールとは？**   
カーネルで扱われる各部品のようなもの  
  
#### 他のカーネルに関するコマンド  
`lsmod`: ロードされているカーネルモジュールを表示するコマンド  

## PCIデバイスの情報を表示するコマンドは?
A: `lspci`, `cat /proc/bus/pci/devices`  
  
※PCIデバイスとは？
イーサネットやSCSIカードなどの周辺機器が接続された際に、振る舞うべき内容が記述される。  

lspicコマンドの実行例(centos7)  
```
$ lspci
00:00.0 Host bridge: Intel Corporation 440FX - 82441FX PMC [Natoma] (rev 02)
00:01.0 ISA bridge: Intel Corporation 82371SB PIIX3 ISA [Natoma/Triton II]
00:01.1 IDE interface: Intel Corporation 82371AB/EB/MB PIIX4 IDE (rev 01)
00:02.0 VGA compatible controller: InnoTek Systemberatung GmbH VirtualBox Graphics Adapter
00:03.0 Ethernet controller: Intel Corporation 82540EM Gigabit Ethernet Controller (rev 02)
00:04.0 System peripheral: InnoTek Systemberatung GmbH VirtualBox Guest Service
00:05.0 Multimedia audio controller: Intel Corporation 82801AA AC'97 Audio Controller (rev 01)
00:07.0 Bridge: Intel Corporation 82371AB/EB/MB PIIX4 ACPI (rev 08)
00:08.0 Ethernet controller: Intel Corporation 82540EM Gigabit Ethernet Controller (rev 02)
```
  
[参考ページ](https://linuxjf.osdn.jp/JFdocs/The-Linux-Kernel-7.html)
