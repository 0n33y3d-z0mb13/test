# PE
Linux - Privilege Escalation

## 1. 개요
   리눅스에서의 권한 상승은 Root 계정의 권한으로 
  a. 공격 벡터를 찾아주는 툴 사용
     - LinPEAS
     - LinuxSmartEnumeration
     - LinEnum
  b. Kernel Exploits


## Permission Model In Linux

## 권한 상승 기법
### 1. Kernel Exploits
Kernel exploits are programs that leverage kernel vulnerabilities in order to execute arbitrary code with elevated permissions

Why You Should Avoid Running Local Privilege Escalation Exploit At First Place?
Though, it feels very tempting to just run an exploit and get root access, but you should always keep this as your last option.

1) The remote host might crash as many of the root exploits publicly available are not very stable.
2) You might get root and then crash the box.
3) The exploit might leave traces/logs that can get you caught.
You should always try the other techniques to get root which have been discussed below before directly jumping to run a local root exploit.

### 2. Exploiting Services Which are Running as Root


## 참고
- Tips and Tricks for Linux Priv Escalation: https://github.com/frizb/Linux-Privilege-Escalation
- https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Methodology%20and%20Resources/Linux%20-%20Privilege%20Escalation.md#tools
- https://github.com/diego-treitos/linux-smart-enumeration
- https://github.com/m0nad/awesome-privilege-escalation#escape-restricted-shells
