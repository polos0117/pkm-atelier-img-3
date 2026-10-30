# 고디보미 (0575 · Gothorita) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 5677b77 · 2026-10-30T13:25:50.901Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 575 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 397 | `d65d551e91f4` | `고디보미_light_glossy_promo_f.webp` |
| ② | heavy | ① 고디보미_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `8914a9fed9af` | `고디보미_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 고디보미_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `da080a31f481` | `고디보미_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 고디보미_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 248 | `1065c5f29cdf` | `고디보미_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 고디보미_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 254 | `07d7070b8ba9` | `고디보미_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 고디보미_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 247 | `c6f8b7357fc6` | `고디보미_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 고디보미_light_glossy_promo_f.webp | `casual1-prompt.txt` | 730 | `a791fe7a7c8e` | `고디보미_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 고디보미_light_glossy_promo_f.webp | `casual2-prompt.txt` | 727 | `8e3e3c54c0bc` | `고디보미_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 고디보미_light_glossy_promo_f.webp | `casual3-prompt.txt` | 695 | `74978ba87e18` | `고디보미_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 옥상 파티 | a city rooftop party under string lights |
| 역할 | — |  |
| 의상 | 란제리풍 · 자동 — 계열 안에서 장면에 맞게 | tasteful lingerie-inspired fashion, fully opaque and securely fitted, with full intimate coverage |
| 몸 자세 · 구도 | 서기 · chest_up · 옆모습 | standing |
| 손 · 소품 동작 | prop · out · 휴대폰 · 셀카를 찍는다 | holds a smartphone up at arm's length to take a selfie |

옷 종류 lingerie_set · 드러내기 plunging neckline, halter neck · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 펜트하우스 | a penthouse window wall over the city at night |
| 역할 | — |  |
| 의상 | 홈웨어 · 오프숄더 잠옷 셔츠 | a loose off-shoulder sleep shirt |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 잔·컵 · 잔을 내려놓는다 | sets a cup down on the surface in front of her |

옷 종류 shirt · 드러내기 off-shoulder neckline, side cutouts · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 레인저 초소 | a mountain-trail Pokémon ranger station with rescue gear on the wall |
| 역할 | — |  |
| 의상 | 운동복 · 자동 — 계열 안에서 장면에 맞게 | activewear made for the activity |
| 몸 자세 · 구도 | 걷기 · full_body · 3/4 정면 | walking |
| 손 · 소품 동작 | prop · natural · 몬스터볼 · 몬스터볼을 든다 | holds a Poké Ball at chest height |

옷 종류 jumpsuit · 드러내기 off-shoulder neckline, plunging neckline · 장면 칸 첫머리 light · 직접 입력 scene, outfit
