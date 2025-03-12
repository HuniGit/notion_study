### **파일 및 디렉토리 관련 명령어**<br>  
1. **`ls`**  
1. **`cd`**  
1. **`pwd`**  
1. **`mkdir`**  
1. **`rm`**  
1. **`cp`**  
1. **`mv`**  
1. **`touch`**  
1. **`find`**  
---  
### **시스템 상태 및 디스크 관리 명령어**<br>  
1. **`df`**  
1. **`du`**  
1. **`top`**  
1. **`ps`**  
1. **`uptime`**  
1. **`free`**  
1. **`who`**  
---  
### **파일 내용 보기 관련 명령어**<br>  
1. **`cat`**  
1. **`less`**  
1. **`head`**  
1. **`tail`**  
---  
### **사용자 및 권한 관리 명령어**<br>  
1. **`whoami`**  
1. **`chmod`**  
1. **`chown`**  
1. **`sudo`**  
---  
### **네트워크 관련 명령어**<br>  
1. **`ping`**  
1. **`ifconfig`** (또는 `ip a`)  
1. **`wget`**  
1. **`curl`**  
---  
### **압축 및 아카이브 관련 명령어**<br>  
1. **`tar`**  
1. **`gzip`**** / ****`gunzip`**  
---  
### . 의 명령어<br>  
`.`은 파일 시스템 경로에서 현재 디렉토리와 관련된 경로를 나타낼 수 있습니다.  
  
---  
이 명령어들은 리눅스를 사용하는 데 필수적인 기본 명령어들  
  
  
  
  
  
  
  
  
---  
### **Ubuntu 기본 명령어 정리**<br>  
Ubuntu는 리눅스 배포판 중 하나로, 명령어 기반의 작업이 중요한 운영체제입니다. 아래는 Ubuntu에서 자주 사용하는 명령어를 카테고리별로 정리한 것입니다.  
---  
### **1. 파일 및 디렉토리 관리**<br>  
|명령어|설명|예시|  
|:---|:---|:---|
|`ls`|디렉토리 목록 보기|`ls`, `ls -l`, `ls -a`|  
|`cd`|디렉토리 변경|`cd /home`, `cd ..`|  
|`pwd`|현재 디렉토리 경로 확인|`pwd`|  
|`mkdir`|새 디렉토리 생성|`mkdir my_folder`|  
|`rmdir`|빈 디렉토리 삭제|`rmdir my_folder`|  
|`rm`|파일/디렉토리 삭제|`rm file.txt`, `rm -r folder`|  
|`cp`|파일/디렉토리 복사|`cp file.txt /backup/`|  
|`mv`|파일/디렉토리 이동 또는 이름 변경|`mv file.txt new_name.txt`|  
|`touch`|빈 파일 생성|`touch newfile.txt`|  
|`find`|파일/디렉토리 검색|`find / -name file.txt`|  
|`locate`|빠른 파일 검색 (사전 색인 필요)|`locate file.txt`|  
---  
### **2. 디스크 및 파일 시스템 관리**<br>  
|명령어|설명|예시|  
|:---|:---|:---|
|`df`|디스크 사용량 확인|`df -h`|  
|`du`|특정 디렉토리 사용량 확인|`du -sh folder`|  
|`mount`|파일 시스템 마운트|`mount /dev/sdb1 /mnt`|  
|`umount`|파일 시스템 마운트 해제|`umount /mnt`|  
|`lsblk`|블록 디바이스 목록 확인|`lsblk`|  
|`blkid`|디스크의 UUID 및 파일 시스템 정보 확인|`blkid`|  
|`fdisk`|디스크 파티션 관리|`sudo fdisk /dev/sda`|  
---  
### **3. 사용자 및 권한 관리**<br>  
|명령어|설명|예시|  
|:---|:---|:---|
|`whoami`|현재 사용자 이름 확인|`whoami`|  
|`who`|로그인 사용자 확인|`who`|  
|`id`|사용자 UID와 GID 확인|`id`|  
|`chmod`|파일/디렉토리 권한 변경|`chmod 755 file.txt`|  
|`chown`|파일 소유자 변경|`chown user:group file.txt`|  
|`passwd`|사용자 비밀번호 변경|`passwd`|  
|`groups`|사용자 그룹 확인|`groups username`|  
|`sudo`|관리자 권한으로 명령 실행|`sudo apt update`|  
---  
### **4. 네트워크 관리**<br>  
|명령어|설명|예시|  
|:---|:---|:---|
|`ping`|네트워크 연결 확인|`ping google.com`|  
|`curl`|URL 요청 및 응답 확인|`curl http://example.com`|  
|`wget`|파일 다운로드|`wget http://example.com/file`|  
|`ifconfig`|네트워크 인터페이스 정보 확인|`ifconfig`|  
|`ip a`|네트워크 인터페이스 정보 확인 (ifconfig 대체)|`ip a`|  
|`netstat`|네트워크 연결 상태 확인|`netstat -tuln`|  
|`ss`|네트워크 상태 확인 (netstat 대체)|`ss -tuln`|  
|`traceroute`|네트워크 경로 추적|`traceroute google.com`|  
|`nslookup`|DNS 정보 조회|`nslookup google.com`|  
---  
### **5. 프로세스 및 시스템 관리**<br>  
|명령어|설명|예시|  
|:---|:---|:---|
|`top`|실시간 시스템 상태 및 프로세스 확인|`top`|  
|`htop`|더 친화적인 프로세스 확인 툴|`htop`|  
|`ps`|현재 실행 중인 프로세스 목록 확인|`ps aux`|  
|`kill`|프로세스 종료|`kill 1234`|  
|`killall`|특정 이름의 모든 프로세스 종료|`killall firefox`|  
|`uptime`|시스템 가동 시간 및 부하 확인|`uptime`|  
|`free`|메모리 사용량 확인|`free -h`|  
|`uname`|시스템 정보 확인|`uname -a`|  
|`reboot`|시스템 재부팅|`sudo reboot`|  
|`shutdown`|시스템 종료|`sudo shutdown now`|  
---  
### **6. 소프트웨어 관리**<br>  
|명령어|설명|예시|  
|:---|:---|:---|
|`apt update`|패키지 목록 업데이트|`sudo apt update`|  
|`apt upgrade`|설치된 패키지 업그레이드|`sudo apt upgrade`|  
|`apt install`|패키지 설치|`sudo apt install vim`|  
|`apt remove`|패키지 제거|`sudo apt remove package_name`|  
|`dpkg`|패키지 정보 확인 및 관리|`dpkg -l`|  
|`snap`|스냅 패키지 설치/관리|`sudo snap install package`|  
---  
### **7. 로그 및 시스템 상태 확인**<br>  
|명령어|설명|예시|  
|:---|:---|:---|
|`dmesg`|커널 메시지 출력|`dmesg`|  
|`journalctl`|시스템 로그 확인|`journalctl -xe`|  
|`tail`|파일의 마지막 줄 출력|`tail -f /var/log/syslog`|  
---  
  
