# Study-Matching-Platform
(프로젝트의 간단한 한마디)

<br>

## Teams
(맴버들의 프로필, 닉네임)

<br>

## Branch Guide
- main: 최종 배포 (ver 1.0)
- develop: 다음 버전 준비 (ver 2.0)
- feature-관련 항목: 관련 항목에 대한 기능 구현

1. 여러 feature 브랜치가 만들어지고 완료된 경우 develop 브랜치에 PR 남김
2. PR에 대한 코드 리뷰 진행 (컨벤션 준수, 효율성, 개선점 등)
3. 리뷰 통과시 Merge

<br>

## PR Convention
### Format
```
type(Capitalization 적용): subject label

```

<br>

## Commit Convention

### Format

```
type: subject

body
```

<br>

## type

- 하나의 커밋에 여러 타입이 존재하는 경우 상위 우선순위의 타입을 사용한다.
- fix: 버스 픽스
- feat: 새로운 기능 추가
- refactor: 리팩토링 (버그픽스나 기능추가없는 코드변화)
- docs: 문서만 변경
- style: 코드의 의미가 변경 안 되는 경우 (띄어쓰기, 포맷팅, 줄바꿈 등)
- test: 테스트코드 추가/수정
- chore: 빌드 테스트 업데이트, 패키지 매니저를 설정하는 경우 (프로덕션 코드 변경 X)


## subject

- 제목은 50글자를 넘지 않도록 한다.
- 개조식 구문 사용
    - 중요하고 핵심적인 요소만 간추려서 (항목별로 나열하듯이) 표현
- 마지막에 특수문자를 넣지 않는다. (마침표, 느낌표, 물음표 등)

## body (optional)

- 각 라인별로 balled list로 표시한다.
    - 예시) - AA
- 가능하면 한줄당 72자를 넘지 않도록 한다.
- 본문의 양에 구애받지 않고 최대한 상세히 작성
- “어떻게” 보다는 “무엇을" “왜” 변경했는지 설명한다.
