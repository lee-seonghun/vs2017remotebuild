
# 비주얼 스튜디오 2017 (VS2017)을 다른 PC에서 빌드하기

개발용 pc를 노트북을 사용하는데 빌드하고 디버깅할 때 너무 뜨거워진다.
빌드할 때 발생하는 열을 다른 사람옆에 있는 데스트콥으로 보내려고 한다.

개발실 구석에 데스크톱 pc가 있고, VS가 설치되어 있어서 디버깅할 때 활용할 방법을 생각해 봤다.

조건)
비주얼 스튜디어가 설치된 PC, 노트북
두 PC의 저장소 드라이브이름이 동일하게 부여할 수 있다.

절차)
1. 노트북) 소스폴더를 네트워크 공유한다.
2. PC) 노트북 공유폴더를 네트워크 드라이브로 연결한다.
3. PC) 노트북의 소스 폴더와 동일한 폴더 트리를 만든다. 소스폴더는 제외
4. PC) 네트워크 드라이브를 폴더아래의 소스폴더이름과 동일하게 심볼릭링크를 연결한다.

*) 외부 프로젝트에 대해서도 위 과정으로 설정한다.
