# 춤추새 (0741 · Oricorio) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 4ed601d · 2026-10-30T12:28:19.218Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 741 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 436 | `b2bce9975d86` | `춤추새_light_glossy_promo_f.webp` |
| ② | heavy | ① 춤추새_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `2581ea45064b` | `춤추새_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 춤추새_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `54b832a0f1ea` | `춤추새_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 춤추새_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 251 | `161e20e8b324` | `춤추새_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 춤추새_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 257 | `3e85742d5087` | `춤추새_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 춤추새_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 250 | `f714218269b5` | `춤추새_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 춤추새_light_glossy_promo_f.webp | `casual1-prompt.txt` | 696 | `1db05a079409` | `춤추새_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 춤추새_light_glossy_promo_f.webp | `casual2-prompt.txt` | 776 | `ec246d96bcab` | `춤추새_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 춤추새_light_glossy_promo_f.webp | `casual3-prompt.txt` | 718 | `ccb2ed6de842` | `춤추새_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 사우나 | a wooden sauna and cold plunge with a cooling lounge |
| 역할 | — |  |
| 의상 | 목욕 차림 · 목욕 유카타 | a light cotton bath yukata with a soft sash |
| 몸 자세 · 구도 | 서기 · environmental · 옆모습 | standing |
| 손 · 소품 동작 | prop · prop · 수건 · 수건으로 머리를 말린다 | dries her hair with a towel |

옷 종류 traditional · 드러내기 cropped hem, side cutouts · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 발코니 | a small balcony with potted plants, a railing and the city beyond |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 서기 · chest_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · out · 잔·컵 · 잔을 입에 댄다 | brings a cup to her lips |

옷 종류 uniform · 드러내기 open back, strapless top · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 의상 수선실 | a sewing and alteration room with a cutting table, a dress form and rolls of fabric |
| 역할 | — |  |
| 의상 | 서브컬처 · 고딕 로리타 | gothic lolita — a black-and-white lace jumper skirt with a bonnet |
| 몸 자세 · 구도 | 벽에 기대 서기 · waist_up · 정면 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 skirt + sweater · 드러내기 bare midriff, one-shoulder cut · 장면 칸 첫머리 detail · 직접 입력 scene, outfit
