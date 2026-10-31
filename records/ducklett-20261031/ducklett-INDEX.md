# 꼬지보리 (0580 · Ducklett) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 38ed730 · 2026-10-31T03:14:26.289Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 580 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 390 | `003a82f1ec5b` | `꼬지보리_light_glossy_promo_f.webp` |
| ② | heavy | ① 꼬지보리_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `1e8371ba43e3` | `꼬지보리_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 꼬지보리_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `99d392e68b29` | `꼬지보리_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 꼬지보리_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 250 | `8ae714e37deb` | `꼬지보리_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 꼬지보리_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 256 | `bc32de027bc6` | `꼬지보리_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 꼬지보리_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 249 | `f72291ddb741` | `꼬지보리_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 꼬지보리_light_glossy_promo_f.webp | `casual1-prompt.txt` | 882 | `193701880a36` | `꼬지보리_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 꼬지보리_light_glossy_promo_f.webp | `casual2-prompt.txt` | 808 | `ff37694f704c` | `꼬지보리_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 꼬지보리_light_glossy_promo_f.webp | `casual3-prompt.txt` | 784 | `2ae5d4754158` | `꼬지보리_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 울타리 친 풀밭 마당 | an enclosed grassy courtyard with a low wooden fence |
| 역할 | — |  |
| 의상 | 목욕 차림 · 페슈테말 | a striped cotton peshtemal wrapped like a dress |
| 몸 자세 · 구도 | 서기 · waist_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · natural · 나무열매 간식 · 동료에게 간식을 내민다 | offers a small berry treat to her companion |

옷 종류 dress · 드러내기 side cutouts, open back · 장면 칸 첫머리 action · 직접 입력 scene, outfit, custom

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 화실·공방 | an art or pottery studio of easels, clay and paint-splattered tables |
| 역할 | — |  |
| 의상 | 서브컬처 · 로맨틱 고스 | romantic goth — a black velvet dress with a corset belt and lace sleeves |
| 몸 자세 · 구도 | 서기 · chest_up · 옆모습 | standing |
| 손 · 소품 동작 | prop · out · 잔·컵 · 잔을 입에 댄다 | brings a cup to her lips |

옷 종류 dress + lingerie_set · 드러내기 high-cut leg, halter neck · 장면 칸 첫머리 place · 직접 입력 scene, outfit, custom

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 바 | a neon-lit bar counter with backlit bottles |
| 역할 | — |  |
| 의상 | 란제리풍 · 가터풍 | a lingerie set with decorative garter straps |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · environmental · 뒤 3/4 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | rail · hair_tuck |  |

옷 종류 lingerie_set · 드러내기 plunging neckline, bare midriff · 장면 칸 첫머리 detail · 직접 입력 scene, outfit, custom
