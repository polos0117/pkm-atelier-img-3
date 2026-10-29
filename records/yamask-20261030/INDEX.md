# 데스마스 (0562 · Yamask) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 7954204 · 2026-10-29T23:17:02.202Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 562 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 409 | `108d528a0cbc` | `데스마스_light_glossy_promo_f.webp` |
| ② | heavy | ① 데스마스_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `9eafccdc3119` | `데스마스_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 데스마스_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `e2a440126980` | `데스마스_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 데스마스_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 248 | `e3039d557af6` | `데스마스_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 데스마스_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 254 | `a67be84d80ca` | `데스마스_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 데스마스_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 247 | `1c25a9c16efd` | `데스마스_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 데스마스_light_glossy_promo_f.webp | `casual1-prompt.txt` | 641 | `275085fec3e5` | `데스마스_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 데스마스_light_glossy_promo_f.webp | `casual2-prompt.txt` | 765 | `9459db76cfae` | `데스마스_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 데스마스_light_glossy_promo_f.webp | `casual3-prompt.txt` | 825 | `0d80200c0671` | `데스마스_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 욕실 · 집 | a bright bathroom with a mirror, tiles and folded towels |
| 하는 일 | 팩 하고 쉬기 · 눕기·기대 눕기 | resting with a clay mask on her face |
| 의상 계열 | 란제리풍 | tasteful lingerie-inspired fashion, fully opaque and securely fitted, with full intimate coverage |
| 옷 | 크바야 응용 레이스 | a kebaya-inspired sheer lace top with floral embroidery over a fitted camisole |

옷 종류 tank · 드러내기 mini length, cropped hem · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 미래풍 스파 · 환상 무대 | a futuristic spa of white curves and soft light |
| 하는 일 | 탕에 몸 담그기 · 앉기 | soaking in the warm water, arms resting on the rim, steam rising |
| 의상 계열 | 목욕 차림 | a bath-time wrap, robe or bathhouse loungewear that stays fully covering at chest and hips |
| 옷 | 목욕 유카타 | a light cotton bath yukata with a soft sash |

옷 종류 traditional · 드러내기 high thigh slit, open back · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 오락실 · 오락실·사진 부스 | an arcade hall of upright cabinets whose screens show only coloured glow |
| 하는 일 | 리듬 게임 발판 · 움직임 | mid-step on a rhythm game's glowing floor panels |
| 의상 계열 | 서브컬처 | a subculture street look |
| 옷 | 이모 | emo — a fitted striped long-sleeve top, a studded belt, skinny jeans and checkered sneakers |

옷 종류 trousers · 드러내기 off-shoulder neckline, bare midriff · 장면 칸 첫머리 place · 직접 입력 scene, outfit
