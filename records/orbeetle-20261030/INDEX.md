# 이올브 (0826 · Orbeetle) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 e1802ac · 2026-10-29T21:27:48.736Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 826 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 429 | `ef03fc385246` | `이올브_light_glossy_promo_f.webp` |
| ② | heavy | ① 이올브_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `4abf12aa013d` | `이올브_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 이올브_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `4e7f82d3f64f` | `이올브_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 이올브_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 249 | `d551be9fe64e` | `이올브_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 이올브_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 255 | `7c8f74213edf` | `이올브_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 이올브_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 248 | `159e87b7404b` | `이올브_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 이올브_light_glossy_promo_f.webp | `casual1-prompt.txt` | 652 | `6b1ee860af3b` | `이올브_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 이올브_light_glossy_promo_f.webp | `casual2-prompt.txt` | 782 | `566cb9650c40` | `이올브_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 이올브_light_glossy_promo_f.webp | `casual3-prompt.txt` | 668 | `3f68bf4bd9a6` | `이올브_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 해변 · 물가 | a sunny beach with wet sand and shallow surf |
| 하는 일 | 천천히 거닐기 · 걷기 | strolling through the place at an easy pace |
| 의상 계열 | 레트로 | a period look from a past decade |
| 옷 | 80년대 에어로빅 | an 1980s high-cut aerobics leotard over shiny tights with leg warmers and a headband |

옷 종류 leggings · 드러내기 halter neck, mini length · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 축제 거리 · 무대·행사 | a festival street of lanterns, food stalls and paper decorations |
| 하는 일 | 행사장에서 손님 맞기 · 서기 | greeting guests at the venue with a bright smile |
| 의상 계열 | 역할극·직업 의상 | a playful adult event costume inspired by an occupation or role — clearly a costume, not a real uniform, no real insignia |
| 옷 | 이벤트 스태프 | an event staff costume with a fitted vest, name-tag ribbon and lanyard |

옷 종류 vest · 드러내기 strapless top, side cutouts · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 빨래방 · 거리·도시 | a coin laundromat late at night, rows of round machine doors |
| 하는 일 | 빨래 개기 · 앉기 | folding laundry into neat piles |
| 의상 계열 | 평상복 | everyday clothes that suit the place and activity |
| 옷 | 후디 + 레깅스 | a cropped hoodie and leggings |

옷 종류 leggings + sweater · 드러내기 halter neck, mini length · 장면 칸 첫머리 light · 직접 입력 scene, outfit
