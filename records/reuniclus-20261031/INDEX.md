# 란쿨루스 (0579 · Reuniclus) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 c66f356 · 2026-10-31T00:58:37.273Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 579 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 414 | `d2d5f86c8c33` | `란쿨루스_light_glossy_promo_f.webp` |
| ② | heavy | ① 란쿨루스_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `a027a383c4f4` | `란쿨루스_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 란쿨루스_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `f95e619db93d` | `란쿨루스_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 란쿨루스_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 248 | `9cab860e36e2` | `란쿨루스_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 란쿨루스_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 254 | `bc6acfe4846e` | `란쿨루스_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 란쿨루스_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 247 | `10a1f3bc25cf` | `란쿨루스_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 란쿨루스_light_glossy_promo_f.webp | `casual1-prompt.txt` | 729 | `69c66c86f213` | `란쿨루스_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 란쿨루스_light_glossy_promo_f.webp | `casual2-prompt.txt` | 769 | `8bdae9f87ec2` | `란쿨루스_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 란쿨루스_light_glossy_promo_f.webp | `casual3-prompt.txt` | 754 | `04dd527537fc` | `란쿨루스_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 화보 스튜디오 | an editorial photo studio with a seamless backdrop and dramatic lights |
| 역할 | — |  |
| 의상 | 레트로 · 80년대 에어로빅 | an 1980s high-cut aerobics leotard over shiny tights with leg warmers and a headband |
| 몸 자세 · 구도 | 옆으로 눕기 · full_body · 정면 | lying on her side |
| 손 · 소품 동작 | behind_head · floor_brace |  |

옷 종류 leggings · 드러내기 mini length, bare midriff · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 육상 트랙 | a running track with lane lines and a grandstand |
| 역할 | — |  |
| 의상 | 전통 의상 · 부부 | a flowing West African boubou — a wide floor-length embroidered robe with a matching head wrap |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | shush · out |  |

옷 종류 robe · 드러내기 plunging neckline, high thigh slit · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 오락실 | an arcade hall of upright cabinets whose screens show only coloured glow |
| 역할 | — |  |
| 의상 | 홈웨어 · 아침 로브 | a loosely tied robe |
| 몸 자세 · 구도 | 벽에 기대 서기 · three_quarter · 뒤 3/4 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 robe · 드러내기 halter neck, strapless top · 장면 칸 첫머리 place · 직접 입력 scene, outfit
