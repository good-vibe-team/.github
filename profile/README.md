# AI Vibe Coding Frontend Project

이 Organization은 AI 바이브코딩 프론트엔드 실무과정에서 진행하는 파이널 프로젝트를 위한 협업 공간입니다.

아직 프로젝트 주제는 확정되지 않았으며, 주제 확정 이후 서비스 소개, 주요 기능, 배포 링크, 기술 스택 등을 순차적으로 업데이트할 예정입니다.

## 목적

이 프로젝트의 목적은 단순히 기능을 구현하는 것에 그치지 않고, 실제 개발 협업 흐름을 경험하는 것입니다.

팀은 GitHub Issue, Branch, Pull Request, Code Review를 기반으로 작업을 진행하며, 프로젝트가 끝났을 때 코드뿐만 아니라 협업 과정과 문서도 함께 남기는 것을 목표로 합니다.

## Repository

| Repository | 설명 |
| --- | --- |
| `frontend` | 프론트엔드 애플리케이션 개발 |
| `backend` | 백엔드 API 및 서버 로직 개발 |

추후 프로젝트 구조가 변경되면 Repository 목록도 함께 업데이트합니다.

## 협업 방식

이 프로젝트는 GitHub Flow를 기반으로 진행합니다.

기본 흐름은 다음과 같습니다.

```txt
Issue 생성
→ Branch 생성
→ 작업 진행
→ Commit
→ Pull Request 생성
→ Code Review
→ main 브랜치 병합
````

## Branch 규칙

```txt
type/#issue-number-short-description
```

예시:

```txt
feature/#1-login-page
fix/#2-header-layout
refactor/#3-user-service
docs/#4-readme-update
```

## Commit 규칙

```txt
type: 작업 내용 (#이슈번호)
```

예시:

```txt
feat: 로그인 페이지 구현 (#1)
fix: 모바일 헤더 레이아웃 수정 (#2)
docs: README 실행 방법 추가 (#4)
```

## Issue / Pull Request

모든 작업은 Issue를 먼저 생성한 뒤 진행합니다.

Pull Request에는 관련 Issue, 작업 내용, 확인 방법, 리뷰 요청 사항을 작성합니다.

```txt
Closes #이슈번호
```

형식으로 Issue와 PR을 연결합니다.

## 문서

각 Repository에는 필요한 문서를 함께 관리합니다.

| 문서                           | 설명                    |
| ---------------------------- | --------------------- |
| `docs/git-strategy.md`       | Git 협업 전략             |
| `docs/backend-convention.md` | Backend 협업 규칙         |
| `README.md`                  | Repository 소개 및 실행 방법 |

## 업데이트 예정

프로젝트 주제 확정 후 아래 내용을 추가할 예정입니다.

* 서비스 이름
* 서비스 한 줄 소개
* 주요 기능
* 기술 스택
* 아키텍처
* 배포 URL
* 팀원 역할
* 최종 발표 자료

