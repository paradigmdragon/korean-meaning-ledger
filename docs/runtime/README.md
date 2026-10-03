# Semantic Runtime

Semantic Runtime은 Meaning Ledger를 실제 AI 판단에서 사용하기 위한 실행 계층입니다.

## Runtime이 하는 일

- 현재 입력에서 관련 Meaning 후보를 찾습니다.
- 동일·부분겹침·별개 의미를 구별할 근거를 제공합니다.
- 기준과 관계를 펼칩니다.
- 확인되지 않은 값을 억지로 고정하지 않습니다.
- 의미 차이가 후속 판단을 바꿀 때만 더 깊게 내려갑니다.
- 모델이 바뀌어도 같은 Meaning 정본을 재사용할 수 있게 합니다.

## Runtime이 하지 않는 일

- 특정 AI 모델 하나에 Meaning 정본을 종속시키지 않습니다.
- 모델 출력 하나를 canonical Meaning으로 자동 승격하지 않습니다.
- 모름이나 미확인을 오류로 강제 변환하지 않습니다.
- 구현 편의를 위해 서로 다른 Meaning을 합치지 않습니다.

## 모델과의 관계

```text
Meaning Ledger
      ↓
Semantic Runtime
      ↓
Model Adapter
      ↓
Jev 같은 의미 판단 AI / 다른 모델 / 도구
```

Jev는 가능한 소비자 또는 참조 사례일 수 있지만, 이 프로젝트의 본체는 특정 모델이 아닙니다.

## 목표

AI가 단순한 표면어 매칭을 넘어 의미의 범위·경계·관계를 사용할 수 있게 만드는 것.

즉:

```text
language
  → meaning candidates
  → distinction
  → contextual judgment
  → action
```
