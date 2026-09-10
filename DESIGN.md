---
version: alpha
name: Notion Analysis
description: A warm, paper-calm system built on an off-white canvas, near-black Inter type, and a single confident blue, punctuated by a playful multi-color sticker palette that does the personality work while the chrome stays quiet.

colors:
  primary: "#0075de"
  primary-active: "#005bab"
  secondary: "#213183"
  on-primary: "#ffffff"
  canvas: "#ffffff"
  canvas-soft: "#f6f5f4"
  surface: "#ffffff"
  ink: "#000000"
  ink-secondary: "#31302e"
  ink-muted: "#615d59"
  ink-faint: "#a39e98"
  hairline: "#e6e6e6"
  accent-sky: "#62aef0"
  accent-purple: "#d6b6f6"
  accent-purple-deep: "#391c57"
  accent-pink: "#ff64c8"
  accent-orange: "#dd5b00"
  accent-orange-deep: "#793400"
  accent-teal: "#2a9d99"
  accent-green: "#1aae39"
  accent-brown: "#523410"

typography:
  display-1: { fontFamily: Inter, fontSize: 64px, fontWeight: 700, lineHeight: 1.0,  letterSpacing: -2.125px }
  display-2: { fontFamily: Inter, fontSize: 54px, fontWeight: 700, lineHeight: 1.04, letterSpacing: -1.875px }
  heading-1: { fontFamily: Inter, fontSize: 40px, fontWeight: 700, lineHeight: 1.1,  letterSpacing: -1px }
  heading-2: { fontFamily: Inter, fontSize: 26px, fontWeight: 700, lineHeight: 1.23, letterSpacing: -0.625px }
  heading-3: { fontFamily: Inter, fontSize: 22px, fontWeight: 700, lineHeight: 1.27, letterSpacing: -0.25px }
  title:     { fontFamily: Inter, fontSize: 20px, fontWeight: 600, lineHeight: 1.4,  letterSpacing: -0.125px }
  body-md:   { fontFamily: Inter, fontSize: 16px, fontWeight: 400, lineHeight: 1.5,  letterSpacing: 0 }
  body-sm:   { fontFamily: Inter, fontSize: 15px, fontWeight: 400, lineHeight: 1.33, letterSpacing: 0 }
  button:    { fontFamily: Inter, fontSize: 16px, fontWeight: 500, lineHeight: 1.5,  letterSpacing: 0 }
  caption:   { fontFamily: Inter, fontSize: 14px, fontWeight: 400, lineHeight: 1.43, letterSpacing: 0 }
  eyebrow:   { fontFamily: Inter, fontSize: 12px, fontWeight: 600, lineHeight: 1.33, letterSpacing: 0.125px }

rounded:
  xs: 4px
  sm: 5px
  md: 8px
  lg: 12px
  xl: 16px
  full: 9999px

spacing:
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 28px
  xxl: 32px
---

## 출처

getdesign.md의 Notion 디자인 시스템 분석에서 가져온 디자인 토큰입니다.
원본: https://getdesign.md/design-md/notion

공개된 패턴을 독립적으로 분석한 자료이며 Notion과는 무관합니다.
Notion 및 로고는 해당 권리자의 상표입니다.

## 적용 원칙

- 페이지 바닥은 순백이 아닌 따뜻한 오프화이트(`canvas-soft`). 화면의 임상적인 느낌을 덜어내고
  문서처럼 읽히게 한다.
- 본문 카드만 순백(`surface`)으로 띄워 종이 한 장이 놓인 것처럼 보이게 한다.
- 색은 거의 쓰지 않는다. 파랑(`primary`)은 링크와 주요 동작에만 쓴다.
- 성격은 스티커 팔레트(purple, teal, pink, orange...)가 담당한다. 작은 요소에만 쓴다.
- 제목은 큰 크기 + 음수 자간. 클수록 자간을 더 좁힌다.
- 원본 폰트는 NotionInter(자체 폰트)이며, 공개 대체 폰트로 Inter를 쓴다.
