# Governance

## 목적

이 프로젝트의 governance는 한글의미원장의 **의미 정체성, 변경 이력, 검수 책임**을 보호하기 위한 최소 규칙입니다.

## Canonical Meaning

Canonical Meaning은 현재 채택된 의미 정본입니다.

Canonical은 절대적 진리라는 뜻이 아니라, 현재 프로젝트가 재사용할 기준점이라는 뜻입니다.

## 역할

### Project Owner
- 프로젝트 방향과 최종 채택 책임
- 상업 라이선스 및 브랜드 관리
- governance 변경 승인

### Maintainer
- Meaning 및 Runtime 변경 검토
- 중복·충돌·revision 여부 확인
- 테스트와 provenance 확인

### Contributor
- Meaning, 사례, 반례, 코드, 문서 제안
- canonical 직접 변경이 아니라 검토 가능한 변경 제안

## 의미 변경 원칙

- 과거 revision을 지우지 않습니다.
- 최신 확정 revision은 이전 현행본보다 우선합니다.
- 이름이 같다는 이유로 다른 의미를 합치지 않습니다.
- 다른 언어의 번역 대응은 의미 동일성의 증거가 아닙니다.
- 구현 편의를 위해 Meaning을 합치지 않습니다.

## 중앙 검수

중앙 검수는 권위적 사전 편찬을 위한 절차가 아니라, 다음 AI와 사람이 같은 Meaning을 복원할 수 있도록 하기 위한 품질 게이트입니다.

검수 항목:

- 기존 Meaning과 중복 여부
- 표면어와 의미 정체성 분리
- 정의의 최소성
- 반례와 경계
- 출처와 provenance
- Runtime에서의 오용 가능성
- revision / 신규 Meaning 여부

## 변경 가능성

Governance 자체도 revision 대상입니다. 실제 기여와 운영 과정에서 불필요한 절차는 줄이고, 의미 보존에 필요한 규칙만 남깁니다.
