# 곤율랭 (0559 · Scraggy) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 d8839d6 · 2026-10-29T12:13:47.859Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 559 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 471 | `5c9d895b7dce` | `곤율랭_light_glossy_promo_f.webp` |
| ② | heavy | ① 곤율랭_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `a69bebde02a6` | `곤율랭_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 곤율랭_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `19505c0b96a5` | `곤율랭_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 곤율랭_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 249 | `25ad6ae75268` | `곤율랭_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 곤율랭_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 255 | `9add7dea1083` | `곤율랭_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 곤율랭_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 248 | `59233a7eeb2d` | `곤율랭_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 곤율랭_light_glossy_promo_f.webp | `casual1-prompt.txt` | 792 | `2126078546b4` | `곤율랭_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 곤율랭_light_glossy_promo_f.webp | `casual2-prompt.txt` | 791 | `5ad21d920dfe` | `곤율랭_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 곤율랭_light_glossy_promo_f.webp | `casual3-prompt.txt` | 836 | `c34db7d54488` | `곤율랭_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 세계 장터 · 포켓몬 세계 | a market street of a Pokémon-world town with awnings and baskets of goods |
| 하는 일 | 진열대 구경 · 서기 | browsing a shelf and pulling one item out for a closer look |
| 의상 계열 | 전통 의상 | a traditional dress that suits her, worn naturally — the traditional dress named in Outfit wins over her apparent ethnicity and the attached image's costume |
| 옷 | 사리 | a formal Indian sari — a long silk drape pleated at the waist with the pallu over one shoulder and a fitted choli |

옷 종류 traditional · 드러내기 one-shoulder cut, side cutouts · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 카페 · 거리·도시 | a neighbourhood café with a counter and window seats |
| 하는 일 | 책 읽기 · 앉기 | reading an unlettered book, one page about to turn |
| 의상 계열 | 레트로 | a period look from a past decade |
| 옷 | 70년대 롤러 디스코 | 1970s satin hot pants and a tube top |

옷 종류 trousers · 드러내기 bare midriff, halter neck · 장면 칸 첫머리 detail · 직접 입력 scene, outfit, custom

## ⑨ casual3 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 오락실 · 오락실·사진 부스 | an arcade hall of upright cabinets whose screens show only coloured glow |
| 하는 일 | 오락기 한 판 · 서기 | leaning into an upright cabinet, one hand on the stick and a coin between two fingers |
| 의상 계열 | 서브컬처 | a subculture street look |
| 옷 | 바이커 | biker — a fitted leather riding jacket open over a bandeau top, leather trousers and boots |

옷 종류 crop_top + jacket + trousers · 드러내기 cropped hem, strapless top · 장면 칸 첫머리 light · 직접 입력 scene, outfit
