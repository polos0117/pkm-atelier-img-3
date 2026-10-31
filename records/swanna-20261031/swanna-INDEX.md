# 스완나 (0581 · Swanna) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 38ed730 · 2026-10-31T03:14:27.441Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 581 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 380 | `3660833c13dc` | `스완나_light_glossy_promo_f.webp` |
| ② | heavy | ① 스완나_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `c6a36ee9a853` | `스완나_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 스완나_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `40feab504ec0` | `스완나_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 스완나_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 250 | `21b746f450db` | `스완나_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 스완나_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 256 | `14a4e970dbc4` | `스완나_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 스완나_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 249 | `cfeefdaf709f` | `스완나_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 스완나_light_glossy_promo_f.webp | `casual1-prompt.txt` | 705 | `0ef4b3f14c36` | `스완나_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 스완나_light_glossy_promo_f.webp | `casual2-prompt.txt` | 699 | `943c1e45d2e1` | `스완나_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 스완나_light_glossy_promo_f.webp | `casual3-prompt.txt` | 791 | `26cc38df4e47` | `스완나_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 현관 | the entryway of her home with a shoe bench, coat hooks and a long mirror |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 슬립 위 실크 로브 | a silk robe over an evening slip |
| 몸 자세 · 구도 | 쪼그려 앉기 · full_body · 옆모습 | crouching low on her heels |
| 손 · 소품 동작 | prop · natural · 헤드폰 · 목에 건 헤드폰을 잡는다 | holds one ear cup of over-ear headphones resting around her neck |

옷 종류 robe + slip · 드러내기 off-shoulder neckline, strapless top · 장면 칸 첫머리 place · 직접 입력 scene, outfit, custom

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 바 | a neon-lit bar counter with backlit bottles |
| 역할 | — |  |
| 의상 | 수영복 · 크로셰 비키니 | a fully lined crochet-knit bikini in a sunny resort colour |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 칵테일 잔 · 잔을 든다 | holds a cocktail glass by the stem at chest height |

옷 종류 bikini · 드러내기 high-cut leg, side cutouts · 장면 칸 첫머리 detail · 직접 입력 scene, outfit, custom

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 역·전철 | a city station platform or the inside of a commuter train |
| 역할 | — |  |
| 의상 | 웨딩 · 자동 — 계열 안에서 장면에 맞게 | bridal wear |
| 몸 자세 · 구도 | 벽에 기대 서기 · waist_up · 정면 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 slip · 드러내기 one-shoulder cut, mini length · 장면 칸 첫머리 action · 직접 입력 scene, outfit, custom
