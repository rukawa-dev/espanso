# Agent Guidelines

## Espanso Match Rules
- **Dual Trigger Requirement (영문 + 한글 트리거)**: 새로운 espanso 매치를 추가하거나 수정할 때는, 영문 트리거와 함께 두벌식 키보드 기준 한글 입력 대비 트리거를 `triggers: ["::eng", "::kor"]` 형식으로 한 항목(Match) 안에 함께 정의해야 합니다.
  - 예시: `triggers: ["::time", "::샤ㅡㄷ"]`, `triggers: ["::uid", "::ㅕㅑㅇ"]`, `triggers: ["::az", "::ㅁㅋ"]`
