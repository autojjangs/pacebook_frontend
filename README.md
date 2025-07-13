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

### 커밋 타입 태그
- `[UI]` : UI 작업  
- `[Logic]` : 기능 구현  
- `[Add]` : 기능 추가  
- `[Delete]` : 파일/코드 삭제  
- `[Fix]` : 버그 수정  
- `[Rename]` : 이름 변경(변수, 파일, 클래스 등)  
- `[Merge]` : Merge 작업  
- `[Back_Connect]` : 백엔드 API/데이터 연결

### Branch 전략
모든 작업은 `main` 브랜치에서 파생된 기능별 하위 브랜치에서 진행합니다. 
- **브랜치명**: `팀원명`  

### Issue 컨벤션
- **제목 형식**: `[타입] 구현 내용`  
- **예시**: `[UI] 메인 화면 UI 구현`  

### PR 컨벤션
- **제목 형식**: `[타입] - 작업 내용`  
- **예시**: `[UI] - 메인화면 UI 구현`  

### Commit 컨벤션
- **메시지 형식**: `#이슈번호 [타입] - 작업 내용`  
- **예시**: `#1 [UI] - RecyclerView 어댑터 구현`  

## 🛠️ 주요 기술 스택

-   **Framework:** Flutter
-   **Language:** Dart
-   **Backend:** Django
