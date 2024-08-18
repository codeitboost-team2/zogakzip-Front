# 🌼 2팀 프론트엔드
## 🚀 기술 스택
- HTML, CSS, JavaScript
- React
- React Router
- JQuery
- ESLint, Prettier
## 📁 프로젝트 폴더 구조
```
/src
│
├── /assets            # 정적 파일 (이미지, 폰트, 전역 스타일 등)
├── /components        # 재사용 가능한 UI 컴포넌트
│   ├── /common        # 범용 컴포넌트 (버튼, 인풋 등)
│   ├── /layout        # 레이아웃 관련 컴포넌트 (헤더, 푸터 등)
│   └── /cards         # 카드 컴포넌트
├── /containers        # 페이지별 컨테이너 컴포넌트 (홈, 그룹, 메모리 페이지 등)
├── /hooks             # 커스텀 훅
├── /context           # 전역 상태 관리 (Context API 등)
├── /services          # API 호출 및 비즈니스 로직
├── /utils             # 유틸리티 함수 모음
├── /routes            # 라우팅 설정 파일
└── index.js           # 애플리케이션 진입점
```
## 📏 컨벤션
- ESLint, Prettier 사용하기
- 특별한 경우가 아니면 문자열은 작은 따옴표를 사용하기
- 컴포넌트는 파스칼 케이스로 선언하기
- 변수 선언은 const와 let 키워드를 사용하기
- 변수는 카멜 케이스로 선언하기
- 상수는 스네이크 케이스를 활용해 대문자와 _를 사용해 선언하기
## 👩‍💻 역할 분담
- **김은영**: 'button', 'tab', 'badge' 등 UI 컴포넌트
- **김혜원**: 입력 폼 관련, 'search, 'more', 'pagination' 컴포넌트
- **유예린**: 카드 관련 컴포넌트
