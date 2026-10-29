# 파크로우 (0822 · Corvisquire) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 ea5e96b · 2026-10-29T12:39:29.930Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 822 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 410 | `6b2c63cf6e20` | `파크로우_light_glossy_promo_f.webp` |
| ② | heavy | ① 파크로우_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `aa228e26c199` | `파크로우_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 파크로우_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `5330d4f94afa` | `파크로우_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 파크로우_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 248 | `9fb2d4d4b038` | `파크로우_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 파크로우_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 254 | `cc694219d0c9` | `파크로우_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 파크로우_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 247 | `fcfcca534010` | `파크로우_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 파크로우_light_glossy_promo_f.webp | `casual1-prompt.txt` | 669 | `42e4924a44c3` | `파크로우_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 파크로우_light_glossy_promo_f.webp | `casual2-prompt.txt` | 694 | `b5f71387ffae` | `파크로우_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 파크로우_light_glossy_promo_f.webp | `casual3-prompt.txt` | 719 | `4f7b75e7907b` | `파크로우_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 항구 마을 지붕 테라스 · 포켓몬 세계 | a rooftop terrace above a Pokémon-world harbor town |
| 하는 일 | 별 보기 · 서기 | adjusting a small telescope to look at the stars |
| 의상 계열 | 수영복 | modern swimwear, fully lined and secure during movement |
| 옷 | 전통 문양 수영복 | a swimsuit in a heritage textile pattern with matching trim |

옷 종류 swimsuit · 드러내기 plunging neckline, open back · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 여행 물품점 · 포켓몬 직업 현장 | a wooden travel-supply shop counter with route maps and feed pouches |
| 하는 일 | 도구 정리 · 서기 | tidying her tools and supplies at the end of a shift |
| 의상 계열 | 직업복 | practical clothing for her Pokémon-world job, readable through its tools — her own original workwear — never a copy of an existing trainer, Gym Leader or Pokémon Center uniform |
| 옷 | 사육 작업복 | work overalls over a fitted tank top and rubber boots |

옷 종류 overalls + tank · 드러내기 off-shoulder neckline, mini length · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 대회 무대 · 무대·행사 | a contest or tournament stage under spotlights |
| 하는 일 | 관중석 응원 · 앉기 | clapping from a seat in the stands |
| 의상 계열 | 역할극·직업 의상 | a playful adult event costume inspired by an occupation or role — clearly a costume, not a real uniform, no real insignia |
| 옷 | 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |

옷 종류 uniform · 드러내기 one-shoulder cut, bare midriff · 장면 칸 첫머리 light · 직접 입력 scene, outfit
