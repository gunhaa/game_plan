# Game Plan

여러 게임 기획 문서를 관리하는 저장소입니다.

## 구조

```
game_plan/
├── _templates/            # 문서 작성용 공통 템플릿
└── [게임 코드네임]/        # 게임 하나당 폴더 하나
    ├── README.md           # 게임 개요 및 기획 목적
    ├── comparisons/        # 이 게임에 참고한 비교군 분석
    ├── design/             # 실제 기획 문서
    └── archive/            # 보류/폐기 아이디어
```

## 사용 방법

### 새 게임 기획 시작
1. `[게임 코드네임]/` 폴더 생성
2. 내부에 `comparisons/`, `design/`, `archive/` 폴더 생성
3. `_templates/design_template.md` 참고해 `design/gdd.md` 작성
4. 아래 게임 목록 표에 추가

### 비교군 추가
해당 게임 폴더의 `comparisons/` 아래에 분석할 게임 이름으로 폴더를 만들고  
`_templates/comparison_template.md`를 복사해 작성합니다.

## 게임 목록

| 폴더명 | 게임명 | 장르 | 상태 | 비교군 |
|--------|--------|------|------|--------|
| `chat_please` | Chat, Please | 퍼즐 / 시뮬레이션 | 기획 중 | Papers, Please |
