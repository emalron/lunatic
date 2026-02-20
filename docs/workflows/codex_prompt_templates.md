# Codex Prompt Templates

아래 템플릿에서 문서 경로만 바꿔서 바로 사용하세요.

---

## 템플릿 A: 시스템 초안 요청
```text
다음 문서를 참고해 [시스템명] 초안을 작성해줘.
우선순위:
1) docs/game-design/GDD.md
2) docs/specs/core-loop.md
3) docs/research/market_report_summary.md

요구사항:
- GDD의 핵심 경험을 훼손하지 말 것
- 모바일 한 손 플레이 기준 유지
- 출력 형식: 핵심 규칙 / 수치 초안 / 리스크 / 검증 계획
- 문서 충돌 시 충돌 지점 먼저 요약
```

## 템플릿 B: 기능 구현 작업 요청
```text
아래 문서를 기준으로 [기능명] 구현 계획을 만들어줘.
참고 문서:
- docs/INDEX.md
- docs/game-design/GDD.md
- docs/specs/core-loop.md

산출물:
1) 작업 분해(WBS)
2) 필요한 데이터 구조
3) 테스트 체크리스트
4) 미확정 이슈 질문 리스트
```

## 템플릿 C: 밸런스 조정 요청
```text
다음 문서를 기반으로 초반 10분 구간 밸런스 조정안을 제안해줘.
- docs/game-design/GDD.md
- docs/specs/core-loop.md
- docs/research/market_report_summary.md

조건:
- 튜토리얼 이탈률 개선이 목표
- 변경 항목마다 예상 KPI 영향과 리스크를 한 줄씩 기입
- 실험 우선순위를 P0/P1/P2로 분류
```

## 템플릿 D: 문서 충돌 점검
```text
다음 문서들의 충돌을 점검해줘.
- docs/game-design/GDD.md
- docs/specs/core-loop.md
- docs/lore/world_setting.md

출력 형식:
- 충돌 항목
- 영향도(높음/중간/낮음)
- 해결 제안
- 결정이 필요한 담당자
```
