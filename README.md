# 💳 Card-Reco Project 
<img src="https://img.shields.io/badge/Python-3766AB?style=flat-square&logo=Python&logoColor=white"/></a> <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=Python&logoColor=white"/></a> <img src="https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=Python&logoColor=white"/></a> <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=OpenCV&logoColor=white"/></a> <img src="https://img.shields.io/badge/Android Studio-3DDC84?style=flat-square&logo=OpenCV&logoColor=white"/></a> <img src="https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=Spring&logoColor=white"/></a>


* 목표: 상황, 때에 맞는 소비를 위한 맞춤형 카드 추천
* 기간: 2022.01.01. ~ 2023.06.30.
* 인원: 5명(김재희, 김보람, 박선민, 이경영, 정주영)
* 기능
  * 카메라 스캔 기능을 활용한 카드 인식 기능
  * 내 지갑 기능을 활용한 카드 보유 목록 조회
    1. 카드 만료 알림 서비스
    2. 카드 재발급 신청 서비스
    3. 카드 분실신고 서비스
  * 내게 맞는 카드 추천 기능(성향 분석 및 소비 패턴 분석)
  * 카드 별 상세 혜택 조회
  * 장소, 카드명 검색 기능 등

## 💳 Git Commit Rule
- [X] 제목과 본문을 한 줄 띄워 분리했는지
- [X] 제목 첫 글자를 대문자로 썼는지
- [X] 영문 기준 50자 이내로 작성했는지
- [X] 제목은 명령조로 썼는지
- [X] 제목 끝에 .를 쓰지 않았는지
- [X] Github - 제목(이나 본문)에 이슈 번호 붙였는지
- [X] 본문의 경우 영문 기준 72자마다 줄을 바꿨는지
- [X] 본문의 경우 어떻게보다 무엇을, 왜에 맞춰 작성했는지


|형식|타입|설명|
|------|---|---|
|[feat]|feat|새로운 기능 추가|
|[fix]|fix|버그 수정|
|[docs]|docs|문서 수정|
|[style]|style|코드 포맷팅(코드 변경이 없어야 함)|
|[refactor]|refactor|코드 리팩터링|
|[test]|test|테스트 코드|
|[design]|design|CSS 등 사용자 UI디자인 변경|
|[etc]|etc|그 외(파일 위치 변경/삭제 외)|


#### commit 작성 예시
    제목: [형식][이름] 간략한 설명(# 이슈번호)
    본문: 관련 기능 및 설명
    꼬리표: (# 해결한 이슈번호)
    

#### 예
    [feat][br] 내 지갑 카드 만료 알림 기능 추가(#13) 
    
    내 지갑 카드 만료 알림 기능 추가
    MyWalletPopup.java: POP-UP 알림창 방식으로 기능 추가
    
    해결: #13
  
## 💳  Merge Requeest Rule
- [X] conflict 여부 확인
- [X] Approve의 승인 여부
