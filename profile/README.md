# Good Vibe Team

감정과 상황에 맞는 문화예술 경험을 추천하는 서비스 **MUUD**를 개발한 팀입니다.

MUUD는 사용자가 복잡한 조건을 직접 검색하지 않아도, 현재 기분과 위치를 바탕으로 가까운 문화예술 행사를 발견할 수 있도록 돕는 웹 서비스입니다.

## MUUD

**MUUD**는 질문 기반 문화예술 추천 서비스입니다.

사용자는 짧은 질문에 답하고, 서비스는 사용자의 현재 위치, 날씨, 미세먼지, 감정 상태를 함께 고려해 지금 가기 좋은 문화예술 행사를 추천합니다.

| 항목         | 내용                                     |
| ---------- | -------------------------------------- |
| Service    | MUUD / Good Vibe                       |
| Production | https://muud-one.vercel.app/           |
| Repository | https://github.com/good-vibe-team/muud |
| Team       | Good Vibe Team                         |

## Preview

<p>
  <img src="./images/location.png" width="220" alt="위치설정화면">
  <img src="./images/questions.png" width="220" alt="질문선택화면">
  <img src="./images/questions_result.png" width="220" alt="결과화면">
</p>

## 주요 기능

| 기능        | 설명                                       |
| --------- | ---------------------------------------- |
| 질문 기반 추천  | 사용자의 감정과 상황을 질문으로 수집해 문화예술 행사를 추천합니다.    |
| 위치 기반 탐색  | 현재 위치 또는 사용자가 설정한 위치를 기준으로 주변 행사를 탐색합니다. |
| 날씨·대기질 반영 | 날씨와 미세먼지 정보를 추천 문구와 행사 추천에 반영합니다.        |
| 관심 행사 저장  | 마음에 드는 행사를 저장하고 다시 확인할 수 있습니다.           |
| 마이페이지     | 최근 추천 결과와 관심 행사를 확인할 수 있습니다.             |


## 서비스 흐름

<table>
  <tr>
    <td width="50%" valign="top">
      <strong>추천 플로우</strong>
      <br /><br />
      <pre>
추천받기 진입
→ 추천 사용 가능 여부 확인
→ 위치 확인 또는 수동 위치 설정
→ 질문 답변
→ 날씨·미세먼지 반영
→ 문화예술 행사 추천
→ 관심 행사 저장 또는 상세 확인
      </pre>
    </td>
    <td width="50%" align="center" valign="top">
      <strong>추천 플로우 화면</strong>
      <br /><br />
      <img src="./images/recommendations-flow.gif" width="260" alt="추천플로우">
    </td>
  </tr>
</table>

## Tech Stack

| 구분           | 기술                                       |
| ------------ | ---------------------------------------- |
| Framework    | Next.js App Router                       |
| Language     | TypeScript                               |
| UI           | React                                    |
| Styling      | Tailwind CSS                             |
| Server State | TanStack Query                           |
| ORM          | Prisma                                   |
| Database     | Supabase PostgreSQL                      |
| Map          | Kakao Maps JavaScript SDK                |
| External API | 문화행사 API, 기상청 API, 에어코리아 API, Gemini API |
| Deploy       | Vercel                                   |

## Team

| 이름  | 역할                                |
| --- | --------------------------------- |
| 신성우 | Team Lead / Full-stack / PM |
| 강송희 | design / Full-stack / PD               |
| 민정아 | Full-stack / AI                              |
| 채준병 | Full-stack                                 |
| 우스만 | Full-stack                                |

## Documents

| 문서 | 설명 |
| --- | --- |
| [PRD](https://full-steam-0ff.notion.site/PRD-v1-4-37d6f75da60e81b9b6d1e005f9ed6055) | 서비스 목적, 사용자 문제, MVP 범위 |
| [요구사항 정의서](https://full-steam-0ff.notion.site/MUUD-v1-1-PRD-v1-4-3826f75da60e81b5bcadf4a5f602b5ce) | 화면과 도메인별 기능 요구사항 |
| [ERD](https://full-steam-0ff.notion.site/ERD-v1-0-v1-0-3826f75da60e8159ac9bf3eb13543dc4) | 데이터 구조와 관계 |
| [TDD](https://full-steam-0ff.notion.site/TDD-v1-6-3836f75da60e81b0bcc7c794f872d10e) | 기술 스택, 아키텍처, 구현 기준 |
| [API 명세서](https://full-steam-0ff.notion.site/587212a1a47a4825ad1d98f8bf6a30de?v=3816f75da60e81f2b9f2000c18422c64) | 내부 API 요청·응답 기준 |
| [Git 협업 전략](https://github.com/good-vibe-team/muud/blob/main/docs/git-strategy.md) | Issue, Branch, Commit, PR 규칙 |

## Repository

* MUUD Repository: https://github.com/good-vibe-team/muud

