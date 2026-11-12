# 디지몬 스토리 선버스트 한글 패치 v1.0.0

일본판 Nintendo DS용 한글 패치입니다. **[릴리스에서 xdelta 다운로드](https://github.com/TeamLimRyan/DIGIMON_STORY_SUNBURST_KOREAN_LOCALIZATION_RELEASE/releases/tag/v1.0.0)**

패치 파일: [`DIGIMON_STORY_SUNBURST_KO_v1.0.0.xdelta`](DIGIMON_STORY_SUNBURST_KO_v1.0.0.xdelta)

## 원본·적용 후·패치 해시

| 대상 | 크기(bytes) | SHA-256 |
|---|---:|---|
| 원본 일본판 ROM | 67108864 | `47d61774d5923f1aff936d9e6adc43f7a376fb12186ab1fa64ceddeafb44f723` |
| 패치 적용 후 ROM | 67108864 | `3a6585aabedb58fe0adbf304303b4db728b5bb688e692b73f410ffb6eb8ad6ca` |
| xdelta 패치 | 559212 | `a3964276c4d1faa0db8b15199f7959481d92596d024da895bcb1ab9475bbd7d8` |

원본 해시가 일치하는 ROM에만 적용하세요. 다른 지역판, 다른 버전, 트리밍한 ROM, 이미 수정한 ROM은 지원하지 않습니다.

## 적용 방법

1. 직접 보유한 일본판 원본의 SHA-256을 위 표와 비교합니다.
2. xdelta3로 아래 명령을 실행합니다. 원본과 출력은 서로 다른 파일이어야 합니다.

```text
xdelta3 -d -s "original.nds" "DIGIMON_STORY_SUNBURST_KO_v1.0.0.xdelta" "korean.nds"
```

3. `korean.nds`의 SHA-256을 적용 후 해시와 비교합니다.

[상세 설치·복구](INSTALL.md) · [호환성과 검증 범위](COMPATIBILITY.md) · [문제 신고](SUPPORT.md) · [권리 안내](NOTICE.md)

게임 ROM, BIOS, 세이브, 키는 포함하지 않습니다. 비공식 한국어화 패치입니다.
