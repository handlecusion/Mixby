# Mixby

### 커밋 규칙

tag: header만 필수로 작성
|tagname|description|
|---|---|
|feat|새로운 기능에 대한 커밋|
|fix|버그 수정에 대한 커밋|
|build|빌드 관련 파일 수정 / 모듈 설치 또는 삭제에 대한 커밋|
|chore|그 외 자잘한 수정에 대한 커밋|
|ci|ci 관련 설정 수정에 대한 커밋|
|docs|문서 수정에 대한 커밋|
|style|코드 스타일 혹은 포맷 등에 관한 커밋|
|refactor|코드 리팩토링에 대한 커밋|
|test|테스트 코드 수정에 대한 커밋|
|perf|성능 개선에 대한 커밋|

커밋 예시
```
git commit -m "feat : api.py 크롤링 서비스 제작
barcode를 입력으로 넣으면 제품명을 리턴하는 getProductName 함수 제작"
```