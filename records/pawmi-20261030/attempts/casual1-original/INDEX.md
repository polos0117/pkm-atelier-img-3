# 빠모 (0921 · Pawmi) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 4d29eca · 2026-10-29T21:38:08.341Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 921 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 395 | `2b5c1e682246` | `빠모_light_glossy_promo_f.webp` |
| ② | heavy | ① 빠모_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `8a8e07f776ea` | `빠모_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 빠모_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `e2715f3d1132` | `빠모_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 빠모_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 246 | `1b0d4602a1f9` | `빠모_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 빠모_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 252 | `f775371305f6` | `빠모_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 빠모_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 245 | `a474be72a2cd` | `빠모_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 빠모_light_glossy_promo_f.webp | `casual1-prompt.txt` | 712 | `52fec5857a02` | `빠모_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 빠모_light_glossy_promo_f.webp | `casual2-prompt.txt` | 761 | `32917231a595` | `빠모_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 빠모_light_glossy_promo_f.webp | `casual3-prompt.txt` | 743 | `b602c1c9465f` | `빠모_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 스파 라운지 · 목욕·스파 | a quiet spa lounge of robes, herbal tea and dim lamps |
| 하는 일 | 사우나 사이 쉬기 · 앉기 | cooling down between rounds, sipping cold water |
| 의상 계열 | 수영복 | modern swimwear, fully lined and secure during movement |
| 옷 | 트라이앵글 비키니 | a triangle bikini with slider cups and tie-side bottoms |

옷 종류 bikini · 드러내기 high-cut leg, bare midriff · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 바 · 밤 문화 | a neon-lit bar counter with backlit bottles |
| 하는 일 | 잔 들기 · 서기 | raising a glass in a toast |
| 의상 계열 | 저녁 드레스 | an evening dress or night-out outfit |
| 옷 | 슬립 위 실크 로브 | a silk robe over an evening slip |

옷 종류 robe + slip · 드러내기 plunging neckline, one-shoulder cut · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 현관 · 집 | the entryway of her home with a shoe bench, coat hooks and a long mirror |
| 하는 일 | 외출 전 옷매무새 · 서기 | checking her outfit in a full-length mirror before going out |
| 의상 계열 | 평상복 | everyday clothes that suit the place and activity |
| 옷 | 선드레스 + 가디건 | a sundress with a light cardigan |

옷 종류 cardigan + dress · 드러내기 high thigh slit, side cutouts · 장면 칸 첫머리 action · 직접 입력 scene, outfit
