# \\# 🎮 GitHub Desktop으로 게임 프로젝트 리포지토리 업로드 가이드

# 

# 

# 

# GitHub Desktop을 활용하여 로컬에서 개발한 게임 프로젝트(Unity, Unreal, 인디 게임 등)를 GitHub 원격 저장소에 등록하고 관리하는 가이드입니다.

# 

# 

# 

# \\---

# 

# 

# 

# \\## 1. 사전 준비 (필수: .gitignore 설정)

# 

# 

# 

# 게임 엔진 프로젝트는 빌드 캐시, 임시 파일, 라이브러리 등 대용량 불필요 파일이 대량 생성됩니다.  

# 

# 리포지토리를 생성하기 전 \\\*\\\*반드시 `.gitignore` 파일을 프로젝트 루트 폴더에 추가\\\*\\\*해야 합니다.

# 

# 

# 

# \\\* \\\*\\\*권장:\\\*\\\* \\\[gitignore.io](https://www.toptal.com/developers/gitignore/)에 접속하여 본인의 개발 환경(예: `Unity`, `UnrealEngine`, `Godot`, `Visual Studio` 등)을 검색 후 생성된 내용을 복사해 `.gitignore` 파일로 저장합니다.

# 

# 

# 

# > ⚠️ \\\*\\\*주의 (Git LFS):\\\*\\\* 100MB를 초과하는 고화질 텍스처, 3D 모델(FBX), 음원 등은 \\\*\\\*Git LFS (Large File Storage)\\\*\\\* 설정을 권장합니다.

# 

# 

# 

# \\---

# 

# 

# 

# \\## 2. GitHub Desktop에 로컬 프로젝트 추가

# 

# 

# 

# 1\\. \\\*\\\*GitHub Desktop\\\*\\\* 실행 및 GitHub 계정 로그인 확인

# 

# 2\\. 상단 메뉴: `File` → `Add Local Repository...` (단축키: `Ctrl + O` / `Cmd + O`)

# 

# 3\\. `Choose...` 클릭 후 업로드할 게임 프로젝트의 \\\*\\\*최상위 폴더\\\*\\\* 선택

# 

# 4\\. `This directory does not appear to be a Git repository.` 경고가 뜨는 경우:

# 

# \&#x20;  \\\* 파란색 링크 \\\*\\\*`create a repository`\\\*\\\* 클릭

# 

# \&#x20;  \\\* 설정 창에서 이름 확인 및 Git Ignore 유형(예: Unity) 선택 후 \\\*\\\*`Create Repository`\\\*\\\* 클릭

# 

# 

# 

# \\---

# 

# 

# 

# \\## 3. 첫 번째 커밋 (First Commit)

# 

# 

# 

# 1\\. 좌측 변경 사항 탭(\\\*\\\*Changes\\\*\\\*)에서 의도하지 않은 대용량 캐시 폴더(예: Unity의 `Library/`, Unreal의 `Intermediate/`)가 제외되었는지 확인

# 

# 2\\. 좌측 하단 커밋 정보 입력:

# 

# \&#x20;  \\\* \\\*\\\*Summary (제목):\\\*\\\* `feat: Initial project commit`

# 

# \&#x20;  \\\* \\\*\\\*Description (설명):\\\*\\\* 프로젝트 초기 세팅 및 기본 에셋 추가 (선택 사항)

# 

# 3\\. \\\*\\\*`Commit to main`\\\*\\\* (또는 `master`) 버튼 클릭

# 

# 

# 

# \\---

# 

# 

# 

# \\## 4. 원격 리포지토리 발행 (Publish Repository)

# 

# 

# 

# 1\\. 상단 툴바의 \\\*\\\*`Publish repository`\\\*\\\* 버튼 클릭

# 

# 2\\. 세부 옵션 지정:

# 

# \&#x20;  \\\* \\\*\\\*Name:\\\*\\\* GitHub에 표시될 리포지토리 이름 지정

# 

# \&#x20;  \\\* \\\*\\\*Description:\\\*\\\* 게임에 대한 간단한 소개 입력

# 

# \&#x20;  \\\* \\\*\\\*Keep this code private:\\\*\\\* 비공개 저장을 원하면 체크, 오픈소스로 공개하려면 체크 해제

# 

# \&#x20;  \\\* \\\*\\\*Organization:\\\*\\\* 개인 계정 또는 팀 조직(Organization) 선택

# 

# 3\\. \\\*\\\*`Publish Repository`\\\*\\\* 버튼 클릭하여 업로드 완료

# 

# 

# 

# \\---

# 

# 

# 

# \\## 5. 작업 시 기본 루틴 (일상 작업 흐름)

# 

# 

# 

# \\\* \\\*\\\*Fetch origin / Pull:\\\*\\\* 작업 시작 전 원격 저장소의 최신 변경 사항 동기화

# 

# \\\* \\\*\\\*Commit:\\\*\\\* 특정 기능 단위(스크립트 작성, 씬 수정 등)로 커밋 분할

# 

# \\\* \\\*\\\*Push:\\\*\\\* 작업 완료 후 상단 `Push origin`을 눌러 원격 저장소에 반영



