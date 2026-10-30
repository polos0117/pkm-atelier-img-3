# 암멍이 (0744 · Rockruff) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 76f624d · 2026-10-30T16:37:56.251Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 744 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 401 | `2ffb6a2c2f9e` | `암멍이_light_glossy_promo_f.webp` |
| ② | heavy | ① 암멍이_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `5312767f6abd` | `암멍이_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 암멍이_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `c115ffb6526e` | `암멍이_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 암멍이_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 247 | `295b605b88d0` | `암멍이_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 암멍이_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 253 | `cafe890922d3` | `암멍이_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 암멍이_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 246 | `b5e3d2fff233` | `암멍이_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 암멍이_light_glossy_promo_f.webp | `casual1-prompt.txt` | 689 | `1a33fb583af1` | `암멍이_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 암멍이_light_glossy_promo_f.webp | `casual2-prompt.txt` | 831 | `f5c51af61bbd` | `암멍이_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 암멍이_light_glossy_promo_f.webp | `casual3-prompt.txt` | 746 | `ba5ea16ba983` | `암멍이_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 밤 택시 | the back seat of a taxi at night, city lights streaking past |
| 역할 | — |  |
| 의상 | 수영복 · 반두 비키니 | a bandeau bikini with a straight strapless top |
| 몸 자세 · 구도 | 의자에 앉기 · three_quarter · 옆모습 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 잔·컵 · 잔을 든다 | holds a cup at chest height |

옷 종류 bikini + crop_top · 드러내기 open back, bare midriff · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 주방 | her home kitchen with a counter, open shelves and hanging pans |
| 역할 | — |  |
| 의상 | 목욕 차림 · 목욕 유카타 | a light cotton bath yukata with a soft sash |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · waist_up · 3/4 정면 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | prop · prop · 반죽 그릇과 거품기 · 반죽을 섞는다 | mixes the batter in a mixing bowl of batter and a whisk on the worktable |

옷 종류 traditional · 드러내기 cropped hem, high thigh slit · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 베이커리 작업실 | a small bakery workroom with a floury wooden worktable and warm ovens |
| 역할 | — |  |
| 의상 | 서브컬처 · 자동 — 계열 안에서 장면에 맞게 | a subculture street look |
| 몸 자세 · 구도 | 서기 · chest_up · 옆모습 | standing |
| 손 · 소품 동작 | prop · out · 휴대폰 · 셀카를 찍는다 | holds a smartphone up at arm's length to take a selfie |

옷 종류 shorts + sweater · 드러내기 strapless top, side cutouts · 장면 칸 첫머리 place · 직접 입력 scene, outfit
