# Pacebook App (pacebook_app)
2025-1 HY-End 재학생 프로젝트 Pacebook Front-End 레포지토리입니다.  
페이스북(Pacebook)은 러닝 기록 측정과 사용자 간의 커뮤니티 활동을 돕는 애플리케이션입니다.

## 📁 폴더 구조

이 프로젝트는 다음과 같은 폴더 구조를 따릅니다.

-   `lib/screens`: 각 화면(UI)을 구성하는 위젯
-   `lib/widgets`: 여러 화면에서 공통으로 사용되는 재사용 가능한 위젯
-   `lib/models`: 애플리케이션에서 사용하는 데이터 모델
-   `lib/services`: API 통신, 데이터베이스 등 외부 서비스와 연동하는 로직
-   `lib/utils`: 상수, 유틸리티 함수 등

## 🤝 팀 규칙 (Contribution Guidelines)

프로젝트에 기여하기 전에 다음 규칙을 숙지해주세요.

1.  **브랜치 전략:**
    -   `main`: 최종 출시 버전
    -   `develop`: 개발의 중심이 되는 브랜치
    -   `feature/기능이름`: 새로운 기능 개발
    -   `fix/수정내용`: 버그 수정
2.  **커밋 메시지:** `[Feat] 로그인 기능 추가`, `[Fix] 프로필 이미지 오류 수정` 과 같이 말머리를 붙여주세요.
3.  **코드 스타일:** 플러터 기본 코드 스타일을 준수합니다. (추후 Linter 규칙 추가 예정)

## 🛠️ 주요 기술 스택

-   **Framework:** Flutter
-   **Language:** Dart
-   **Backend:** Django
