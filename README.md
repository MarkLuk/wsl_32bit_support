# Windows Subsystem for Linux - Enable 32bit executable support
Windows Subsystem for Linux (WSL) does not support 32bit executables. 
This script enables execution of 32bit executables via QEMU.

#### Setup
```
wget https://raw.githubusercontent.com/MarkLuk/wsl_32bit_support/master/wsl_32bit_enable.sh
chmod +x wsl_32bit_enable.sh
```

#### Execution
```
sudo ./wsl_32bit_enable.sh
```
