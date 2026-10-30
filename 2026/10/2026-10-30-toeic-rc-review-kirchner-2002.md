# 2026-10-30 · 토익 모의 1회 RC 복습 (P5·P6) · Floor Field 원 논문 ② Kirchner 2002 시작

> 편입 준비(최상위 계획). 토익 정기시험(10/31) 전날. 모의 1회에서 흔들린 RC 19문제를 근거와 함께 다시 풀고, Floor Field 0단계 논문 읽기를 이어 갔다.

## 주제
1. 토익 모의 1회(ETS 기출 1000 Vol.5 TEST 1) RC 복습: P5 13문제 + P6 6문제를 선택지를 가리고 다시 풀고, 공책에 규칙 10줄과 단어를 정리했다.
2. Floor Field 원 논문 ② Kirchner & Schadschneider (2002), *Simulation of evacuation processes using a bionics-inspired cellular automaton model for pedestrian dynamics* (Physica A 312): 단계 0~2.

## 1. 토익 RC 복습

### 핵심 개념
1. **품사 자리는 단어 모양이 아니라 자리로 정한다.** 형용사는 명사를 꾸미고, 부사는 동사·형용사·문장을 꾸민다. last처럼 형용사와 부사 모양이 같은 단어도 있다 (102).
2. **"빈칸 + 명사"는 형용사가 먼저다.** 명사로 판정한 130번(diagnostic fee)이 틀렸다. 명사+명사 복합어는 형용사 선택지가 뜻이 안 될 때만 쓴다.
3. **5형식 find + 목적어 + 형용사.** 부사로 판정한 143번(found our services satisfactory)이 틀렸다.
4. **전치사 vs 접속사는 121번만 그 기준으로 풀렸다.** 117(role in), 128(rather than), 145(For instance)은 고정 표현·뜻·접속부사 문제였다.
5. **부정의 뜻이 어디에 있나**: neither·nobody는 혼자 부정이고, anybody는 not과 함께여야 부정이다 (120).

### 공책 뒤쪽 규칙 10줄
```
[품사]
1. 관사 ___ 명사 → 형용사 자리. 분사는 뜻까지 확인 (lasted ✕)              (102)
2. ___ + 명사 → 형용사 우선 (명사+명사는 형용사 선택지가 뜻이 안 될 때만)      (130)
3. find/keep/make + 목적어 + ___ → 형용사 (목적어의 상태)                     (143)
[전치사·접속사·연결어]
4. ___ + 명사(구) → 전치사 / ___ + 주어+동사 → 접속사                        (121)
5. 문장 맨 앞 ___ , → 접속부사: 앞 문장과 관계로 고름 (예시 / 반대 / 결과)    (145)
6. rather than = B가 아니라 A, 앞뒤 같은 형태 → 품사 말고 뜻으로              (128)
[대명사]
7. not 없는데 "아무도 ~않다" → neither(둘) / nobody·none(셋 이상)             (120)
8. no- = 혼자 부정 / any- = not과 함께여야 부정                               (120)
[P6]
9. 광고·안내문의 소유격 빈칸 → 글쓴이가 회사면 our                            (134)
10. 문장 삽입 → 빈칸 앞 문장 + 뒤 문장을 둘 다 이어 주는 것                    (141)
```

### 공책 앞쪽 단어 (덩어리)
play a role in -ing · status update · compensate for · accumulate · commercial supplier / lumber · diagnostic fee · precisely locate · study diligently · with any certainty · cooperative agreement / disruptive · be grateful for · with great dedication / deduction / declaration · reach a milestone · productivity · infinitely · sincerely · decidedly · unmatched · to repeat · otherwise · consequently · somehow · nevertheless

- 맞힌 문제(113·123·127)에 동그라미 친 단어도 사진에서 찾아 함께 정리했다. 오답 노트 DB에는 흔들린 문제만 기록되기 때문이다.

### 막혔던 점과 해결
- **102번**: 형용사 자리라고 판정했는데 답이 부사인 줄 알았다. → 답 last는 이 문장에서 형용사다. last는 형용사와 부사 모양이 같다.
- **120번**: neither와 anybody를 넣어 봐도 같은 뜻으로 해석돼서 고민했다. 문법 판정은 하지 않았다. → anybody는 not이 없으면 부정이 안 된다. nobody와 anybody를 헷갈렸다.
- **119번**: "부족한 경험을 경험해 보게 하다"로 읽었다. → compensate for = 보완하다·메우다.
- **패턴**: 해석만으로 고르면 두 답이 같은 뜻으로 보인다. 그때가 문법(부정어 위치, 대상 수, 빈칸 뒤 명사·절)을 확인할 때다.

### 정리 방식 결정
- 규칙과 단어는 종이 공책 한 권(앞 단어 / 뒤 규칙)에만 정리한다. 카테고리 칸 나누기와 Notion 규칙 모음은 쓰지 않기로 했다. 매일 보기 쉬운 게 우선이다.

## 2. Floor Field ② Kirchner 2002 (단계 0~2)

### 단계 0. 워밍업
- ① Burstedde 식 (3)을 책 덮고 다시 썼다. Δ 안에는 지도 값(s·d)이 들어가고, n은 (1 − n)에만 나온다. 10/20의 빈틈이 해결됐다.
- Burstedde에서 미확인이던 두 곳을 PDF 렌더링으로 확인했다. 식 (5)·(6)에 β가 있고, Fig.4 캡션의 "= 10"은 β다.

### 단계 1. 훑어보기 (Abstract · Conclusions)
- 내 말로 한 문장: 대피 상황에서 두 개의 파라미터(출구를 얼마나 아는지, 사람을 얼마나 따라가는지)를 가지고 대피 시간을 시뮬레이션해 보았을 때, herding behaviour와 use of knowledge가 적절한 조합을 이루는 것이 중요하다는 것을 알게 되었다.
- 핵심: k_S = 출구 지식, k_D = 따라가기(herding). 대피 시간은 k_D에 대해 non-monotonic(U자)이고, 중간에서 가장 짧다. 파라미터만 바꿔서 평상시부터 패닉까지 표현한다.
- 이 모델은 각자 옆 칸 지도만 보니까 계산량이 O(N)이다. social-force 모델은 O(N²)이다.

### 단계 2. 두 지도와 업데이트 규칙 (설명까지, 「내 말로」는 다음에)
- S: 고정. 출구까지 최단 거리 기반이고, 문 칸이 가장 크다.
- D: 가상 발자국. 칸을 떠나면 +1. 매 스텝 알갱이마다 확률 δ로 사라지고(decay), 확률 α로 이웃 칸으로 옮겨 간다(diffusion). 움직인 사람만 남기므로 속도 밀도다.
- 식 (1):
  ```
  p_ij = N · exp(k_D·D_ij) · exp(k_S·S_ij) · (1 − n_ij) · ξ_ij
  ξ_ij = 0 (벽) / 1 (그 밖)
  ```
- 한 스텝 5단계: D 감쇠·확산 → 확률 계산 → 목표 칸 선택 → 충돌 해결 → 움직인 사람이 D +1.

## 다음에 할 것
- 10/31 토익 정기시험 (09:20, 울산 약사중). 시험 전 공책 뒤쪽 규칙 10줄 훑기.
- 모의 2회 실전 + 채점 + `/toeic 02` (오늘 못 함).
- Kirchner 단계 2 「내 말로」 3줄 → 단계 3(k_S·k_D, Fig.5).
- P7 삼중지문 복습은 시험 뒤로 미룸.
