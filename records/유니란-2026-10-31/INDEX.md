# 유니란 (0577 · Solosis) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 76f624d · 2026-10-30T16:16:26.170Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 577 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 379 | `a47bf66baaa1` | `유니란_light_glossy_promo_f.webp` |
| ② | heavy | ① 유니란_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `56eac81d907e` | `유니란_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 유니란_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `49881de6b299` | `유니란_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 유니란_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 248 | `27254300e7bb` | `유니란_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 유니란_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 254 | `1b1789905f1d` | `유니란_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 유니란_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 247 | `e5f123599071` | `유니란_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 유니란_light_glossy_promo_f.webp | `casual1-prompt.txt` | 745 | `19491a4b8c16` | `유니란_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 유니란_light_glossy_promo_f.webp | `casual2-prompt.txt` | 659 | `862a506b9de1` | `유니란_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 유니란_light_glossy_promo_f.webp | `casual3-prompt.txt` | 799 | `e300ef35e2a0` | `유니란_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 라이브 하우스 | a small live house with a low stage, a crowd barrier and amps |
| 역할 | — |  |
| 의상 | 란제리풍 · 보디수트 | a lingerie bodysuit with a scooped neckline, wide straps and lace side panels |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 기타 · 기타를 든다 | carries an acoustic guitar by its neck at her side |

옷 종류 lingerie_set · 드러내기 plunging neckline, halter neck · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 박물관 갈라 | a grand museum hall with marble statues at night |
| 역할 | — |  |
| 의상 | 홈웨어 · 오프숄더 잠옷 셔츠 | a loose off-shoulder sleep shirt |
| 몸 자세 · 구도 | 걷기 · full_body · 3/4 정면 | walking |
| 손 · 소품 동작 | prop · down · 칵테일 잔 · 잔을 든다 | holds a cocktail glass by the stem at chest height |

옷 종류 shirt · 드러내기 off-shoulder neckline, side cutouts · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 열매 저장고 | a cool berry storeroom stacked with padded crates |
| 역할 | — |  |
| 의상 | 운동복 · 스키 재킷 + 스키 팬츠 | a fitted ski jacket and padded ski pants |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | prop · prop · 잔·컵 · 두 손으로 잔을 감싼다 | holds a cup in both hands, wrapped around its warm sides |

옷 종류 jacket + trousers · 드러내기 one-shoulder cut, strapless top · 장면 칸 첫머리 light · 직접 입력 scene, outfit
