# MacOS

- 각 명령어에 대한 자세한 정보는 MacOS 터미널에서 `man [command name]` 명령어를 입력하여 확인

## 핵심 명령어

| 키/명령어           | 설명                                                     |
|:----------------|:-------------------------------------------------------|
| cd [folder]     | 디렉토리를 변경합니다. 예) `cd Documents`                         |
| cd              | 홈 디렉토리                                                 |
| cd ~            | 홈 디렉토리                                                 |
| cd /            | 드라이브의 root                                             |
| cd -            | 이전 디렉토리                                                |
| ls              | 현재 디렉토리의 짧은 목록                                         |
| ls -l           | 현재 디렉토리의 긴 목록                                          |
| ls -a           | 숨겨진 파일이 포함된 목록                                         |
| ls -lh          | 사람이 읽을 수 있는 파일 사이즈 표기가 포함된 목록                          |
| ls -R           | 재귀적으로 모든 폴더의 컨텐츠 표시                                    |
| sudo [command]  | superuser의 보안 권한으로 명령어를 실행합니다. (sudo = Super User DO)  |
| open [file]     | 파일을 엽니다. ( 더블클릭 한 것처럼 )                                |
| top             | 현재 동작중인 프로세스를 표시합니다. q를 누르면 표시를 종료합니다.                 |
| nano [file]     | nano 에디터로 파일을 엽니다.                                     |
| vim [file]      | vim 에디터를 파일을 엽니다.                                      |
| clear           | 화면을 지웁니다.                                              |
| reset           | 터미널을 reset합니다.                                         |



## 디렉토리 관리

| 키/명령어                | 설명                                        |
|:---------------------|:------------------------------------------|
| mkdir [dir]          | 새 디렉토리를 만듭니다.                             |
| mkdir -p [dir]/[dir] | 중첩된 디렉토리를 만듭니다.                           |
| rmdir [dir]          | 디렉토리를 삭제합니다. (빈 디렉토리인 경우에만 작동합니다.)        |
| rm -R [dir]          | 디렉토리와 컨텐츠를 삭제합니다.                         |
| less [file]          | 화면 사이즈로 제공되는 파일의 내용                       |
| [command] > [file]   | output을 파일로 만듭니다. 이 파일은 덮어써지는 것을 명심해야합니다. |
| [command] >> [file]  | output을 기존의 파일에 추가합니다.                    |
| [command] < [file]   | 파일에서 내용을 읽으라는 명령을 수행합니다.                  |


## 네트워크 관리

| 키/명령어      | 설명                                           |
|:-----------|:---------------------------------------------|
| ifconfig   | MacOS의 네트워크 인터페이스의 상태를 표시합니다.                |
| ping       | 네트워크 호스트의 응답 상태를 테스트합니다.                     |
| nslookup   | 도메인 이름 또는 IP 주소에 대한 DNS 정보를 검색합니다.           |
| traceroute | 네트워크 패킷이 어디에서부터 어디로 가는지 보여줍니다.               |
| route      | 네트워크 경로를 검색하고 관리합니다.                         |
| mtr        | 네트워크 경로의 상태를 실시간으로 모니터링합니다.                  |
| ssh        | 원격 호스트에 접속합니다.                               |
| scp        | 원격 호스트로 파일을 복사합니다.                           |
| wget       | 파일을 다운로드합니다.                                 |
| curl       | 파일을 다운로드합니다.                                 |
| telnet     | 원격 호스트에 접속합니다.                               |
| netstat    | 네트워크 상태를 표시합니다.                              |
| arp        | ARP(Address Resolution Protocol) 테이블을 보여줍니다. |
| lsof			    | 현재 시스템에서 열려 있는 파일 리스트를 보여줍니다.                |

