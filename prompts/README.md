# Claude Code 프롬프트 모음

KRIS (Slack Bot)가 수행했던 작업들을 Claude Code에서 재현할 수 있는 프롬프트 모음입니다.

## 프롬프트 목록

| 파일 | 설명 | 용도 |
|------|------|------|
| [image-analysis.md](./image-analysis.md) | 이미지 분석 프롬프트 | 이미지를 보고 상세하게 설명 |
| [timestamp-summary.md](./timestamp-summary.md) | 타임스탬프 요약 프롬프트 | 채팅/로그를 간결하게 정리 |

## 사용 방법

### 1. 이미지 분석
```bash
# Claude Code에서 이미지 파일 분석
"이 이미지를 분석해줘: /path/to/image.jpg"

# URL 이미지 분석
"이 이미지를 분석해줘: https://example.com/image.png"
```

### 2. 타임스탬프 정리
```bash
# 채팅 내용을 붙여넣은 후
"위 내용을 타임스탬프별로 정리해줘. 한 행당 20자 이내로."
```

## 원본 작업 (Slack 스레드)

이 프롬프트들은 다음 Slack 스레드에서 KRIS가 수행한 작업을 기반으로 작성되었습니다:
- 이미지 설명 요청 -> 상세한 장면 분석 출력
- 타임스탬프 정리 요청 -> 간결한 로그 형식 출력
