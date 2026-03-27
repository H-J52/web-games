# 🌐 Web Games — 군대에서 메모장으로 만든 웹 게임 모음

![HTML](https://img.shields.io/badge/HTML-2b2d3f?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-2b2d3f?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-2b2d3f?style=flat-square&logo=javascript&logoColor=white)
![Solo](https://img.shields.io/badge/1인_개발-기획·개발·그래픽_전체-2b2d3f?style=flat-square)

> 군대 개인 정비 시간에 메모장과 브라우저만으로 완성한 웹 게임 5작품 모음

🎮 **[게임 목록 바로 플레이하기](https://H-J52.github.io/web-games/)**

<br>

## 🎮 게임 소개

Unity를 설치할 수 없는 군대 환경에서, 게임을 만들고 싶다는 마음을 포기하지 않았습니다.
개인 정비 시간에 **메모장(텍스트 에디터) + 브라우저만으로** HTML · CSS · JavaScript를 공부하며 웹 게임 5개를 완성했습니다.
환경의 제약이 오히려 웹 기술을 배우는 계기가 됐습니다.

**진행 기간:** 2026.01 ~ 2026.03  
**개발 환경:** 메모장 + 브라우저 (별도 IDE 없이 개발)  
**담당:** 기획 · 개발 · 그래픽 전체 (1인 개발)

<br>

## 🕹 게임 목록

| 게임 | 설명 | 인원 |
|---|---|---|
| 🍎 [사과 게임](https://H-J52.github.io/web-games/apple/apple.html) | 드래그로 합이 10인 숫자를 제거하는 퍼즐 게임 | 1인용 |
| 🔫 [ONE BULLET : DUEL](https://H-J52.github.io/web-games/duel/duel.html) | 단 한 발로 상대를 먼저 맞춰야 하는 1v1 대전 | 2인용 |
| 🚀 [Neon 2P PvP Shooter](https://H-J52.github.io/web-games/spaceShoot/spaceShoot.html) | 네온 배경의 2인 우주 슈팅 대전 | 2인용 |
| 🧮 [Target Calc](https://H-J52.github.io/web-games/targetCalc/targetCalc.html) | 주어진 숫자로 목표값을 만드는 수학 퍼즐 | 1인용 |
| 🎲 [Mini Yacht](https://H-J52.github.io/web-games/yacht/yacht.html) | 주사위로 점수를 쌓는 클래식 야추 | 멀티 |

<br>

## 🛠 기술 스택

`HTML` `CSS` `JavaScript`

<br>

## 🌱 기술적 도전

### 1. Unity 없이도 게임을 만들 수 있다는 것

군대라는 제약된 환경에서 Unity 없이 게임을 만들어야 했습니다. HTML 파일 하나로 브라우저에서 바로 실행되는 구조를 발견하고 가능성을 봤습니다.

Canvas API, 키보드 이벤트, `requestAnimationFrame` 같은 웹 기술로 Unity에서 하던 것들을 구현할 수 있었습니다.

→ 게임 루프, 충돌 처리, 상태 관리 — **도구가 달라도 개념은 동일하다**는 걸 배웠습니다.

### 2. JavaScript로 게임 루프 직접 설계

Unity에서는 `MonoBehaviour`의 `Update()`가 게임 루프를 관리해줍니다. 웹에서는 `requestAnimationFrame`으로 직접 게임 루프를 구성해야 했습니다.

상태 관리, 충돌 감지, 점수 계산까지 직접 설계하면서, Unity가 내부적으로 어떤 역할을 하는지 더 깊이 이해하게 됐습니다.

### 3. 제약이 오히려 창의성을 자극한다

5개의 게임 모두 슈팅, 전략, 퍼즐, 논리 등 **다른 장르**를 시도했습니다. 같은 HTML/CSS/JS라는 도구로 전혀 다른 게임 경험을 만들 수 있다는 게 흥미로웠습니다.

→ 환경의 제약이 없었다면 웹 기술을 탐험하지 않았을 수도 있습니다. 제약이 오히려 성장의 계기가 됐습니다.

<br>

## 📁 파일 구조

```
web-games/
├── index.html              ← 게임 목록 메인 페이지
├── apple/
│   └── apple.html
├── duel/
│   └── duel.html
├── spaceShoot/
│   └── spaceShoot.html
├── targetCalc/
│   └── targetCalc.html
└── yacht/
    └── yacht.html
```

<br>

