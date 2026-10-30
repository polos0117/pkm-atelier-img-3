# 고디탱 (0574 · Gothita) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 5677b77 · 2026-10-30T13:25:50.514Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 574 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 409 | `16ede042c735` | `고디탱_light_glossy_promo_f.webp` |
| ② | heavy | ① 고디탱_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `cde4e18d4a2a` | `고디탱_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 고디탱_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `4c999739c346` | `고디탱_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 고디탱_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 248 | `289ee20166f5` | `고디탱_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 고디탱_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 254 | `a2a4ea777f8b` | `고디탱_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 고디탱_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 247 | `f256e3fc02d4` | `고디탱_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 고디탱_light_glossy_promo_f.webp | `casual1-prompt.txt` | 685 | `c8b002610031` | `고디탱_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 고디탱_light_glossy_promo_f.webp | `casual2-prompt.txt` | 738 | `d781c072aae5` | `고디탱_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 고디탱_light_glossy_promo_f.webp | `casual3-prompt.txt` | 788 | `265756af903b` | `고디탱_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 옥상 파티 | a city rooftop party under string lights |
| 역할 | — |  |
| 의상 | 레트로 · 50년대 핀업 란제리 | a 1950s pin-up lingerie set with a structured bra and high-waisted bottoms |
| 몸 자세 · 구도 | 의자에 앉기 · full_body · 옆모습 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 칵테일 잔 · 잔을 든다 | holds a cocktail glass by the stem at chest height |

옷 종류 lingerie_set · 드러내기 high-cut leg, halter neck · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 옥상 | a city rooftop with a water tank, string lights and the skyline |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 턱시도 재킷 + 캐미솔 + 정장 바지 | a sharp tuxedo jacket over a silk camisole with tailored trousers |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | v_sign · out |  |

옷 종류 jacket + tank + trousers · 드러내기 halter neck, bare midriff · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 보드게임 라운지 | a cozy board-game lounge with shelves of game boxes and low tables |
| 역할 | — |  |
| 의상 | 수영복 · 랩 프론트 | a wrap-front swimsuit with a crossed bodice tied at the waist |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 잔·컵 · 잔을 든다 | holds a cup at chest height |

옷 종류 swimsuit · 드러내기 high-cut leg, strapless top · 장면 칸 첫머리 light · 직접 입력 scene, outfit
