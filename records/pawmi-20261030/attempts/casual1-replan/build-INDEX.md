# 빠모 (0921 · Pawmi) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 4d29eca · 2026-10-29T21:53:31.941Z

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
| ⑦ | casual1 | ① 빠모_light_glossy_promo_f.webp | `casual1-prompt.txt` | 754 | `a0dac2f38d40` | `빠모_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 빠모_light_glossy_promo_f.webp | `casual2-prompt.txt` | 732 | `a873a18274ec` | `빠모_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 빠모_light_glossy_promo_f.webp | `casual3-prompt.txt` | 714 | `cc0d2e0a18e1` | `빠모_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 카페 · 거리·도시 | a neighbourhood café with a counter and window seats |
| 하는 일 | 비즈 공예 · 앉기 | threading beads into a small charm with tidy craft tools |
| 의상 계열 | 레트로 | a period look from a past decade |
| 옷 | 20년대 라운지 가운 | a 1920s bias-cut satin lounge gown |

옷 종류 dress · 드러내기 plunging neckline, one-shoulder cut · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 바 · 밤 문화 | a neon-lit bar counter with backlit bottles |
| 하는 일 | 잔 들기 · 서기 | raising a glass in a toast |
| 의상 계열 | 저녁 드레스 | an evening dress or night-out outfit |
| 옷 | 슬립 위 실크 로브 | a silk robe over an evening slip |

옷 종류 robe + slip · 드러내기 plunging neckline, one-shoulder cut · 장면 칸 첫머리 — · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 현관 · 집 | the entryway of her home with a shoe bench, coat hooks and a long mirror |
| 하는 일 | 외출 전 옷매무새 · 서기 | checking her outfit in a full-length mirror before going out |
| 의상 계열 | 평상복 | everyday clothes that suit the place and activity |
| 옷 | 선드레스 + 가디건 | a sundress with a light cardigan |

옷 종류 cardigan + dress · 드러내기 high thigh slit, side cutouts · 장면 칸 첫머리 — · 직접 입력 scene, outfit
