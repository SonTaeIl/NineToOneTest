# NineToOneTest

** Info **

[App Name]: NinetoTest
[Bundle]: com.app.nine.NinetoTest
[Architecture]: RIBs

**Library ( SPM, Carthage 사용 )
- GEOSwift
- Lottie
- Moya
- RIBS
- RxCocoa
- NaverMap

**Others
~~SwiftUI~~ Swift 사용

기본 좌표 서울 숲 사용, 줌 레벨 15 사용

앱 시작시 도큐먼트 위치에 areaResource.json 파일이 없으면 다운로드 -> 도큐먼트 위치에 저장 후 사용
Map 그려진 후 중앙 위치 지점에서 반경 300 정도의 카페 검색 후 뿌림 
