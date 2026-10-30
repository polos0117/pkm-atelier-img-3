# 조로아크 (0571 · Zoroark) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 35f693f · 2026-10-30T11:18:02.652Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 571 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 424 | `693ff9ab64c8` | `조로아크_light_glossy_promo_f.webp` |
| ② | heavy | ① 조로아크_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `b53430607c13` | `조로아크_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 조로아크_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `900ae1942c2d` | `조로아크_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 조로아크_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 247 | `28e167505ea5` | `조로아크_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 조로아크_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 253 | `65afdef99c87` | `조로아크_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 조로아크_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 246 | `ebc96c1242d8` | `조로아크_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 조로아크_light_glossy_promo_f.webp | `casual1-prompt.txt` | 807 | `3bfdbbfaea46` | `조로아크_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 조로아크_light_glossy_promo_f.webp | `casual2-prompt.txt` | 750 | `c25948ad517e` | `조로아크_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 조로아크_light_glossy_promo_f.webp | `casual3-prompt.txt` | 728 | `b4dae4ec2231` | `조로아크_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 길가 노점 | a small roadside stall with a counter, a juice pitcher and steaming pots |
| 역할 | — |  |
| 의상 | 직업복 · 공방 앞치마 | a work shirt under a canvas workshop apron, safety glasses pushed up |
| 몸 자세 · 구도 | 서기 · chest_up · 옆모습 | standing |
| 손 · 소품 동작 | prop · out · 몬스터볼 · 몬스터볼을 얼굴 옆에 든다 | raises a Poké Ball beside her face |

옷 종류 apron + shirt · 드러내기 bare midriff, strapless top · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 노래방 | a private karaoke room with spinning coloured lights |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 레트로 우주비행사 | a retro space-age costume — a fitted white jumpsuit with silver trim and moon boots |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 잔·컵 · 잔을 든다 | holds a cup at chest height |

옷 종류 jumpsuit · 드러내기 plunging neckline, open back · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 사막 길 | a wind-rippled desert dune trail |
| 역할 | — |  |
| 의상 | 웨딩 · 슬립 웨딩드레스 | a simple slip wedding dress with a long veil |
| 몸 자세 · 구도 | 서기 · waist_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · natural · 휴대폰 · 휴대폰을 본다 | holds a smartphone at chest height, screen toward her |

옷 종류 dress + slip · 드러내기 mini length, high thigh slit · 장면 칸 첫머리 light · 직접 입력 scene, outfit
