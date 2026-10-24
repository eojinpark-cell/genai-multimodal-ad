# 하다 보면 끝남 — AI 브랜드 광고 스토리보드

(재)이노베이션아카데미 경영관리팀 · 계약 업무 인식 개선 광고 · 32초

## 1. 브랜드 아이덴티티

| 항목 | 내용 |
|---|---|
| 브랜드명 | 하다 보면 끝남 |
| 타겟 | 이노베이션아카데미 직원 중 계약 업무를 처음 맡거나 어려워하는 담당자 |
| 톤앤매너 | 이성적·논리적. 차분한 남색·흰색 톤의 플랫 3D 일러스트, 담담한 내레이션 |
| 차별점(USP) | 막연한 감이 아니라 법령 조문과 실무 선례를 근거로, 계약 절차를 단계별로 쪼개 보여준다 (추정가격 → 계약방법 → 견적 → 계약보증금 → 검사·대가) |

## 2. 캠페인 목표 / 핵심 메시지

| 항목 | 내용 |
|---|---|
| 광고 목적 | 인지 — 계약 업무는 어려운 것이 아니라 근거와 순서가 있는 일이라는 인식 전환 |
| 핵심 메시지(1문장) | 근거대로 한 걸음씩, 계약은 충분히 할 수 있다. |
| 스토리 구조 | 문제(씬1·2: 쌓이는 질문, 미로) → 전환(씬3: 빛나는 길, 법령과 선례) → 해결(씬4·5: 단계별 조문, 질문에 대한 답) → 브랜드(씬6) |

## 3. 최종 영상 정보

| 항목 | 내용 |
|---|---|
| 파일명 | 하다보면끝남_최종_v4.mp4 |
| 길이 | 32.0초 |
| 해상도 / 프레임레이트 | 1920×1080 / 30fps |
| 코덱 | H.264 / AAC |
| 구성 | 씬1~5 각 5초 + 씬6(엔딩) 7초, 씬 사이 0.5초 전환 |

## 4. 사용 도구 목록

| 구분 | 사용 도구 | 사용 목적 | 선택 이유 | 대체 도구 |
|---|---|---|---|---|
| 이미지 생성 | ChatGPT | 씬1~6 전 장면 이미지 | 레퍼런스 이미지 첨부로 같은 채팅 안에서 캐릭터·화풍 유지가 쉬움, 한국어 프롬프트 이해 | Midjourney, Ideogram, Leonardo |
| 비디오 생성 | Kling 4.0 | 씬1 이미지→영상 (5초, 720p) | Image to Video 품질이 높고 일일 무료 크레딧 제공 | Runway, Pika, Hailuo |
| 비디오 생성 | ChatGPT | 씬4 이미지→영상 | Kling 무료 크레딧 소진으로 대체 사용 (품질은 Kling보다 낮음) | Pika, Hailuo |
| 음성 생성 | ElevenLabs | 6문장 내레이션 | 한국어 지원 다국어 음성, 웹에서 바로 생성·mp3 다운로드 | Typecast, 클로바더빙 |
| 통합 편집 | Claude (ffmpeg 기반) | 컷 연결, 자막·화면 텍스트, 카메라 이동, 전환, 오디오 배치 | 설치 없이 대화로 편집 지시 가능 | CapCut, Clipchamp |

## 5. 제작 전략

- **크레딧 대응:** 이미지 6장을 먼저 확정한 뒤 영상 변환. Kling 무료 크레딧으로 씬1만 영상화하고, 나머지는 '정지 이미지 + 짧은 모션(줌·패닝·카메라 이동)'으로 구성. 씬4는 대체 도구(ChatGPT)로 영상화.
- **일관성 유지:** ① 씬1 이미지를 레퍼런스로 첨부하고 'Same character and style' 지시 ② 캐릭터 고정 문장(late 20s, short black hair, white shirt, navy cardigan) 반복 ③ 공통 스타일 문장(flat 3D illustration, muted navy and white, soft studio lighting, no text) 고정 ④ 같은 채팅에서 연속 생성
- **한글 텍스트:** 이미지 AI의 한글 깨짐을 피하려고 모든 이미지는 'no text'로 생성하고, 자막·조문·브랜드명은 편집 단계에서 삽입
- **내용 근거:** 화면 조문은 국가계약법(법률 제21418호)·시행령(대통령령 제36338호) 원문, 민법 제157조로 확인. 재단은 국가계약법 직접 적용 대상이 아니어서 씬5에 '재단은 「계약요령」 함께 확인' 주석 표기

## 6. 편집 단계에서 추가한 요소 (AI 생성물이 아닌 부분)

| 요소 | 내용 | 적용 씬 |
|---|---|---|
| 자막·화면 텍스트 | 내레이션 자막, 질문 6개, 단계 라벨, 답변 패널, 브랜드명·슬로건 | 전 씬 |
| 카메라 이동 | 정지 이미지에 줌인·줌아웃·패닝 적용 ('정지 이미지 + 짧은 모션' 전략) | 씬2·3·5·6 |
| 컷 분할 | 씬4 영상을 클로즈업·트래킹·와이드 3컷으로 재구성 | 씬4 |
| 빛 효과 | 징검다리 5개가 차례로 밝아지는 발광·빛기둥 그래픽 | 씬4 |
| 전환·오디오 | 0.5초 화면 전환, 내레이션 문장별 배치, 음량 표준화 | 전 씬 |

## 7. 도구 비교

| 목적 | 시도한 도구 | 결과 | 채택 |
|---|---|---|---|
| 이미지→영상 | Kling 4.0 (씬1) | 자연스러운 카메라 모션, 품질 우수. 단 무료 크레딧이 하루 약 1컷 분량 | 씬1 채택 |
| 이미지→영상 | ChatGPT (씬4, 3회 생성) | 1·2차: 캐릭터 잔상·그림자 발생 / 3차: 잔상은 없으나 제자리 걷기 형태 | 3차본 채택 후 편집으로 보완 |
| 내레이션 | 오픈소스 TTS (Mimic3 한국어) | 기계음, 물음표 억양 미반영, 씬2·4 발음 부정확 | 미채택 |
| 내레이션 | ElevenLabs | 자연스러운 한국어 발음과 억양 | 채택 |

## 8. 씬별 스토리보드

### 씬 1

| 필드 | 내용 |
|---|---|
| 씬 번호 / 길이 | 씬 1 / 5초 (0–5초) |
| 목표 메시지 | 계약담당자가 매일 마주하는 막막함(수의계약이냐 입찰이냐)을 한 컷에 제시한다. |
| 화면 구성 | 구도: 정면 뒷모습 미디엄샷 / 피사체: 직원 / 배경: 서류·바인더가 쌓인 사무실 / 텍스트: 있음(하단 자막) |
| 내레이션 | 수의계약일까, 입찰일까? 오늘도 질문이 쌓인다. |
| 사용 도구·목적 | 이미지: ChatGPT — 키 비주얼 + 캐릭터 기준 이미지 생성<br>영상: Kling 4.0 (Image to Video, 720p·5초) — 정지 이미지에 실제 모션 부여<br>음성: ElevenLabs — 내레이션 |
| 출력 결과 요약 | 뒷모습·서류 더미·남색/흰색 톤의 기준 컷과 카메라 푸시인 모션 영상 확보 |
| 결과 파일명 | s01_img.png / S01_motion.mp4 / voice1.mp3 |

**입력 프롬프트(원문)**

```
[이미지] Create a 16:9 image. A Korean office worker in late 20s, short black hair, white shirt, navy cardigan, seen from behind, sitting at a desk, tall stacks of documents and binders around, slightly overwhelmed but calm posture, clean flat 3D illustration, muted navy and white color palette, soft studio lighting, minimal modern office, calm and rational mood, no text, no letters, no logo
[영상] slow camera push-in, papers slightly rustling, subtle movement only
```

### 씬 2

| 필드 | 내용 |
|---|---|
| 씬 번호 / 길이 | 씬 2 / 5초 (5–10초) |
| 목표 메시지 | 계약 근거(법·시행령·예규·지침)가 너무 많아 어디서부터 봐야 할지 모르는 혼란을 보여준다. |
| 화면 구성 | 하이앵글 서류 미로 / 입구의 작은 캐릭터 / 상단 여백에 실무 질문 6개 순차 등장(수의계약? 입찰? · 1인 견적 돼? · 추정가격은 어떻게? · 나라장터 꼭 거쳐야 해? · 보증금은 몇 %? · 계약기간 첫날도 세?) / 줌아웃 / 텍스트: 있음(질문 6개, 하단 자막) |
| 내레이션 | 법, 시행령, 예규, 지침. 어디부터 봐야 할지 모르겠다. |
| 사용 도구·목적 | 이미지: ChatGPT — 씬1 이미지를 레퍼런스로 첨부해 캐릭터·화풍 고정<br>음성: ElevenLabs |
| 출력 결과 요약 | 갈림길·표지판이 보이는 미로와 질문 자막용 상단 여백 확보 |
| 결과 파일명 | s02_img.png(수정 전) / s02_img_v2.png(수정 후) |

**입력 프롬프트(원문)**

```
(수정 후 프롬프트, 수정 전/후 기록은 별도 페이지)
첨부한 이미지와 같은 캐릭터, 같은 화풍으로 16:9 이미지를 만들어줘.
[구도] 45도 정도 높은 각도에서 내려다본 넓은 장면. 화면 아래쪽 가운데에 미로 입구가 있고, 미로는 화면 뒤쪽 멀리까지 끝없이 이어져서 깊이감이 느껴져야 해.
[미로 구조] 통로가 최소 5갈래 이상으로 나뉘고, 막다른 길, 꺾이는 길, 되돌아오는 길이 섞여 있어서 한눈에 복잡한 미로로 보여야 해. 앞쪽 통로는 선명하고, 뒤로 갈수록 살짝 흐릿해져.
[벽 재질] 미로의 벽은 사람 키보다 높게 쌓은 하얀 서류 더미와 남색 바인더로 되어 있어. 서류 사이사이에 클립, 노란 포스트잇, 접힌 모서리, 끈으로 묶은 서류철, 결재판이 보이고, 몇몇 서류는 벽 위에서 살짝 흘러내려 있어. 바인더 옆면에는 글자 없는 빈 라벨만 붙어 있어.
[바닥과 소품] 바닥은 밝은 회색이고, 몇 장의 서류가 바닥에 흩어져 있어. 갈림길마다 글자 없는 작은 표지판들이 서로 다른 방향을 가리키고 있고, 어떤 표지판은 화살표가 엇갈려 있어서 혼란스러워 보여.
[캐릭터] 입구에 작게 서 있는 뒷모습. 남색 가디건, 흰 셔츠, 회색 바지. 한 손을 머리에 얹고 고개를 살짝 기울인 채 어느 길로 가야 할지 고민하는 모습. 미로에 비해 아주 작아서 미로의 거대함이 강조돼야 해.
[조명과 분위기] 위에서 부드럽게 내려오는 스튜디오 조명, 서류 벽 사이로 옅은 그림자가 지고, 전체적으로 차분하지만 막막한 분위기.
[여백] 이미지 위쪽 30%는 아무것도 없는 깨끗하고 부드러운 연회색 하늘로 비워줘.
[스타일] 깔끔한 플랫 3D 일러스트, 차분한 남색과 흰색 톤, 노란 포스트잇만 작은 포인트 색. 글자, 문자, 숫자, 로고는 절대 넣지 마.
```

### 씬 3

| 필드 | 내용 |
|---|---|
| 씬 번호 / 길이 | 씬 3 / 5초 (10–15초) |
| 목표 메시지 | 전환: 모든 절차에는 정해진 순서(법령 → 선례)가 있다는 깨달음. |
| 화면 구성 | 위에서 내려다본 미로 / 입구에서 출구까지 빛나는 한 갈래 길 / 상단에 '국가계약법 · 시행령 · 시행규칙 · 계약예규' / 아래→위 카메라 이동 / 텍스트: 있음(상단 법령 체계, 하단 자막) |
| 내레이션 | 답은 늘 같은 순서에 있다. 법령, 그리고 선례. |
| 사용 도구·목적 | 이미지: ChatGPT (레퍼런스 고정)<br>음성: ElevenLabs |
| 출력 결과 요약 | 빛나는 길이 미로를 관통하는 탑뷰 컷 확보 |
| 결과 파일명 | s03_img.png |

**입력 프롬프트(원문)**

```
Same character and style. Create a 16:9 image: top-down view of the giant paper maze, a single soft glowing path appears from entrance to exit, the worker tiny at the entrance, no text
```

### 씬 4

| 필드 | 내용 |
|---|---|
| 씬 번호 / 길이 | 씬 4 / 5초 (15–20초) |
| 목표 메시지 | 해결: 추정가격에서 대가 지급까지 근거 조문을 따라 한 단계씩 진행한다. |
| 화면 구성 | 3컷 구성 — ①발 클로즈업(추정가격·시행령 제7조) ②상반신 트래킹(계약방법·제26조, 견적·제30조) ③와이드: 징검다리 5개가 차례로 점등되며 단계·조문 표시(추정가격 제7조 → 계약방법 제26조 → 견적 제30조 → 계약보증금 법 제12조 → 검사·대가 법 제14·15조) / 텍스트: 있음(단계 라벨, 상단 자막) |
| 내레이션 | 추정가격에서 대가 지급까지, 한 걸음씩. |
| 사용 도구·목적 | 이미지: ChatGPT (레퍼런스 고정)<br>영상: ChatGPT — Kling 무료 크레딧 소진으로 대체 도구 사용<br>음성: ElevenLabs |
| 출력 결과 요약 | 제자리 걷기 형태의 보행 영상 확보(관절 생성 보행은 아님) → 편집에서 3컷으로 나눠 전진감 보완 |
| 결과 파일명 | s04_img_1.png / S04_motion3.mp4 |

**입력 프롬프트(원문)**

```
[이미지] Same character and style. Create a 16:9 image: the worker stepping forward on five glowing stepping stones in a straight line, side view, no text
[영상] Use the uploaded image as the exact visual reference. Create a 6–8 second, 16:9 cinematic 3D animation. The young man walks naturally from left to right across the glowing blue circular platforms. Animate a continuous, realistic walking cycle with alternating leg movements, proper knee and ankle articulation, natural heel-to-toe foot contact, subtle hip and shoulder motion, and gently swinging arms. His body stays balanced and moves forward smoothly. Each foot lifts, swings forward, and lands naturally on the next platform. The floating papers drift slowly in the background. Preserve the character's face, hairstyle, clothing, proportions, lighting, navy-blue background, glowing platforms, and glossy reflections. Camera remains steady in a wide shot. Smooth motion, consistent character design, no morphing, no extra limbs, no sliding feet, no sudden jumps, no cuts. End with the walking motion continuing naturally.
```

### 씬 5

| 필드 | 내용 |
|---|---|
| 씬 번호 / 길이 | 씬 5 / 5초 (20–25초) |
| 목표 메시지 | 결과: 근거가 있으면 계약 업무는 충분히 해낼 수 있다. |
| 화면 구성 | 옆모습으로 서명하는 캐릭터 / 따뜻한 창가 빛 / 왼쪽 패널에 씬2 질문의 답 4개 순차 등장(①1인 견적·2천만원 이하 시행령 제30조① ②2천만원 초과 수의·나라장터 견적 제30조② ③계약보증금 10% 이상 제50조① ④계약기간 첫날 빼고 계산 민법 제157조, ※국가계약법 기준·재단은 「계약요령」 함께 확인) / 얼굴 쪽 푸시인 / 텍스트: 있음(답변 패널, 하단 자막) |
| 내레이션 | 근거가 있으면, 충분히 할 수 있다. |
| 사용 도구·목적 | 이미지: ChatGPT (레퍼런스 고정)<br>음성: ElevenLabs |
| 출력 결과 요약 | 같은 캐릭터가 미소 지으며 서명하는 결말 컷 확보 |
| 결과 파일명 | s05_img.png |

**입력 프롬프트(원문)**

```
Same character and style. Create a 16:9 image: the worker in side profile signing a document at a tidy desk, calm confident smile, warm morning light, no text
```

### 씬 6

| 필드 | 내용 |
|---|---|
| 씬 번호 / 길이 | 씬 6 / 7초 (25–32초) |
| 목표 메시지 | 마지막 7초 동안 브랜드명과 슬로건을 각인시킨다. |
| 화면 구성 | 남색 그라데이션 배경 / 중앙 브랜드명 '하다 보면 끝남' / 슬로건 '근거대로 한 걸음씩, 계약은 충분히 할 수 있다' / 하단 '이노베이션아카데미 경영관리팀' / 글자가 아래에서 떠오르는 모션 / 텍스트: 있음(브랜드명·슬로건·기관명) |
| 내레이션 | 하다 보면, 끝난다. 이노베이션아카데미 경영관리팀. |
| 사용 도구·목적 | 이미지: ChatGPT — 로고 배경<br>음성: ElevenLabs |
| 출력 결과 요약 | 중앙이 비어 있는 남색 로고 배경 확보 |
| 결과 파일명 | s06_img.png |

**입력 프롬프트(원문)**

```
Same style. Create a 16:9 image: minimal abstract navy gradient background, subtle geometric lines suggesting a path, large empty space in the center, no text, no people
```

## 9. 프롬프트 수정 전/후 기록 — 씬2

**수정 전 프롬프트**

```
Same character and style. Create a 16:9 image: the worker as a small figure standing at the entrance of a giant maze made of paper documents, tangled arrows floating above, wide shot, no text
```

| 항목 | 내용 |
|---|---|
| 문제점 | 서류 더미가 나란히 늘어선 형태라 '미로'로 인식하기 어려웠고, 화살표 뭉치가 화면 상단 중앙을 차지해 질문 자막을 넣을 공간이 부족했다. |
| 수정 내용·이유 | 구도(45도 하이앵글, 깊이감), 미로 구조(5갈래 이상, 막다른 길), 벽 재질, 소품(글자 없는 표지판), 캐릭터 자세, 조명, 상단 30% 여백을 항목별로 지정. 목적은 '막막함'의 시각화와 자막 공간 확보. |
| 결과 변화 | 갈림길·막다른 길·엇갈린 표지판이 보여 한눈에 미로로 인식됨. 상단 여백에 질문 6개를 배치할 수 있게 됨. 캐릭터 복장은 씬1과 동일하게 유지. |

수정 후 프롬프트는 씬 2 항목 참조. 결과 이미지: 수정 전 `s02_img.png` / 수정 후 `s02_img_v2.png`
