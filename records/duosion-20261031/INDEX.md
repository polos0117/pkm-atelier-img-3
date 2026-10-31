# 듀란 (0578 · Duosion) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 c66f356 · 2026-10-31T00:58:37.094Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 578 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 378 | `b2c8dee6e59c` | `듀란_light_glossy_promo_f.webp` |
| ② | heavy | ① 듀란_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `115fa8f718b7` | `듀란_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 듀란_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `dd5ab0bf0136` | `듀란_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 듀란_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 248 | `c6f4e2fac17f` | `듀란_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 듀란_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 254 | `6b409af2b5ee` | `듀란_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 듀란_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 247 | `c9117a37b866` | `듀란_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 듀란_light_glossy_promo_f.webp | `casual1-prompt.txt` | 761 | `3c8c2cacdcb0` | `듀란_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 듀란_light_glossy_promo_f.webp | `casual2-prompt.txt` | 698 | `bec5bec353e7` | `듀란_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 듀란_light_glossy_promo_f.webp | `casual3-prompt.txt` | 786 | `ace13ad1d0d6` | `듀란_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 화보 스튜디오 | an editorial photo studio with a seamless backdrop and dramatic lights |
| 역할 | — |  |
| 의상 | 수영복 · 딥 플런지 원피스 | a one-piece swimsuit with a deep plunging V and a secure wide waistband |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 카메라 · 카메라를 든다 | carries a camera by its grip at her side |

옷 종류 swimsuit · 드러내기 high-cut leg, plunging neckline · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 호텔 방 | a hotel suite with a city view and an open suitcase |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 해적 선장 | a pirate captain party costume — a cropped brocade coat over a cinched waist, a tricorn hat and tall boots |
| 몸 자세 · 구도 | 서기 · environmental · 옆모습 | standing |
| 손 · 소품 동작 | prop · prop · 책 · 탁자 위 책장을 넘긴다 | turns a page of a book lying open on the table |

옷 종류 coat · 드러내기 cropped hem, off-shoulder neckline · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 야영 조리장 | an outdoor cooking site at a campsite with a camp stove and a folding table |
| 역할 | — |  |
| 의상 | 평상복 · 자동 — 계열 안에서 장면에 맞게 | everyday clothes that suit the place and activity |
| 몸 자세 · 구도 | 서기 · face_close · 3/4 정면 | standing |
| 손 · 소품 동작 | cheek · out |  |

옷 종류 shirt + trousers · 드러내기 open back, one-shoulder cut · 장면 칸 첫머리 action · 직접 입력 scene, outfit
