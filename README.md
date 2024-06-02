# 오픈소스 과제 20243124 김선재

## 순서
1. top 명령어
2. ps 명령어
3. jobs 명령어
4. kill 명령어

## 1. top 명령어

top 명령어는 실시간으로 시스템의 프로세스 및 성능 정보를 보여주는 명령어 입니다.

| 옵션 | 기능 |
| ---- | ---- |
|-d|갱신 주기를 설정합니다.|
|-p|특정 PID를 모니터링합니다.|
|-u|특정 사용자의 프로세스만 표시합니다.|
|-n|지정한 횟수만큼 업데이트한 후 종료합니다.|

## 2. ps 명령어

ps 명령어는 현재 실행 중인 프로세스를 보여줍니다.

| 옵션 | 기능 |
| ---- | ---- |
|-e|모든 프로세스를 나열합니다.|
|-f|전체 형식으로 출력합니다.|
|-u|특정 사용자의 프로세스를 나열합니다.|
|-aux|모든 사용자의 모든 프로세스를 상세히 나열합니다.|

## 3. jobs 명령어

jobs 명령어는 명령어는 현재 쉘 세션에서 실행 중인 작업을 보여줍니다.

| 옵션 | 기능 |
| ---- | ---- |
|-l|모든 프로세스를 나열합니다.|
|-p|각 작업의 프로세스 id만 출력합니다.|
|-r|실행 중인 작업만 나열합니다.|
|-s|멈춘(stopped) 작업만 나열합니다.|

## 4. kill 명령어

kill 명령어는 특정 프로세스를 종료합니다.


| 옵션 | 기능 |
| ---- | ---- |
|-9|강제 종료 시그널을 보냅니다.|
|-15|정상 종료 시그널을 보냅니다.|
|-l|사용할 수 있는 시그널 목록을 출력합니다.|
