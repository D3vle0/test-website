# Comjipsa-컴집사
---
## 컴집사란?
사용자들의 좋지 않은 컴퓨터 사용 습관을 고치기 위한 보안 솔루션 프로그램입니다.   

## 원리
사용자가 인터넷을 들어갈 때 URL을 분석하여 블랙리스트 DB에 포함되어 있는지 확인합니다.   
만약 있을 경우, 웹사이트 접근 권한을 거부하고 로그를 남깁니다. (날짜, 시간과 함께)   

## 개발 동기
인터넷의 발전과 함께 그에 따른 사이버 범죄도 심각합니다.   
2017년 5월 랜섬웨어 국내 대량 유포, 급증하는 몸캠 피싱, 범죄 뿐 아니라 심지어는 보안적인 문제도 일어나고 있습니다.   
몇몇 바이러스는 웹페이지 자체에 심어 접속하자마자 내 컴퓨터가 좀비 PC가 되기도 하고, 웹캠 녹화와 마이크 녹음 권한도 얻습니다.    
따라서 이런 일을 사전에 예방하고자 PC 최적화와 보안을 지킬 수 있는 통합 솔루션 프로그램을 만들게 되었습니다.   

## 개발 과정
이 프로젝트는 영재원 1차 프로젝트실습 시간 (여름) 때 부터 생각해왔습니다.   
그 당시에는 계획만 세웠고, 2차 프로젝트실습 시간 때 설마 이걸 구현하는 건 아니겠지 라는 생각으로 했기에 처음 개발은 막막했습니다.   
원래의 계획은 인터넷 브라우저에서 현재 접근하려는 URL 을 파싱하려고 했으나 JS 를 쓰면 또 다른 부분에 문제가 생겨   
조금 다른 방식으로 C언어로 구현을 했습니다.   

## 추가 개발 계획   
1. 원래 계획이었던 URL 파싱
2. 블랙리스트를 사용자 제보 방식으로 만들기, 제보용 웹페이지 제작
3. 컴퓨터 시작 시 자동으로 실행하여 백그라운드로 돌아가며 1시간에 한 번 씩 메모리 정리

이걸 C언어로 구현한다니... API 쪽으로도 많이 공부해야겠다.
