## Weakness Tracker (Full review, 2026-08-03)

### 🔴 Top priority (failed repeatedly)
1. The anchor tag trio — failed 3 times. target="_blank" (underscore!),
   rel is ONE attribute with TWO values inside ONE pair of quotes: rel="noopener noreferrer"
   → Drill: type the full line once a day. Retest at the start of next session.
2. Syntax closing habits — closing quotes, closing </body> and </html>.
   After writing, always check every open/close pair.

### 🟡 In progress
3. <a> is INLINE — "links, emphasis (em/strong), and images live inside a sentence"
4. Paths — use ../ ONLY when the current file is inside a folder.
   Step 1 is always: where am I standing? Then compare letter by letter.
5. Attribute = name="value" pair — must be able to explain tag / attribute name / attribute value
6. Local vs server — ① case sensitivity ② browsers silently fix broken HTML
   (local is forgiving, the server is strict)
7. Explain web concepts by definition, not by example —
   browser = a program, search engine = a website, HTTPS = encrypted HTTP,
   packets = data is split so the network can be shared and lost pieces can be resent
8. HTML comment <!-- --> / git init = start a new repo locally (clone = copy from remote)

### 🟢 Graduated
- 4 image formats (3 correct in a row), git "ahead by N" + push, ul/ol,
  pwd/cd/ls/mkdir/touch, cd .. = ../ in HTML (same concept, now unified),
  relative paths (going up), img/src/alt, full git workflow order

### Analogy dictionary
- folder = room, ../ = step out of the room (same in HTML and terminal)
- block = a floor (takes the whole line), inline = furniture (flows inside a sentence)
- git: add = put in the box → commit = seal + label → push = ship it
- browser = the car, search engine = a place you drive to / HTTP = postcard, HTTPS = sealed letter

## 약점 추적표 (2026-08-03 전범위 복습 기준)

### 🔴 최우선 (반복 실패)
1. a 태그 3종 세트 — 3회 실패. target="_blank"(밑줄!), rel은 따옴표 한 쌍에 값 두 개: rel="noopener noreferrer"
   → 처방: 매일 한 번 통째로 타이핑. 다음 세션 첫 문제로 재시험.
2. 문법 마감 — 따옴표 닫기, </body></html> 닫기. 쓰고 나서 여닫기 검사 습관.

### 🟡 진행 중
3. a는 인라인 — "링크, 강조 둘(em/strong), 그림(img)은 문장 속에 산다"
4. 경로 — ../는 방 안에 있을 때만. 출발점 확인이 1단계. + 글자 단위 대조
5. 속성 = 이름"값" 쌍 — 속성값 개념 포함해서 설명 가능해야 함
6. 로컬 vs 서버 — ① 대소문자 ② 브라우저의 HTML 오류복구(로컬은 관대, 서버는 엄격)
7. 웹 개념 정의로 말하기 — 브라우저=프로그램, 검색엔진=웹사이트, HTTPS=암호화, 패킷=조각내야 나눠쓰고 재전송 가능
8. HTML 주석 <!-- --> / git init=로컬에서 새로 시작(clone=원격에서 복제)

### 🟢 졸업
- 4대 이미지 포맷(3연속 정답), git ahead by N + push, ul/ol, pwd/cd/ls/mkdir/touch,
  cd .. = HTML ../ (동일 개념 통합), 상대경로 작성(올라가기), img/src/alt, git 실전 순서

### 오늘 배운 비유 사전
- 폴더=방, ../=방 밖으로 한 칸 (HTML과 터미널 공통)
- 블록=층(통째로 차지), 인라인=가구(문장 속을 흐름)
- git: add=상자에 담기 → commit=봉인+송장 → push=발송
- 브라우저=차, 검색엔진=안내소 / HTTP=엽서, HTTPS=봉인 편지