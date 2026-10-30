# 에블리 (0742 · Cutiefly) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 4ed601d · 2026-10-30T12:54:44.758Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 742 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 418 | `a0a7a195cebd` | `에블리_light_glossy_promo_f.webp` |
| ② | heavy | ① 에블리_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `1b9c6db090a1` | `에블리_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 에블리_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `1afb1421f489` | `에블리_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 에블리_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 249 | `787e38d392b2` | `에블리_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 에블리_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 255 | `df8dba4412c0` | `에블리_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 에블리_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 248 | `e3896a5b6e4a` | `에블리_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 에블리_light_glossy_promo_f.webp | `casual1-prompt.txt` | 829 | `896e2099a324` | `에블리_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 에블리_light_glossy_promo_f.webp | `casual2-prompt.txt` | 729 | `c2a10bd250ea` | `에블리_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 에블리_light_glossy_promo_f.webp | `casual3-prompt.txt` | 654 | `e3a0ce10bb32` | `에블리_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 리조트 카바나 | a resort cabana with a shaded daybed by the water |
| 역할 | — |  |
| 의상 | 전통 의상 · 자동 — 계열 안에서 장면에 맞게 | a traditional dress that suits her, worn naturally |
| 몸 자세 · 구도 | 의자에 앉기 · face_close · 3/4 정면 | seated on a chair |
| 손 · 소품 동작 | prop · out · 칵테일 잔 · 잔을 입에 댄다 | brings a cocktail glass to her lips |

옷 종류 blouse · 드러내기 cropped hem, mini length · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 레드카펫·시상식 | a red carpet and award hall with camera flashes |
| 역할 | — |  |
| 의상 | 평상복 · 멜빵바지 | fitted denim overalls over a cropped top |
| 몸 자세 · 구도 | 서기 · waist_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · pocket · 꽃다발 · 꽃다발을 든다 | holds a small bouquet at chest height |

옷 종류 crop_top + overalls · 드러내기 side cutouts, open back · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 클럽 | a nightclub with a dance floor under moving coloured lights and a velvet-rope queue at its door |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 이벤트 스태프 | an event staff costume with a fitted vest, name-tag ribbon and lanyard |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · three_quarter · 정면 | perched on a ledge or edge |
| 손 · 소품 동작 | edge_brace_both · edge_brace_both |  |

옷 종류 vest · 드러내기 cropped hem, halter neck · 장면 칸 첫머리 light · 직접 입력 scene, outfit
