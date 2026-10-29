# 훔처우 (0827 · Nickit) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 e1802ac · 2026-10-29T21:28:16.977Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 827 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 439 | `f789d65cbc93` | `훔처우_light_glossy_promo_f.webp` |
| ② | heavy | ① 훔처우_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `0d02f2e78d1c` | `훔처우_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 훔처우_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `a330b2bd71d1` | `훔처우_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 훔처우_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 247 | `0ffa0010a215` | `훔처우_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 훔처우_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 253 | `cadeaf05e402` | `훔처우_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 훔처우_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 246 | `1d84f5f4db52` | `훔처우_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 훔처우_light_glossy_promo_f.webp | `casual1-prompt.txt` | 893 | `1022f23d75ff` | `훔처우_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 훔처우_light_glossy_promo_f.webp | `casual2-prompt.txt` | 721 | `6aa832a0bbc6` | `훔처우_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 훔처우_light_glossy_promo_f.webp | `casual3-prompt.txt` | 750 | `5042050468ec` | `훔처우_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 오락실 · 오락실·사진 부스 | an arcade hall of upright cabinets whose screens show only coloured glow |
| 하는 일 | 천천히 거닐기 · 걷기 | strolling through the place at an easy pace |
| 의상 계열 | 서브컬처 | a subculture street look |
| 옷 | 바이커 | biker — a fitted leather riding jacket open over a bandeau top, leather trousers and boots |

옷 종류 crop_top + jacket + trousers · 드러내기 halter neck, cropped hem · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 극장·오페라 · 저녁 자리 | the grand lobby and staircase of an opera house |
| 하는 일 | 구두 벗고 쉬기 · 앉기 | sitting down after the night out, heels in one hand |
| 의상 계열 | 레트로 | a period look from a past decade |
| 옷 | 50년대 홀터 플레이수트 | a 1950s halter playsuit |

옷 종류 jumpsuit · 드러내기 high thigh slit, off-shoulder neckline · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 양궁장 · 운동 | an archery range of targets on a green field |
| 하는 일 | 물 마시며 숨 고르기 · 서기 | catching her breath with a water bottle |
| 의상 계열 | 운동복 | activewear made for the activity |
| 옷 | 자동 — 계열 안에서 장면에 맞게 |  |

옷 종류 jumpsuit · 드러내기 strapless top, one-shoulder cut · 장면 칸 첫머리 action · 직접 입력 scene, outfit
