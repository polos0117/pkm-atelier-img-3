# 스완나 (0581 · Swanna) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 38ed730 · 2026-10-31T03:34:42.880Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 581 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 380 | `3660833c13dc` | `스완나_light_glossy_promo_f.webp` |
| ② | heavy | ① 스완나_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `c6a36ee9a853` | `스완나_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 스완나_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `40feab504ec0` | `스완나_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 스완나_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 250 | `21b746f450db` | `스완나_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 스완나_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 256 | `14a4e970dbc4` | `스완나_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 스완나_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 249 | `cfeefdaf709f` | `스완나_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 스완나_light_glossy_promo_f.webp | `casual1-prompt.txt` | 724 | `b1e21b100329` | `스완나_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 스완나_light_glossy_promo_f.webp | `casual2-prompt.txt` | 736 | `9c8617983f5b` | `스완나_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 스완나_light_glossy_promo_f.webp | `casual3-prompt.txt` | 727 | `bdf5d28fcb1a` | `스완나_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 현관 | the entryway of her home with a shoe bench, coat hooks and a long mirror |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 슬립 위 실크 로브 | a silk robe over an evening slip |
| 몸 자세 · 구도 | 쪼그려 앉기 · full_body · 옆모습 | crouching low on her heels |
| 손 · 소품 동작 | prop · natural · 헤드폰 · 목에 건 헤드폰을 잡는다 | holds one ear cup of over-ear headphones resting around her neck |

옷 종류 robe + slip · 드러내기 off-shoulder neckline, plunging neckline · 장면 칸 첫머리 action · 직접 입력 scene, outfit, custom

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 바 | a neon-lit bar counter with backlit bottles |
| 역할 | — |  |
| 의상 | 란제리풍 · 크바야 응용 레이스 | a kebaya-inspired sheer lace top with floral embroidery over a fitted camisole |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | clasp_both · clasp_both |  |

옷 종류 tank · 드러내기 bare midriff, one-shoulder cut · 장면 칸 첫머리 detail · 직접 입력 scene, outfit, custom

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 역·전철 | a city station platform or the inside of a commuter train |
| 역할 | — |  |
| 의상 | 웨딩 · 브라이덜 레이스 | a white lace bridal lingerie set with a short veil |
| 몸 자세 · 구도 | 벽에 기대 서기 · environmental · 3/4 정면 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 lingerie_set · 드러내기 high-cut leg, open back · 장면 칸 첫머리 light · 직접 입력 scene, outfit, custom
