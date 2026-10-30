# 쌍검킬 (0680 · Doublade) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 76f624d · 2026-10-30T16:31:51.957Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 680 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 419 | `9e42dab9c09f` | `쌍검킬_light_glossy_promo_f.webp` |
| ② | heavy | ① 쌍검킬_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `88e3783526cf` | `쌍검킬_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 쌍검킬_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `f8144a7163d4` | `쌍검킬_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 쌍검킬_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 249 | `a85e74e57e04` | `쌍검킬_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 쌍검킬_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 255 | `d9c7605174af` | `쌍검킬_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 쌍검킬_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 248 | `9499b7c14520` | `쌍검킬_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 쌍검킬_light_glossy_promo_f.webp | `casual1-prompt.txt` | 714 | `c5b05327a679` | `쌍검킬_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 쌍검킬_light_glossy_promo_f.webp | `casual2-prompt.txt` | 796 | `b92f5978a3cd` | `쌍검킬_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 쌍검킬_light_glossy_promo_f.webp | `casual3-prompt.txt` | 717 | `d241630883d6` | `쌍검킬_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 배틀 스타디움 | the stands of an open-air Pokémon battle stadium above a marked battle court |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 가운 + 이브닝 코트 | a long gown under an evening coat |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 몬스터볼 · 몬스터볼을 든다 | holds a Poké Ball at chest height |

옷 종류 coat + dress · 드러내기 high thigh slit, off-shoulder neckline · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 세계 부엌 | a sunny home kitchen in a Pokémon-world town, bowls of berries on the counter |
| 역할 | — |  |
| 의상 | 직업복 · 글래머 앞치마 룩 | a sleek fitted wrap dress under a crisp short apron |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | shush · out |  |

옷 종류 apron + dress · 드러내기 plunging neckline, mini length · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 스티커 사진기 | an arcade photo-sticker booth under bright ring lights |
| 역할 | — |  |
| 의상 | 레트로 · 70년대 디스코 | a 1970s lurex halter jumpsuit with flared legs |
| 몸 자세 · 구도 | 서기 · waist_up · 뒤 3/4 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 jumpsuit · 드러내기 high thigh slit, off-shoulder neckline · 장면 칸 첫머리 detail · 직접 입력 scene, outfit
