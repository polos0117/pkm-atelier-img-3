# 아케오스 (0567 · Archeops) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 6b9f8ca · 2026-10-30T00:19:25.187Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 567 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 446 | `cf48ffe686ee` | `아케오스_light_glossy_promo_f.webp` |
| ② | heavy | ① 아케오스_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `20f585e911b4` | `아케오스_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 아케오스_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `132d808357e4` | `아케오스_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 아케오스_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 249 | `7e6b3e793c4d` | `아케오스_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 아케오스_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 255 | `cabcda9cd3b8` | `아케오스_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 아케오스_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 248 | `7907d0bf2373` | `아케오스_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 아케오스_light_glossy_promo_f.webp | `casual1-prompt.txt` | 732 | `437c5c2affa7` | `아케오스_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 아케오스_light_glossy_promo_f.webp | `casual2-prompt.txt` | 721 | `1d49c9acd533` | `아케오스_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 아케오스_light_glossy_promo_f.webp | `casual3-prompt.txt` | 679 | `2d9021adbfca` | `아케오스_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 라이브 하우스 · 밤 문화 | a small live house with a low stage, a crowd barrier and amps |
| 하는 일 | 앉아 쉬기 · 앉기 | resting on a seat for a moment, catching her breath |
| 의상 계열 | 서브컬처 | a subculture street look |
| 옷 | 이모 | emo — a fitted striped long-sleeve top, a studded belt, skinny jeans and checkered sneakers |

옷 종류 trousers · 드러내기 open back, mini length · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 해변 · 물가 | a sunny beach with wet sand and shallow surf |
| 하는 일 | 선베드에 눕기 · 눕기·기대 눕기 | lying back on a sunbed with a cold drink beside her |
| 의상 계열 | 레트로 | a period look from a past decade |
| 옷 | 70년대 디스코 | a 1970s lurex halter jumpsuit with flared legs |

옷 종류 jumpsuit · 드러내기 high thigh slit, one-shoulder cut · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 화실·공방 · 화실·공방 | an art or pottery studio of easels, clay and paint-splattered tables |
| 하는 일 | 앉아 쉬기 · 앉기 | resting on a seat for a moment, catching her breath |
| 의상 계열 | 홈웨어 | soft homewear or loungewear |
| 옷 | 원숄더 라운지 | a one-shoulder lounge top and matching soft pants |

옷 종류 trousers · 드러내기 bare midriff, strapless top · 장면 칸 첫머리 detail · 직접 입력 scene, outfit
