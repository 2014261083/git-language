# git 명령어와 markdown 명령어 정리 과제
### 학번 : 2014261083
### 성명 : 김대준
### 과목명 : 안드로이드프로그래밍
### 시간 : (수)15:00~17:50
### 담당교수님 : 진용화 교수님



---
---


## git 명령어 ##

git명령어|기능
---|---
git clone <저장소url>|저장소 복제
git init|새로운 저장소 초기화하기
git config --global - -list|전역 설정 정보 조회
git config --global user.email|이메일 주소를 추가
git config --global user.name |유저 이름을 추가
git config --global --unset-all user.email|전역 설정 정보 삭제시키기
git config --global --unset-all user.name |전역 설정 정보 삭제시키기
git remote add <원격 저장소> <저장소 url>|새로운 원격 저장소 추가
git add <파일>|새로운 파일 git에 등록시키기(스태깅)
git commit -m “<메시지>”|현재까지 작업한 내용 저장하기
git fetch <원격 저장소>|원격 저장소에서 합치지 않고 지역 브랜치로 변경 사항 가져오기
git pull <원격 저장소>|원격 저장소에서 변경 사항을 가져와 현재 브랜치에 합치기
git push <원격 저장소> <지역 브랜치>|새로운 로컬 브랜치를 원격 저장소에 푸싱하기
git config --global color.ui "auto"|출력 결과 색상 활성화
git config --global color.ui "off"|출력 결과 색상 비활성화


---


## markdown 명령어 ##

마크다운은 일반 텍스트 문서의 양식을 편집하는 문법입니다. README 파일이나 온라인 문서, 혹은 일반 텍스트 편집기로 문서 양식을 편집할 때 쓰이고 마크다운을 이용해 작성된 문서는 쉽게 HTML 등 다른 문서 형태로 변환이 가능합니다.

### 폰트 관련 사용법

볼드체 설정|이탤릭체 설정|취소선 긋기|색입히기
---|:---|:---:|---:
**볼드**|*이탤릭*|~~취소선~~|<span style="color:red">색입히기</span>
글자앞뒤를 **으로 씌움|글자 앞뒤를 *로 씌움|글자 앞뒤를 ~~로 씌움|html의 span 태그 사용

### 링크 넣기

[naver로 갑니다](naver.com)

[]안에 텍스트를 지정합니다. 지정했다면 바로 뒤에 (링크명)를 붙여 링크를 넣어줍니다.

### 구분선 넣기
-을 3번 입력.

### 이미지 넣기

![사진](C:\Users\user\Desktop\crescent.jpg)

![텍스트]라는 형태로 이미지 이름을 지정합니다. 지정했다면 (이미지링크)를 바로 뒤에 붙여 이미지를 링크해줍니다.

### 인용구 활용하기

> 인용구 원문

: >뒤에 인용구를 넣어서 인용구를 넣어 줍니다. 

