# Sample Project

과제용 샘플 프로젝트 구조입니다. 실제 프로젝트 코드가 생기면 이 자리에 복제해 넣고 feature 브랜치 워크플로로 관리합니다.

## 워크플로
1. `git checkout -b feature/<작업명>` — 기능별 브랜치 생성
2. 작업 후 `git add` → `git commit` → `git push -u origin feature/<작업명>`
3. GitHub에서 PR 생성, 리뷰 후 main으로 merge
4. 로컬에서 `git checkout main && git pull` → 작업 브랜치 정리
