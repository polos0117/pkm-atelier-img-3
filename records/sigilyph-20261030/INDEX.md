# 심보러 (0561 · Sigilyph) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 5466246 · 2026-10-29T15:49:35.912Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 561 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 411 | `6b6d2c505428` | `심보러_light_glossy_promo_f.webp` |
| ② | heavy | ① 심보러_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `5cec6325e995` | `심보러_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 심보러_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `eb0a1c913115` | `심보러_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 심보러_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 250 | `dad015501bcc` | `심보러_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 심보러_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 256 | `3584a5afb024` | `심보러_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 심보러_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 249 | `8cc7591cec53` | `심보러_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 심보러_light_glossy_promo_f.webp | `casual1-prompt.txt` | 792 | `f85d4eeff977` | `심보러_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 심보러_light_glossy_promo_f.webp | `casual2-prompt.txt` | 632 | `7b2d72a35256` | `심보러_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 심보러_light_glossy_promo_f.webp | `casual3-prompt.txt` | 729 | `ee2c218a0ba7` | `심보러_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 밤 택시 · 밤 문화 | the back seat of a taxi at night, city lights streaking past |
| 하는 일 | 구두 벗고 쉬기 · 앉기 | sitting down after the night out, heels in one hand |
| 의상 계열 | 저녁 드레스 | an evening dress or night-out outfit |
| 옷 | 가운 + 이브닝 코트 | a long gown under an evening coat |

옷 종류 coat + dress · 드러내기 strapless top, mini length · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 화실·공방 · 화실·공방 | an art or pottery studio of easels, clay and paint-splattered tables |
| 하는 일 | 야근 커피 · 앉기 | late at night with her feet up on the chair, coffee held in both hands |
| 의상 계열 | 홈웨어 | soft homewear or loungewear |
| 옷 | 아침 로브 | a loosely tied robe |

옷 종류 robe · 드러내기 plunging neckline, side cutouts · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 거실 · 집 | her living room with a deep sofa, floor cushions and a low table |
| 하는 일 | 바닥에 누워 웃기 · 눕기·기대 눕기 | lying back on the floor after a long session, laughing at the ceiling |
| 의상 계열 | 란제리풍 | tasteful lingerie-inspired fashion, fully opaque and securely fitted, with full intimate coverage |
| 옷 | 브라렛 + 하이웨이스트 | a soft-cup bralette with wide straps and matching high-waisted bottoms |

옷 종류 crop_top · 드러내기 bare midriff, open back · 장면 칸 첫머리 detail · 직접 입력 scene, outfit
