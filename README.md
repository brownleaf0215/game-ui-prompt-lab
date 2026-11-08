# Game UI Prompt Lab

게임 UI 디자인용 프롬프트를 만드는 도구입니다. 화면 종류, 기기, 장르, 아트 스타일, 분위기, 색상, 넣을 요소를 고르면 원하는 AI에 맞는 형식으로 프롬프트를 만들어 줍니다.

사용: https://brownleaf0215.github.io/game-ui-prompt-lab/

`index.html` 파일 하나로 동작하므로 내려받아 오프라인에서도 쓸 수 있습니다.

## 출력 형식

| 대상 | 내용 |
|---|---|
| 자연어 이미지 AI | GPT 이미지, Gemini, Ideogram 등에 쓰는 문장형 프롬프트 |
| Midjourney | 쉼표로 나눈 키워드와 `--ar`, `--no` 파라미터 |
| Stable Diffusion | 태그와 네거티브 프롬프트 |
| HTML/CSS | 코딩 AI에게 단일 파일 목업을 요청하는 명세 |
| Unity UI Toolkit | UXML, USS, C#을 요청하는 명세(색상 토큰, PanelSettings, 세이프 에어리어 포함) |
| Unity uGUI | Canvas와 TextMeshPro로 화면을 만드는 에디터 스크립트 요청 명세 |

영어와 한국어 중 출력 언어를 고를 수 있습니다. 이미지 AI는 영어 프롬프트를 더 정확하게 따릅니다.

## 기능

- 색상 프리셋 8종과 5가지 역할(배경, 패널, 주색, 보조색, 글자)의 직접 지정
- 색, 모서리, 깊이감을 보여 주는 간단한 미리보기와 글자 대비 수치
- 무작위 조합
- 설정 저장, 최근 복사 기록, JSON 백업과 가져오기(브라우저 localStorage에 저장)
- 현재 설정을 담은 공유 링크

## 라이선스

MIT
