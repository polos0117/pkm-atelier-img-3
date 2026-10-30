# 더스트나 (0569 · Garbodor) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 148397d · 2026-10-30T10:25:54.421Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 569 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 470 | `70efa597c607` | `더스트나_light_glossy_promo_f.webp` |
| ② | heavy | ① 더스트나_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `3df3c7a90e19` | `더스트나_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 더스트나_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `aff70aa3bb87` | `더스트나_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 더스트나_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 246 | `bd293abc33a9` | `더스트나_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 더스트나_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 252 | `3fb2a079f93c` | `더스트나_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 더스트나_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 245 | `6bccf948ee1e` | `더스트나_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 더스트나_light_glossy_promo_f.webp | `casual1-prompt.txt` | 698 | `1411aef0fa7e` | `더스트나_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 더스트나_light_glossy_promo_f.webp | `casual2-prompt.txt` | 803 | `71012b7a439f` | `더스트나_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 더스트나_light_glossy_promo_f.webp | `casual3-prompt.txt` | 727 | `24527d35d9c0` | `더스트나_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 파우더룸 | a club powder room with a lit mirror and neon on the tiles |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 카지노 딜러 | a casino dealer costume with a fitted waistcoat, bow tie and cuffs |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 잔·컵 · 잔을 내려놓는다 | sets a cup down on the surface in front of her |

옷 종류 vest · 드러내기 bare midriff, cropped hem · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 나무열매 과수원 | a sunny berry orchard of small trees heavy with ripe, colorful berries |
| 역할 | — |  |
| 의상 | 평상복 · 멜빵바지 | fitted denim overalls over a cropped top |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 나무열매 바구니 · 나무열매 바구니를 팔에 건다 | carries a woven basket of berries in the crook of her arm |

옷 종류 crop_top + overalls · 드러내기 strapless top, side cutouts · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 체육관·복싱장 | a training gym with a heavy bag, ring ropes, a fencing strip and racks of weights |
| 역할 | — |  |
| 의상 | 운동복 · 자동 — 계열 안에서 장면에 맞게 | activewear made for the activity |
| 몸 자세 · 구도 | 벽에 기대 서기 · full_body · 옆모습 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 shorts + tank · 드러내기 one-shoulder cut, open back · 장면 칸 첫머리 light · 직접 입력 scene, outfit, custom
