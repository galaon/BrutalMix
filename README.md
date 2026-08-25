# 브루탈믹스 (BrutalMix) 폰트

내가 쓰고싶어서 AI 시켜서 만든 밤티나는(중요) 폰트입니다. 이것저것 되는대로 '무자비하게 뒤섞어놔서' 브루탈믹스 입니다.

한글 : 나눔스퀘어 / 영문 : Rajdhani (일부 글자만 Cairo) / 문장부호 : Spoqa 한 산스 네오

원 폰트의 저작권은 원 저작자에게 있습니다. 변경 및 가공 라이센스를 제공해주신 원 저작자 분들에게 감사의 말씀을 드립니다.

| 번호 | 웨이트 | 파일 |
|---|---|---|
| 01 | Light | `fonts/BrutalMix_01_Light.ttf` |
| 02 | Regular | `fonts/BrutalMix_02_Regular.ttf` |
| 03 | Bold | `fonts/BrutalMix_03_Bold.ttf` |
| 04 | ExtraBold | `fonts/BrutalMix_04_ExtraBold.ttf` |
| 05 | Heavy | `fonts/BrutalMix_05_Heavy.ttf` |
| 06 | Black | `fonts/BrutalMix_06_Black.ttf` |

## 견본

![BrutalMix 견본](images/specimen.png)

- **통합 파일**: `fonts/BrutalMix.ttc` — 6웨이트가 하나에 담긴 컬렉션.
  일러스트레이터·프리미어·애프터이펙트 등 데스크톱 앱용.
- **웹/Remotion 등**: TTC 미지원 환경에서는 개별 `.ttf`를 사용하세요.

## 제작 방식

이 폰트는 아래 4종의 오픈 폰트를 **글리프 단위로 병합**하여 만든 파생 폰트입니다.

- **한글** — 나눔스퀘어 네오 (NanumSquare Neo)
- **라틴 알파벳·숫자·괄호·특수문자** — Rajdhani
- **K, k (이 두 글자만)** — Cairo
- **문장부호(쉼표·마침표·따옴표·가운데점 등)** — Spoqa 한 산스 네오

각 폰트의 정렬 기준(베이스라인·글자 높이)이 서로 달라, 나눔스퀘어 네오가
자신의 라틴·부호를 배치한 위치를 기준으로 나머지 폰트를 맞춰 정렬했습니다.
Black 웨이트는 Heavy를 균일 팽창하여 합성한 웨이트입니다.

## 라이선스

이 파생 폰트(BrutalMix)는 **SIL Open Font License 1.1** 로 배포됩니다. → [`OFL.txt`](OFL.txt)

사용한 원본 폰트의 저작권자와 라이선스는 [`licenses/THIRD-PARTY-NOTICES.md`](licenses/THIRD-PARTY-NOTICES.md)
에 정리되어 있습니다. 요약하면:

- 4종 모두 자유로운 **사용·수정·병합·재배포**가 가능합니다.
- **폰트 파일 자체를 유료로 판매하는 것은 금지**됩니다. (무료 배포는 허용)
- 파생물도 **같은 오픈 라이선스**로만 배포할 수 있습니다.
- 원본 이름(NanumSquare/Nanum, Rajdhani, Spoqa, Cairo)은 이 폰트 이름에
  사용하지 않았습니다. "브루탈믹스 / BrutalMix"는 독립된 이름입니다.

> **저작권 및 상표 주의**
> - "NanumSquare Neo"는 (주)네이버의 **등록상표**입니다. 이 이름을 파생 폰트 이름에
>   쓸 수 없으며, 본 폰트는 사용하지 않습니다.
> - 원저작자들이 이 파생물을 보증·승인한 것은 아닙니다. 본 저장소는 원본을
>   병합했다는 **사실을 출처로 밝히는 것**이며, 원저작자의 추천을 의미하지 않습니다.

## 사용한 원본 (출처)

- 나눔스퀘어 네오 — © 2022 NAVER Corp., 제작 Sandoll Inc. — https://hangeul.naver.com/font
- Rajdhani — © 2014 Indian Type Foundry — Google Fonts (OFL)
- Spoqa 한 산스 네오 — © 2020 Spoqa — https://spoqa.github.io/spoqa-han-sans/
- Cairo — © 2009 The Cairo Project Authors — Google Fonts (OFL)

## 면책

이 저장소의 라이선스 정리는 참고용이며 법적 자문이 아닙니다. 배포 전 각 원본
폰트의 **공식 배포처 라이선스 원문**(특히 예약 폰트 이름 지정 여부)을 직접
확인하시기 바랍니다.
