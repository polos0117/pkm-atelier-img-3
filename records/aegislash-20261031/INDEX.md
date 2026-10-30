# 킬가르도 (0681 · Aegislash) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 76f624d · 2026-10-30T16:38:54.452Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 681 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 409 | `723ff9ca97a8` | `킬가르도_light_glossy_promo_f.webp` |
| ② | heavy | ① 킬가르도_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `47263c251cdc` | `킬가르도_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 킬가르도_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `103e21a5c2ba` | `킬가르도_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 킬가르도_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 249 | `cca43167d9cb` | `킬가르도_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 킬가르도_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 255 | `ea2c9c74db6b` | `킬가르도_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 킬가르도_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 248 | `9e1b6e446d2b` | `킬가르도_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 킬가르도_light_glossy_promo_f.webp | `casual1-prompt.txt` | 791 | `24fba8d0899b` | `킬가르도_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 킬가르도_light_glossy_promo_f.webp | `casual2-prompt.txt` | 680 | `1803beb3242a` | `킬가르도_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 킬가르도_light_glossy_promo_f.webp | `casual3-prompt.txt` | 719 | `7e578b35678c` | `킬가르도_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 롤러장 | a roller rink under coloured lights |
| 역할 | — |  |
| 의상 | 평상복 · 가디건 + 스커트 | a soft cardigan and a slip skirt |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · waist_up · 옆모습 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | prop · rail · 물병 · 물병을 든다 | holds a water bottle at chest height |

옷 종류 cardigan + skirt + slip · 드러내기 one-shoulder cut, off-shoulder neckline · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 골목 | a narrow city alley with hanging signboards and wet pavement |
| 역할 | — |  |
| 의상 | 레트로 · 70년대 디스코 | a 1970s lurex halter jumpsuit with flared legs |
| 몸 자세 · 구도 | 서기 · three_quarter · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · prop · 카메라 · 찍은 사진을 확인한다 | checks the photo on the back screen of a camera at chest height |

옷 종류 jumpsuit · 드러내기 high thigh slit, one-shoulder cut · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 런웨이 | a fashion runway under white spotlights |
| 역할 | — |  |
| 의상 | 란제리풍 · 자동 — 계열 안에서 장면에 맞게 | tasteful lingerie-inspired fashion, fully opaque and securely fitted, with full intimate coverage |
| 몸 자세 · 구도 | 무릎 꿇기 · chest_up · 3/4 정면 | kneeling on the ground |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 slip · 드러내기 plunging neckline, strapless top · 장면 칸 첫머리 action · 직접 입력 scene, outfit
