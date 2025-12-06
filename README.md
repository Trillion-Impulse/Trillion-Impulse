- 👋 Hi, I’m @Trillion-Impulse
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Trillion-Impulse/Trillion-Impulse is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

memo
1. 문서화 주석, doc comments
2. tailwind
3. branching strategy, workflow (ex gitflow, trunk-based)
4. 패키지관리도구 npm과 그 밖에..
5. HTML에서 &amp;lt;와 같은 엔티티코드를 텍스트로 표시하는 법 (amp 이용)
6. HTML의 엔티티코드에 대하여
7. jquery
8. typescript
9. js Object.assign vs concat
10. js const vs Object.freeze
11. js BOM, DOM, API 객체
12. js preventDefault
13. js web storage API - local storage
14. js className vs classList
15. js innerText vs innerHTML
16. js Storage API - localStorage vs sessionStorage
17. Promise 메서드(any, try, withResolvers)
18. JSDoc - 주석
19. Docker
20. Flask 로그인 라이브러리
21. MYSQL
22. SQLAlchemy
23. flask - jinja2
24. OAuth2.0 vs OIDC
25. 시간복잡도
26. 공간복잡도
27. deque의 메서드
28. flask blueprint
29. 포트폴리오 README.md 정리
30. 멀티스레드
31. 멀티프로세싱
32. API로 만드는 경우 vs APP으로 만드는 경우
33. NLP
34. GHCR

IDE feat
1. vscode - 텍스트 범위 선택
   - 한 글자, 한 줄 - shift + 화살표
   - 한 단어 - shift + ctrl + 왼/오
2. vscode - 멀티 커서 - 쉬프트로 텍스트 범위 지정 후 ctrl+d
3. vscode - 자동완성
   - 코드를 작성할 때 가능한 코드 조각을 자동으로 제시해주는 기능
   - 트리거: for, class, function 등의 구문, 제어구조, 선언 등을 입력, .을 입력 등
   - 수동 사용법: 단어 입력 후 ctrl + space
4. vscode - snippets
   - 반복적으로 작성해야 하는 코드 블록을 빠르게 삽입할 수 있도록 미리 정의해놓은 코드 템플릿
   - 자동완성과 통합: 스니펫은 자동완성 기능과 함께 작동
      - 특정 단어를 입력한 뒤 탭을 눌러서 미리 정의된 코드 조각을 삽입
      - ex: for를 입력하고 자동완성 제안 목록에서 원하는 스니펫 항목을 선택한 후 Tab 키를 눌러 삽입
   - 확장성: 다양한 언어와 프레임워크에 맞춰서 스니펫을 확장 가능
   - 사용자 정의: 사용자는 settings.json 또는 snippets 폴더에서 개인화된 스니펫을 생성 가능
5. vscode - 탭 간 전환
   - ctrl + tab - 빠른 탭 전환
   - ctrl + p - 파일 탐색기

Coding Convention
1. 반복적, 변경되지 않을 문자열
   - 상수로 저장하여 관리
   - 대문자 + 스네이크
   - ex) ALL_CAPS

Conventional Commits
- 기본 구조
   - `<type>(<scope>): <commit message>`
   - type   커밋의 목적 (기능 추가, 수정, 리팩토링 등)
   - scope   어떤 기능, 모듈, 파일 등에 대한 변경인지 (선택적)
   - message   변경의 요약 내용
- 자주 사용하는 type 목록
   - feat   새로운 기능 추가
   - fix   버그 수정
   - refactor   코드 구조 개선 (기능 변화 없음)
   - style   스타일, 포맷팅 변경 (기능 변화 없음)
   - test   테스트 코드 관련
   - chore   빌드, 설정 등 기타 작업
   - docs   문서 수정
- scope
   - <기능/모듈명>/<파일명>
   - ex) login/index.html
   - 기능/모듈명 -> 파일명 순서의 이유
      - 폴더 구조 컨벤션을 따르는 순서라 자연스러움
