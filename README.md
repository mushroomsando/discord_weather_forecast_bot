# Discord_WEATHER FORECAST Bot

기록 & 백업용 레포지토리

## BOT INTRODUCE

이 봇은 기상청 API를 이용해서 일기예보를 보여주는 봇입니다.

간단한 게임과 간단하게 서버를 관리할 수 있는 기능도 제공합니다.

## 구현중인 기능

현재 구현 또는 개발중인 기능

##### GAME

* [ ] 가위바위보

##### WEATHER FORECAST

* [X] 일기예보 출력
* [ ] 일기예보 버그 수정 (API 데이터를 처리하는 과정에서 문제가 있는것으로 보임)
* [X] 지금 날씨 출력
* [X] 서버 별로 지역 선택 및 저장
  * [X] 저장한 데이터를 사용하도록 코드 전체 수정
* [ ] 기상특보 출력 [(이거 쓸꺼임)](https://github.com/mushroomsando/special-weather-report)
* [X] 코드 ~~최적화~~ *(의도치 않은)* 로직 재구성 및 코드 재작성

##### SEVER MANEGEMENT

* [X] 킥
* [X] 밴
* [X] 언밴
* [X] 채팅청소
* [ ] 타임아웃 적용
* [X] 서버 정보 출력 (일기예보 지역 선택 및 저장 기능과 연계)

##### Other Features

* [ ] discord.py 2.0 코드 지원
* [X] 명령어 정보 출력
* [ ] 파일구조 개편
<<<<<<< HEAD

## 문제점

* 기상청 단기예보 API가 문제인건지 아니면 버그인건지 모르겠는데 기상청 홈페이지와 기상청 API 정보와 데이터가 일치하지 않음